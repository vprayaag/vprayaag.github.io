# August 2020


## August 10, 2020
Went to sleep a bit late last night.

- \[6:45-9:27\]: Wrote down logs for last two days. Identified sections of Filmus's notes to read and problems to do for next time. Along the way, got distracted by some really interesting papers related to PCPs such as [this one](https://www.dcs.warwick.ac.uk/~tomgur/pdf/dist_proofs.pdf). Cleaned out email and dealt with various bureaucratic things. Checked library books. Here is a list of projects I am working on.

  - Faster covariance estimation: We need to check that solving this degree 4 polynomial optimization problem directly and approximately plugs into our mean estimation framework. Currently, we don't get the correct interpolation between exponential time, optimal rate and polynomial time rate. I also think it would be quite interesting to see what this has to say about not exploiting SoS certifiable hypercontractivity. Hopefully can meet with Fred this week.
  - Subcube conditioning/correlation rounding: I think I can simplify their result by exploiting the approximate product structure of random restrictions guaranteed by correlation rounding. I feel there are more applications of correlation rounding here and that there might be some insight by thinking about it in terms of AoBF. More generally, this regularity approach for probability distributions seems like it should have more algorithmic applications. Hopefully can meet with Fred this week and then try to see if Paris is interested too.
  - Estimating partition functions: Currently, I need to analyze an inner product term for bounding the TRW approximation. I should start by trying to do it in some special case. I also want to study notions of entropy that are well-defined for pseudodistributions and try to set up a meeting with Boaz, Pravesh and Jeff. Next, I want to understand the Bethe approximation better and when one might expect to be accompanied by an efficient algorithm. Want to meet with Andrej, Jeff, and Andrej's student some time soon. Can we do rounding of pseudodistributions to tree-like (pseudo)distributions?
  - Coupling: I have some nontrivial calculations. Will try to meet with Sidhanth this week and then meet with Prasad. One issue is that I can only lower bound expected correlation with respect to some abstract coupling, not the independent coupling. Also, I need to see whether the actual contraction proof that involves coupling works out for pseudodistributions; it involves some conditioning and such.
- \[1:10-2:47\]: Attended BM reading group and learned about using Eldan's stochastic calculus approach to prove correlation inequalities. I didn't follow a lot of this talk, especially the discussion at the end on using level-k inequalities. I did get the high-level approach, but don't yet have a good intuition for correlation inequalities. I think they might be useful for correlation rounding.

### Summary of July 28 - August 9

- \[32:14\]: Statistical physics stuff.
  - Tried to improve JKR STOC19 paper directly by proving stronger correlation rounding result for specific graphs. Never actually dived deep on this.
  - More open problems: prove BP actually converges fast, Galanis et al. counting solutions to random formulas vs. finding them. Encountered convexified version of Bethe approximation.
  - Did skimming of MM Chapter 14 to become more comfortable with BP and Bethe.
  - Attempted to prove error bound for convexified Bethe approximation.
  - Rounding into tree-like distributions: Had a simplistic idea of deleting vertices to make a graph approximately tree like (no short cycles), but this can't work in general. Didn't know how to make rigorous.
  - Watched talk by Pravesh on Barak-Kothari-Steurer because I thought a new rounding algorithm might be useful.
  - Realized broader importance of entropy surrogates for pseudodistributions.
  - Read and thought about Boaz's essay on structure vs. combinatorics. Had some bigger picture questions and understand why we care about statistical physics and phase transitions in the first place. Definitely want to think more about proof systems, crypto and average case complexity in the future.
  - Watched Pravesh's talk on list-decodable linear regression. Got a little bit stuck in the talk, but still had some takeways. Realized that list-decodability not applicable to certifying clusters of Gibbs distribution because we don't have an appropriate notion of succinct proof for distributions.
  - Attended Tselil's talk in MINDS seminar. Realized that there are quite a few opportunities in this area (average case reductions between problems and between algorithms).
  - Got stuck on Coja-Oghlan and Dembo-Montanari papers. I feel these papers are impenetrable right now.
  - Got interested in subcube conditioning and have some thoughts about how to maybe simplify existing algorithm.
- \[5:57\]: Covariance estimation.
  - Learned about BKS QPTAS for injective tensor norm from Moitra lecture.
  - Explored connections between combinatorial and spectral center. We just need to approximate spectral center. Looked into literature on approximating injective tensor norms.
  - Got brute force idea from Boaz; I think it works but need to plug it in and turn the cranks. It gives us something nontrivial, but not ideal.  
