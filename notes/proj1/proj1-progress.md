---
layout: default
---

---
# BRAIN DUMP BELOW
---

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
