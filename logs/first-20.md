# First 20 Hours

This is a documentation of my attempts to implement the ["first 20 hours"](https://www.youtube.com/watch?v=5MgBikgcWnY) method for learning new skills. Below is a list of several topics of interest and progress I have made on them. I plan to run a few in parallel at a time. However, if I start something, it is important that I quit immediately or see it through to the end.

##  Phylogenetic Models

Goal: Understand some papers of Roch, Daskalakis, Mossel. Understand connections of these phylogenetic models to stochastic block models (Kesten-Stigum threshold).

### Resources

1. [Lecture notes by Sebastian Roch](https://www.math.wisc.edu/~roch/evol-gen/index.html)
2. [Optimal Phylogenetic Reconstruction](https://arxiv.org/abs/math/0509575v1) by Daskalakis, Mossel, and Roch.
3. [Paper on likelihood-based methods for phylogeny](https://arxiv.org/pdf/1508.01964.pdf) by Roch and Sly.
4. Noisy population recovery?

### Progress

- April 3, 2020: [2:45]. Set up the above. Started on Roch lecture notes, but found them too dense and without motivation. Watched [a Simons Institute lecture](https://www.youtube.com/watch?v=CexALZI_500) which was helpful and handwrote some notes. Already found some interesting open problems. Next step is to dig into some of the details of lecture notes.
- April 4, 2020: [1:20]. Skimmed Roch's notes for lectures 8-12. I think I developed some intuition for broadcasting on trees. I started reading introduction of [Roch-Sly 2018](https://arxiv.org/pdf/1508.01964.pdf). Basically, they analyze the MLE, even though performance guarantees for other algorithms were known previously (see references therein). They prove a phase transition in upper bounds on the sample complexity of the MLE with respect to a certain parameter $g$; it is open to supply lower bounds and pin down the true transition point $g^*$. I need to search more to see if there are any suspected stat-comp gaps. It will be very interesting if we can make a connection back to the existing stat-comp gap literature. I would also recommend skipping Part 2 of Roch's notes; I think it is better to just watch the Simons Institute bootcamp videos. Pretty soon, I should be able to start reading papers.
- April 5, 2020: [1:00]. Almost finished analysis of majority statistic for ancestral reconstruction, corresponding to lecture 11.
- April 7, 2020: [0:30]. Finished analysis of majority statistic and started skimming the analysis of the MLE.
- April 8, 2020: [1:00]: Finished majority statistic and skimmed analysis of MLE; I think I get the main ideas but the calculations are annoying. Trying to replicate the details really slows me down. I need high-quality exercises that are actually instructive and don't just rely on some symbol manipulation tricks. I am not sure where I want to go next.


## Quantum information

Goal: Understand the role of SoS in quantum information theory.

### Resources

1. [Barak-Kothari-Steurer 2017 paper](https://arxiv.org/abs/1701.06321).
2. [BBWKSZ 2012 paper](https://arxiv.org/abs/1205.4484).
3. [Harrow-Natarajan lecture notes](http://www.mit.edu/~aram/teaching/sdp/).
4. [ABMB book](http://math.univ-lyon1.fr/~aubrun/ABMB/ABMB.pdf). (Advanced; to be used only as a reference)
5. [Harrow course lecture notes](http://web.mit.edu/8.371/www/).
6. Even more targeted notes on entanglement by [Brandao et al.](https://arxiv.org/abs/1604.01790).
7. [School on mathematics of quantum computation](https://iias.huji.ac.il/SchoolCSE4). Lots of good exercises.


### Progress

- April 3, 2020: [1:20]. Skimmed over Harrow-Natarajan notes, but didn't learn all that much. Wasn't all that focused. Then tried to review QIT from ABMB book, but realized that book is too advanced (for now). Instead, Harrow's lecture notes (lectures 1 and 2) should be sufficient.
- April 4, 2020: [1:45]. Watched [talk](https://www.youtube.com/watch?v=DKGmTnZooEI) on BKS17 paper. I noticed that no knowledge of quantum information is required to understand this paper. This paper has lots of valuable technical ideas. The only value in learning about QIT is to be able to extract new computational problems for which SoS might give improved guarantees or which might be related to HoA/UGC/SSE. Started on Brandao et al. lecture notes.
- April 5, 2020: [1:10]. Finished lecture 1 in Brandao et al. notes. Don't fully understand partial trace yet. Will try to move through introductory material faster, then slow down on the real core topics.
- April 7, 2020: [0:35]. Skimmed over lectures 1-3 and started reading about entanglement distillation, dilution and the quantum marginal problem. These topics are very interesting; I want to understand them in more detail. Also, today I noticed that my initial motivation has run dry. However, since I promised, I will complete the full 20 hours (for both this and the phylogeny projects). In the future, I need to be more careful about committing to a project.
- April 8, 2020: [1:00]. Switched over to first lecture by Or Sattath in HUJI school. I don't plan to take too many notes but do want to do a reasonable number of exercises. I switched because I realized I probably won't learn anything of lasting value if I just go through the lecture notes.


## Sampling from continuous state spaces

## Sampling from discrete state spaces

## Large deviations

## Geometry of polynomials

## UGC, HoA, CSPs

## Message passing, BP, and statistical physics methods

## Stochastic processes

BM, Martingales, Stochastic calculus

## Review of probability

Conditional E, convergence theorems, Stein's method, Characteristic functions

## Control theory

## Convex geometry

## SoS Upper Bounds

## SoS Lower Bounds

## SoS Theory

## Convex optimization

## Iterative methods

## Lattices

## Algebraic statistics


## Optimal transport

https://chewisinho.github.io/drp-2020