- \[12:06\]: Other stuff.
  - Met with Prasad, got some ideas.
  - Met with Sidhanth, started discussing coupling in more detail.
  - Fleshed out coupling idea on my own. Did some digging in Levin-Peres-Wilmer book on coupling.
  - Reading groups

### Reflections

- Go to sleep on time
- Defend the morning session. There were a few days where I got distracted and didn't have a clear train of thought
- I didn't actually learn that many concrete tools and didn't read that many textbook pages.
- My meetings with Jeff were not very productive. I don't really remember what I take away at the end of each meeting.
- I spent a lot of time digging around the literature to see if a problem was a good one.
- I did encounter a lot problems. Next time, I think it might be better to just assess them first and just pick the one or two which are most promising. Then I can investigate those deeply. This is in contrast with doing a shallow exploration "around" many of them, without diving too deep.
- I feel that I spend a lot of time going around in circles only to arrive at a conclusion I could have arrived at in the beginning.
- When reporting what I did here, I want to be a bit more precise. When I "thought" about something, what was the main question I struggled with or what was the main takeaway message? I think this is a good practice that may help me pick up where I left off more easily.

## August 9, 2020

- \[6:30-9:00\]: Continued on the same paper. Understood the edge tester. Thought about what is the tradeoff in conditioning on more or less variables. Realized that I might be able to simplify the recursion part of the algorithm by exploiting approximate product structure of random restrictions. Formally, want to prove that if a distribution is approximately product-like and far from uniform, then its mean must have large norm. Also realized that random restriction is exactly the object to study in correlation rounding. As a next step, I want to see if using AoBF can give anything.
- \[1:40-2:55\]: AoBF reading group. I gave an impromptu explanation of what I was learning about in subcube conditioning paper. I realized that I don't understand Pisier's inequality all that well; maybe it is some type of isoperimetric inequality. Started to feel like maybe AoBF is a good investment.

## August 8, 2020

