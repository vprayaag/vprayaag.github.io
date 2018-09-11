---
layout: default
---

# Variational inference

### Basic overview
In Bayesian inference, we observe data $x$ and we want to infer hidden variables $z$. A priori, we posit that the connection between the two is given by the joint distribution $p(x,z)$.

We are interested in the posterior distribution:
$$
p(z | x) = \frac{p(z,x)}{p(x)}.
$$

The numerator $p(x,z)$ is easy to compute: just write $p(x,z) = p(x | z) p(z)$. The first term, **the likelihood**, is easy to compute; this is just follows by definition of the generative model. The second term, **the prior**, is our a priori belief about $z$; it encodes the uncertainty about it we have before anything happens.

The denominator, called **the evidence**, is hard to compute because we need to sum over all configurations $z$. It is related to the partition function. From now on, the goal is to compute (maybe approximately) this quantity.

To do so, we approximate the posterior by some family of distributions $\{q_\lambda\}_\lambda$, where $\lambda \in \Lambda$ is some parameter we have introduced to succinctly identify a particular distribution from the family.

Having chosen the family, the natural thing to do is the pick the distribution in it which is "closest" to the posterior. One way to do this is to minimize the KL divergence $KL(q_\lambda(z) || p(z | x))$. Unfortunately, optimizing this objective function is still too hard.

It turns out that one can show that:
$$
KL(q_\lambda(z) || p(z | x)) = \log p(x) - L(\lambda),
$$
where $L(\lambda) = \mathbb{E}_q[\log p(x,z)] + S(q)$ is called the **ELBO (evidence lower bound)** and $S$ is the Shannon entropy. Rearranging:
$$
\log p(x) = KL(q_\lambda(z) || p(z | x)) + L(\lambda) \geq L(\lambda)
$$

It turns out that optimizing $L$ is more tractable because it involves quantities that we know. In terms of statistical physics, the ELBO exactly seeks to balance minimizing energy while maximizing entropy (in the same way as the free energy).

There are several drawbacks of this approach:
- Blindly optimizing $L$ does not tell us quantitatively how far or close we are from the log-partition function.
- We need to decide on a family of distributions beforehand. If we choose a powerful family of distribution, then there may exist a distribution in it which contains the posterior or something close to it, but then optimizing $L$ may become hard. On the other hand, choosing an easy to optimize family may not be strong enough; in other words, even the best distribution in that family may not be close (in KL divergence) to the true posterior.

