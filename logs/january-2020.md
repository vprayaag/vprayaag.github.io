# January 2020

## 1/31/20

I attended a seminar class by Jose Zubizarreta, on the design of experimental and non-experimental studies. I know have some understanding of the difference between stats. theory and stats. methodology. I learned a lot of things:

- When reading a paper (especially for the purpose of presenting to others), a common tendency is to get a high-level overview of what the paper is about. This is actually quite useless; you are just skimming the top-level of the paper, which anyone can do. This type of reading doesn't really advance our knowledge at all. Instead, one should strive to take a *deep dive*. Just focus on a single theorem or section and drill down. Fundamentally understand in a way that you actually advance your knowledge (this is true learning) and present something new to others. Really focus on working on this aspect, this is actually a way to practice creativity.
- Ask yourself why the authors took the approach they did and compare/contrast other approaches.
- We waste a lot of energy just learning the notation.
- Every equation or step of the proof has some meaning.
- He was very slow and methodical. Even from staring at something very simple (a small equation, notation, or definition) he made some interesting, deeper observation.
- We don't need to read every single paper on a given subject; just a few carefully selected, representative papers is sufficient to get a deep understanding (think back to what John Tukey said).

Andrei Kolmogorov, when approaching a new problem, lightened the psychological burden of solving the problem by embedding it in a broader context. He would organize a seminar with the goal of learning all around the problem; at the end of the semester, he was at least guaranteed to have learned relevant tools (even if he couldn't solve the problem).

## 1/29/20

- Go through SoS survey, focus heavily on mixture modelling part
- Revisit identifiability survey
- Create an outline of twilight zone paper

- work on IBC
- work on ICML

## 1/28/20

I had some further thoughts on some comments by Prof. Jun Li on learning. He mentioned that compared to other subjects, the technical background required for Bayesian statistics is not too deep, but the main challenge is understanding the philosophy. He then said that if all a student cares about is getting a good grade, it is sufficient to just read lecture notes and do a few problems, without coming to class. He estimated that such a strategy would require only 1/3 of the time needed to learn in the standard way. However, this time is completely wasted because the student will forget everything one week after the final exam.

I think I make this mistake too often. Most of the things I read fall out of my head within a week, so I am essentially running in place. I either need to commit to learning something thoroughly, or otherwise just skim, without investing much effort. As an example, I spent about 2.5 hours today trying to read [a paper by Pierre Jacob on minimum Wasserstein distance estimation](https://arxiv.org/abs/1701.05146) without making much progress. I have very little to take away beyond my initial skimming. If I come back to this paper after a few weeks of class, I can probably cut much deeper with less effort. Whenever reading something, I either need to commit to just skimming it or thoroughly digesting it; don't hang around in the middle.

Connection to Fognini: don't play games that have already been lost. If you are down 0-40, just give up and move on to the next game. Identify the games that really matter and invest effort in them.  

## 1/10/20 - ## 1/27/20

In India. Obviously didn't record any details.

## Brain dump

- Talk to Subhabrata Sen about El Alaoui-Montanari paper on amenable graphs. For which graphical models is inference computationally easy/hard? Also talk to him about any other problems with random graphs in them (see: Bayesian approach to causal inference and how to put a prior on graphs?). This is similar in spirit to program towards resolving UGC by characterizing which instances are hard.

- See Pierre Jacob paper on Wasserstein distance based estimators; I think there are some clear open problems here, with applications to robustness. Are there applications of optimal transport to the heterogeneity approach to causal inference? Talk to Natesh Pillai about this.

- Talk with Junwei Lu about combinatorial inference.  

- I read a little bit about selective inference. I think this is a very interesting subject; will try to talk with Lucas Janson. I am sure there are some computational problems here.

- I am fascinated by Fabio Fognini's playing style. I wonder if his approach can be extended to other endeavors. Basically, he conserves energy and doesn't waste effort; he only engages fully when it really matters. Do more with less. In many aspects of life, we spend a lot of energy to move a short distance. How far can you get by just investing the minimum amount of energy?

- Jun Liu (Harvard, Statistics) cited an interesting quote of Andrew Gelman that is along the lines of "Theoretical statistics develops theory for applied statistics". The main takeaway is that in order to do good theoretical research, one has to be motivated by practical issues. It is very hard to do meaningful theoretical research without stepping outside of the theory bubble. How do I get my hands on some interesting practical problem?

## 1/7/20 - ## 1/9/20

Forgot to record details. Had some errands on the 7th, so didn't get much done.

Had quite an effective day on the 8th. Came up with a candidate lower bound strategy in IBC project. I did the upper bounds in the HSS15 paper as exercises.

Read the HSS15 paper, sort of made some progress, but now need to analyze candidate lower bound construction.


## 1/6/20

1. Picked up with trying to show gap for degree 4 SoS for tensoring operation. Tried to prove result via a naive comparison inequality, but then showed that this is the wrong process to compare to. Got a bit stuck then; how to compare pseudoexpectations of degree 2 vs degree 4 polynomial? I feel like having an SoS toolkit here would help.

2. Fully caught up on monotonicity project. Going through calculations for non-isotropic case after applying reduction; will finish up calculation tomorrow. I made progress on a question that has been bothering me for a long time: why is nontrivial prediction accuracy even achievable (by some form of least squares) for overparameterized linear regression? This was only recently addressed by [Bartlett et al.](https://arxiv.org/abs/1906.11300). It turns out that the answer depends critically on the structure of the covariance of the covariates. With "benign" structure, prediction is possible, whereas with other structures, one can't do better than trivial accuracy. I hope to read this high-dimensional linear regression literature this semester.

## 1/5/20

Took a break. Also, realized a few things from David Goggins video. The PhD is short; the only purpose is to prove you have potential. The way to do this is to become an expert on one topic. It doesn't matter too much what the topic is. For me, my main project is IBC/shape-constrained inference. My next project will likely be mixture modelling. Along the way, I can make some quick money in the monotonicity project. Second, Goggins says to focus on your weaknesses. For me, I think my weakness is technical problem solving ability. I feel underconfident in my problem solving abilities. What if I could bring them up to par? I know my high-level skills (speaking, writing, communicating, strategizing, choosing research problems and building a research program) are top-notch; I have full confidence in these skills. I think problem solving is the only thing holding me back; if I can fix this, I am as good as anybody in the business. Let me triple-down on my weaknesses and become a better, faster, more efficient technical problem solver this semester. Third, don't focus on winning awards or recognition; focus on growth. Fourth, see his comments on how physical health affects the mind.

## 1/4/20

1. Read next relevant [lecture notes](https://homes.cs.washington.edu/~jrl/teaching/cse599swi16/notes/lecture8.pdf), but got a bit stuck. I didn't find the connection between psd-rank and sums-of-squares to be all that enlightening; I'll just proceed with research next time and try reading the [Fleming-Kothari-Pitassi survey](https://eccc.weizmann.ac.il/report/2019/106/) before returning to James Lee's lecture notes.

2. Continued reading about MLE in [Balakrishnan lecture notes](http://www.stat.cmu.edu/~siva/705/lec19.pdf), but took a detour to learn about Fisher information from [Duchi lecture notes](http://web.stanford.edu/class/stats311/lecture-notes.pdf).

## 1/3/20

1. Read [lecture notes from James Lee's course](https://homes.cs.washington.edu/~jrl/teaching/cse599swi16/notes/lecture5.pdf). Now, I understand the connection between non-negative rank and size of LP lifts (Yannakakis' Factorization Theorem). The proof is just to interpret Farkas' Lemma in this context, but requires a few details to make precise. One thing I notice is that once given the write language/notation, proving a statement which I know to be true becomes much easier.

2. Read about MLE in Wasserman book and [Balakrishnan lecture notes](http://www.stat.cmu.edu/~siva/705/lec18.pdf); I now understand MLE quite a bit better. In particular, I now realize why it isn't always so important to obtain an estimator (different from the MLE, in general) which achieves the minimax optimal rate: MLE has a clean asymptotic theory surrounding it (in particular, this allows *inference*), whereas other estimators may not. From a practical perspective, quantifying uncertainty is more important than optimizing sample complexity. For this reason, it is very natural to just study the computational complexity of the MLE separately from minimax rate-optimal estimation. This prompts another question: in cases where MLE is computationally hard and we instead choose computationally efficient relaxations, do the relaxations have asymptotic theory or admit inference? The [CJ13] paper only treats point estimation: the relaxed estimator can be thought of as the MLE for a misspecified model (enlarging the parameter space). It seems that this adds an additional dimension of complexity: how does the size of the confidence intervals change as we back off to relaxations? Intuitively, it seems to me that the confidence intervals would be larger as well; it would be interesting if this is fundamental, or it is possible to recover the original confidence interval size.

3. Caught up on monotonicity project. I read Tengyu's proof and it makes sense. I understand the next steps we are trying to take and can begin to work on them.

## 1/2/20

1. Watched the first [video](https://www.youtube.com/watch?v=1UpOSCt6zAs) of a four-lecture series on lower bounding the size of SDP relaxations. I got a bit lost towards the end on verifying Yannakakis' Factorization Theorem and the proof-complexity interpretation of semidefinite extension complexity in terms of sums-of-squares. I think I will pause and fix up these misunderstandings by reading [lecture notes from James Lee's course](https://homes.cs.washington.edu/~jrl/teaching/cse599swi16/).

2. Started skimming the chapter on parametric models in Wasserman's book. I think my new approach will be to read his chapter and then use a combination of other resources (such as [Jon Wellner's lecture notes](https://www.stat.washington.edu/jaw/COURSES/580s/581/lectnotes.18.html)) to fill in the technical details.

3. I started reading [Larry Wasserman's blog](); I really like the way he explains things simply (always with motivation). I also agree with his philosophy and opinions and want to learn more. For example, one thing I never really thought about: how to evaluate assumptions? One criterion: can the assumptions actually be verified in practice?

Another very fundamental thing which he touched on was the following: prediction -> inference -> causation. Recently, the ML community has basically solved the prediction problem; I think there isn't much progress left to be made and that this area is going to start getting stale soon. At this point, Google/Facebook/Microsoft/Amazon have taken over - it is at the point where academic research on this subject is not really useful anymore. In the statistics community, a lot of progress has been made on inference in modern settings, but the picture is far from complete. Finally, work is just beginning on causality, with much to be explored. Both inference and causality need to be solved before impacts can be made in higher-stakes application areas. I believe this is the future; I am willing to bet my career on it! I plan to shift over to statistics - I finally found something about which I have a strong personal conviction.


Finally, he mentions quite often the importance of the computational perspective in statistics and laments how computer scientists don't want to come to the statistics side of things. I think this opinion is shared more broadly in the statistics community and I want to contribute towards bridging this gap. A very characteristic trait of CS researchers is to study a problems that "belongs" in another domain by ignoring past work, reinventing the wheel, and then realizing many years later that much the problem had already been studied. When it comes to statistics, however, I don't think this will work; ultimately, the world is moving towards decision making uncertainty - this is precisely the problem statistics can solve and I do not think it can be supplanted as CS has done to other disciplines. The only real contribution CS can bring to the table is the computational tools; unfortunately, I see very few computer scientists who share this perspective, despite warnings from the statistics community.  This coming semester, I want to interact with more statisticians and eventually be able to call myself a statistician too.

## 1/1/20

Took a break today.