- \[7:24-8:30\]: Thought about partition functions project. In particular, tried to remember where we left off with regards to Bethe approximation. Thought about TRW approximation, but just felt a bit stuck.
- \[8:30-10:02\]: Started reading [this paper](https://arxiv.org/abs/1911.07357) because I think it has some connections to correlation rounding. Was a bit slow in picking up their notation, but sort of get the high level idea.
- \[2:00-3:00\]: (forgot exact times) Continued reading the same paper. Went off on my own tangent and started thinking about whether we can simplify the recursive part of the algorithm by using approximate product structure of random restrictions.

## August 7, 2020
Went to sleep later yesterday night, still woke up later than intended.

\[6:47-10:00\]: Wrote down some notes from Tselil's talk yesterday. Tried to draw analogy to hardness of approximation to explain why average case reductions are hard to come by: maybe we need a new characterization of these problems that allows us to come up with new reductions (analog of NP = PCP). This is related to my idea of when do there exist interesting proofs of properties of Gibbs distribution. Then worked on coupling problem and got something decent. Can lower bound correlation, but w.r.t. some coupling. Need to think how to get rid of that weird coupling and also check whether the coupling proof of contraction is "low degree". Got quite distracted past two mornings. Train of thought constantly getting interrupted.

- \[2:15-3:30\]: Tried to get back on track with partition functions project. Tried to read "Harnessing Bethe free energy" paper, but gave up because it was too dense. Instead, was able to parse the introduction of [this paper](https://arxiv.org/pdf/1603.08191.pdf).

## August 6, 2020
Woke up late.


- \[7:15-10:16\]: Watched Pravesh's talk on list decodable linear regression and started writing some notes. I am a bit confused on the counterexample for certifying a list is good. Spent time thinking about whether this can be used to output list of cluster centers for space of solutions of a random CSP. The issue in the latter case is that a list may not have a succinct certificate. But maybe there are some non-trivial (i.e. don't just output) proofs of properties of the Gibbs distribution, along the lines of poly-sized PCPs?

- \[2:30-3:55\]: Attended Tselil's talk. Got some good ideas how bigger research program of building reductions between algorithms, which we don't have much of. Even further, existing reductions are not quantitatively tight or don't apply to broad enough class of problems. Didn't follow all the technical details. Want to look into Vempala works on connecting convex programs with SQ model. Felt quite drained afterwards.


## August 5, 2020

- \[6:33-9:47\]: Wrote down "big ideas" and list of all important (on meta level) papers I want to read. Then started reading essay's on Boaz's blog and writing notes. In particular, I spent some time thinking about structure vs. combinatorics and how statistical physics fits into that theme. I also want to study the role of robustness and posterior mean vs. MLE in explaining this phenomenon.

- \[4:00-5:00\]: Met with Boaz. Updated him on brute force thing. It doesn't give us the correct interpolation, but still non-trivial result. One added benefit is we can remove SoS certifiably hypercontractive assumption; can we do this for other robust statistics problems? FOCS 2020 paper by Morris, Yeshwanth and Sidhanth doesn't face this issue because they only deal with mean estimation. Even if we can't remove this assumption, that would also be very interesting if there is a gap between what can and cannot be done. Then I asked him about structure vs combinatorics. Realized that defining a notion of entropy for pseudodistributions is actually quite important. Will try to talk with Pravesh about it.

## August 4, 2020

Did 1008 Gayatri in the morning. Pre-planned off-day.

- \[1:00-2:33\]: Met with Jeff. Discussed rounding to tree-like distributions first. I thought there was not much hope here, but need to read Dembo-Montanari (or related work) which proves that Bethe approximation is correct. I want to understand whether the proof even makes sense for pseudodistributions. Also, what properties uniquely identify the Gibbs distribution? Can I hard-code those constraints into SoS? Seems like identifiability; same idea showed up when I was thinking about coupling two days ago. Then explained tree-reweighted approximation. Don't really have an idea of whether calculation will work out or not.

## August 3, 2020

Avani Avittam - went to SBAT in the morning.

- \[6:30-7:00\]: Thought about tree-reweighted approximation. Realized that maybe Lipschitz constant is too big, so need to directly analyze inner product of deviation term and gradient term.
- \[1:00-2:40\]: Attended Brownian motion reading group on using BM to do analysis of Boolean functions. I understood the whole talk, but am always curious: how does one come up with such martingales in the first place?


## August 2, 2020

Have been waking up later each day.

- \[7:08-9:12\]: Worked on coupling idea. Wrote down what the proof outline should look like. The key issue is how to define the distance between two (pseudo)distributions so that the proof carries through. I need to revisit the basics of the coupling method to redefine things correctly. One worrying aspect is that everything seems to carry through even for slow mixing chains. I don't have a satisfactory explanation for this yet; maybe it has to do with the precision with which we solve the SDP?
- \[9:12-9:56\]: Revisited tree-reweighting. Basically, I have reduced things to the following question. How well does the log partition function of a random tree concentrate about its expectation, where the random tree is sampled uniformly from the set of all spanning trees of the original graph. This distribution can be related to the spectral properties of the original graph, which seems useful for me to encode how well the graph can be approximated by a tree. Need to carry out this calculation next.
- \[11:00-12:40\]: Met with Fred. Discussed brute-force idea suggested by Boaz. Checked it over and we think it should work. In fact, we probably don't need to go through SoS at all. We want to try to directly extend our mean estimation algorithm, but replace the approximate eigenvector oracle with an approximate injective tensor norm oracle. The key idea is that we are promised a good solution exists. Next step is to try to formalize it and write down the technical details.

## August 1, 2020

- \[6:50-8:41\]: Continued thinking about provable bounds for Bethe approximation idea from yesterday. Came up with a counterexample that shows it can't work for worst case bounded degree graphs. However, we might get something interesting for ferromagnetic Potts model on expanders. Then I realized that even getting something on expanders may not be possible by my approach by extending the counterexample. Next time I want to think about the tree reweighted approximation. I think cluster expansion might be quite interesting. Wrote up these logs.
- \[8:41-9:50\]: Thought about coupling idea from yesterday and convinced myself that something interesting is doable. Next step is to write down the polynomial constraints and run through the full proof, but rephrased in terms of moments instead of probabilities. I think paper by [Bresler-Nagaraj] and Mossel paper on MCMC diagnostics may be relevant. The latter shows a worst case, complexity theoretic hardness. What about a low degree version? In the same way that in SoS world, P = NP, could we get an interesting analogue of their results for sampling from an easy distribution?
\[12:47-1:50\]: Watched [this talk](https://www.youtube.com/watch?v=K2VFS1gADdw), understood all of it. Wrote down part of notes, to finish later.