### Resources
- [A blog post by Jaan Altosaar](https://jaan.io/how-does-physics-connect-machine-learning/) - easy to read
- **TODO**: [A much more rigourous survey paper](https://arxiv.org/pdf/1601.00670.pdf) - contains actual examples of deriving the ELBO for specific models, and explains how to optimize it.

### Future directions
1. Instead of fixating on the KL divergence, why not choose some other measure of closeness? There may an alternative which has better tradeoffs between efficiency and approximation power. See [this paper](https://arxiv.org/abs/1610.09033).
2. The ELBO is quite general in the sense that it holds for all posteriors; we made no assumption on its structure. Can we develop better approximations for only a specific class of posteriors? Ideally, this class of posteriors would also include practically interesting posteriors of models that are actually used.
3. At a very general level, it might be useful to try and transfer statistical physics tools for computing partition functions over the the inference setting.
# Kac-Rice Formula

---
# BRAIN DUMP BELOW
---

9/10/18: Talk to Prof. Lu about the Kac-Rice formula. It is a tool for computing the number of local optima of a random objective function. So far, there are only two results I know of which use this tool. It would be a good class project to learn about this tool and its applications. There are potentially close connections with counting complexity.

1. Prof. Lu mentioned this result in the context of initialization methods for gradient descent applied to a formulation of the phase retrieval problem.
2. Tengyu Ma used it to understand the optimization landscape of tensor decomposition. See https://arxiv.org/abs/1706.05598

Another potentially related paper, is by Ankur Moitra: https://arxiv.org/abs/1610.04317 This is also related to counting.

# Provable algorithms for computing partition functions

In general, computing partition functions are hard. However, they are very practically relevant, so people just use some heuristics. There has been some work on designing approximation algorithms. There are two classes of algorithms: MCMC and Variational Methods.

For MCMMC, here are two classic, nice papers:
- Mark Jerrum and Alistair Sinclair.  Polynomial-time approximation algorithms for the ising model.
- Mark Jerrum, Alistair Sinclair, and Eric Vigoda.  A polynomial-time approximation algorithm for the permanent of a matrix with nonnegative entries.

In the real world, people actually use variational methods, which converts the problem to an optimization problem using the Gibbs principle. Essentially, one must optimize over the set of probability distributions on some set like {0,1}^n, which is hard. So, people use heuristics instead.

One heuristic is the mean field approximation. Basically, one solves a simpler optimization problem and hopes that the answer is close to the true partition function. The [following paper:][jain-mean-field-2018] tries to be more rigorous. They prove theorems about the quality of the mean field approximation and also design algorithms for the mean field approximation.

One potential open direction: the algorithms and theorems are all very general, but the running time bounds are completely impractical (Note: these are just upper bounds, so I don't know if the algorithms might run faster in practice). It would be interesting to do the opposite of this paper -> restrict the model until we can get a provably FAST algorithm. What is the most interesting model for which we can prove bounds which might actually be practical?

Returning to the idea that variational methods involve optimizing over probability distributions, this paper https://arxiv.org/pdf/1607.03183.pdf (see also video on youtube) recalls that convex programming hierarchies are a perfect tool to do this task. The conclusion of this paper describes many open problems, most of which I don't understand. I think this paper is simple at its core, I just don't understand the terminology yet. At a high level, they have to do with exploring the algorithms in different parameter regimes. As before, the running time bounds are impractical, so it would be interesting to see in what special cases they can be sped up. Also, it is known that once a convex programming hierarchy algorithm exists, once can design fast spectral algorithms (see: https://arxiv.org/abs/1512.02337) that might be practical. This is especially the case if the hierarchy is used to prove a theorem, after which being true, it is easier to find a fast algorithm (Note: this is known for SoS, what about other hierarchies?).

Further comments on the following paper: https://arxiv.org/pdf/1607.03183.pdf

First, a followup, maybe slightly easier to understand paper is https://arxiv.org/pdf/1808.07226.pdf

The core idea of these papers is quite simple: we want to approximate log Z, so we use Gibbs variational principle to rewrite it as the opt. value of an optimization problem over the set of distributions over {0,1}^n. Then, the SA hierarchy is designed exactly to solve these kinds of problems. Basically, no new tools are developed: powerful (and complicated) machinery from the hierarchies literature are just applied as a black box.

Essentially, they prove theorems about the quality of various relaxations of log Z as well as give algorithms for solving those relaxations. It turns out that even the relaxations are quite hard to solve.

The hardest part of the paper is exactly that the inner workings of the black box are hard to understand. Furthermore, the open problems posed in these paper seem very complicate; they are all related to the power of the hierarchies and are closely connected with other problems related to hardness of approximation.

Additionally, there are strong lower bounds that have been proven, meaning that it is quite unlikely one can even get away with worse approximation factor but faster run time. I only seem to have two potentially interesting questions:

1. What is the dual and its interpretation in the context of the Gibbs variational characterization of $\log Z$?
2. Can we restrict the class of Ising models to something simpler for which the problem becomes much easier (i.e. doesn't require these hierarchies?) Do hardness results extend to "practically interesting" classes of Ising models? It might be useful to look into some of the popular Ising models used in machine learning papers (see David Blei) and try to design faster algorithms (inspired by the Risteski papers)?
3. Related to the previous problem, for what special cases of Ising models is it the case that (for example) the mean field approximation is even more accurate than proven in these Risteski papers?
4. What do the "hard" Ising model instances look like? Is there some property of the underlying graph or the edge weights which make it hard?

Looking forward, this may be an easy introduction to some relevant ideas: https://jaan.io/how-does-physics-connect-machine-learning/

Also, this project may be a much more long term one, as it will help a lot once I learn more in 6.438 and AM 254

---
[jain-mean-field-2018]: https://arxiv.org/pdf/1802.06126.pdf
