# December 2019

## 12/31/19

1. Skimmed through the [Gyorfi book](https://www.springer.com/gp/book/9780387954417) and decided not to continue with it at this time. I think it goes into too much detail for me and is a bit outdated. I am also suspicious of nonparametrics (at least, "classical" topics like density estimation): is it just a collection of toy models and technical tools? When would one ever use these things in practice? It seems very hard to interpret nonparametric estimators, which seems to be one of the main purposes of any statistical model. I am sure there are nice applications, but I am not convinced yet. Then, I started skimming through Tsybakov's book: I think this book is better for me because it is more concise and doesn't beat around the bush.

2. However, I think that for now, I should instead work through Wasserman's books. Even though these books are lighter on the technical details, I can learn all the key ideas and get the big picture more quickly. From Wasserman's books, I should be able to jump directly to papers and pick up the details as needed.

3. Partially caught up on monotonicity project. Just need to read and digest Tengyu's proofs - then can understand next steps.

## 12/30/19

1. Watched a bit of a [video](https://www.youtube.com/watch?v=v8_NtULXV-g) of a talk on lower bounding size of SDP relaxations. Got lost at Yannakakis' Factorization Theorem and SoS, as well as how this extends the LP case I saw yesterday. However, I would like to learn more about this literature because I think it is very fascinating and might have some interesting implications for statistical inference. I also hope to learn about connections to quantum information theory; I believe Boaz may be interested in this as well.

### Things to improve on

1. Got a bad stomachache last night, so couldn't fall asleep until 2AM. Lesson learned: *moderation in everything*.

2. Watched a very interesting [segment on 60 minutes]() about the effect of psilocybin on the mind. In particular, there were two main effects that had huge impacts. First, it reduces activity in the part of the brain associated with the ego (the internal voice that keeps talking). This is something I really want to work on through meditation: silence the inner turmoil and just exist in the present. Second, partially as a result of the first effect, it massively increases connections between parts of the brain that don't interact with each other so heavily; this leads to very unique, creative, and powerful thoughts.

3. *How does a tree grow? We never see it grow each day, yet it happens over long periods of time. When a tree grows, it doesn't think "in which direction should I grow?" or "how to optimally allocate my nutrients for today?" - the branches just grow towards the sun and the roots grow where there is water and nutrients. How does water erode rock? We never see any change on a particular day, yet it happens over long periods of time. The water doesn't strategize, it just surrounds the rock and takes the shape of whatever is around it, constantly flowing back and forth.* I think these are the most fundamental lessons you can apply to your studies and life in general: *STOP OVERTHINKING*. Each day, you only have one responsibility: make one small step after another. Let the inner voices fade away. Directing too much thought at anything is very powerful: it creates attachment. If you think about the fruit at the end, then you are guaranteed to lose - the human mind simply cannot handle these types of thoughts over an extended period of time - it only leads to self destruction. From now on, these logs should be purely technical and descriptive, with only occasional reflections (kept to be succinct).

4. Looking at the time or thinking about it is a distraction and form of slavery.

## 12/29/19

1. Tried to lower bound computational width for tensoring operation. Couldn't quite figure things out, but have a slightly clearer understanding of the problem. It seems to be connected to the broader literature of proving lower bounds for hierarchies - this is a difficult, but important task.

2. Watched [video](https://www.youtube.com/watch?v=wWHoEjn2iIs) of talk on lower bounding size of LP relaxations - I thought James Lee explained things very well. I also believe this work is conceptually aligned with ours; the techniques seem to be relevant. I want to study this (and related literature) carefully.

3. Continued to work through [paper](https://arxiv.org/pdf/1901.05078.pdf) by Nhat Ho and others, but got a bit stuck because the paper is quite dense. Next step is to just pick off the things I don't know one-by-one.

### Things to improve on

Overall, I thought today was quite effective. I didn't accomplish a huge amount, but spent quality time thinking about the problem and learned something concrete. If I can repeat this 100 times, I think I will have made significant progress.


## 12/28/19

1. Skimmed over a [survey by McLachlan et al.](https://www.gwern.net/docs/statistics/2019-mclachlan.pdf) on finite mixture models and wrote down the concepts I don't know. Then, skimmed over [two](https://arxiv.org/pdf/1709.08094.pdf) [papers](https://arxiv.org/pdf/1901.05078.pdf) by Nhat Ho and wrote down the concepts I don't know, as well as some open problems. There are two types of open problems. The first pertains to doing parameter estimation under weaker assumptions or less knowledge of hyperparameters. I think a good exercise would be to go through the process of how parameter estimation for mixture models is done in practice to learn what types of assumptions are valid/invalid. The second is related more broadly to understanding what methods are robust to model misspecification; this question can even be asked in the Bayesian setting and has connections to [recent work by Dunson and Miller](https://arxiv.org/abs/1506.06101).   

2. Skimmed [Hopkins-Shi-Steurer paper](https://www.dsteurer.org/paper/tensorpca.pdf) on tensor PCA. The upper bounds are quite simple and would be a good exercise to return to next time I get stuck. The lower bounds are much more complicated and face the same issue in other papers: how to explicitly construct a valid pseudodistribution? Maybe GP tools can simplify this?

## 12/27/19

1. Continued through most of third lecture from yesterday, but got lost, so I stopped. I didn't understand the motivation behind de Finetti's Theorem (why is it useful?), how the Chinese Restaurant Process is related to DPM, and why completely random measures are useful. I think the fourth lecture may have more applications. It seems like BNP is an area where one needs to understand the motivation beforehand - current papers are very hard to access directly. I will eventually pick up the tools needed in class in the spring semester, so I will not try to rush into this.

2. Instead, I revisited papers of Nhat Ho and Long Nguyen on mixture models and realized that they are quite accessible. It will be good to have a very concrete problem to work on - I believe I can understand this literature and learn a lot. Moreover, there seem to be several connections that I can look into in the future. First, the notion of *identifiability* plays a central role - see ICM survey by RSS on computational analogue - I think more exploration is needed here. Second, there are many types of mixture models: mixtures of linear regressions, mixtures of experts, and robust/corruption models (e.g. Huber contamination model). Third, the notion of identifiability seems to be much more broad - it even shows up in causality - this may be a nice opportunity to learn about causality as well.

## Things to improve on

1. Break big tasks into small pieces.

## 12/26/19

1. I keep getting overwhelmed by having too big of a list of things to do - paradox of choice. In an effort to combat this, I have simplified the deliverables below. Maybe this is related to Aaditya Ramdas's advice on being able to break something big into smaller chunks.

2. I realized that for now, it would be best to learn about BNP now and work on it with Natesh. Then, I can slowly learn more about causality and selective inference and work on those things in the future. There are a lot of interesting people in the Biostatistics Department - hopefully I can interact with them in the future. For next summer, I might be able to try for a summer internship with them or at MSR (Lester Mackey).

3. Completed 1.5 of [lectures by Tamara Broderick and Michael Jordan](http://people.csail.mit.edu/tbroderick//tutorial_2017_simons.html). So far, I learned about basic motivation for BNP: clustering - what to do when number of underlying components may grow as we see more data? Solution is to introduce the Dirichlet Process (via stickbreaking representation of Dirichlet) and associated mixture model. This model induces a random measure (fencepost picture), which can also be interpreted as a stochastic process. Then, I learned about the Chinese Restaurant Process (a preferential attachment model) and how it is a generalization of the Polya urn. Looking forward to learning about actual challenges; so far, I just learned basic definitions and motivations.  

### Deliverables for Natesh Pillai

- Explain SoS via perspective of [Fleming, Kothari, Pitassi survey](https://eccc.weizmann.ac.il/report/2019/106/).
  - Identify a small list of example applications.
  - Construct expositions for those examples.
- Identify something we can work on together. Here are the topics which interest me:
  - Bayesian nonparametrics.
  - Causality
  - Selective inference


## 12/25/19

1. Mostly resolved statistical width issues - should be fairly straightforward to figure it out. Got stuck on analyzing computational widths under tensoring operation. What does the degree-4 SoS relaxation of the order-4 tensor nuclear norm ball even look like? It is hard to analyze the width of a convex relaxation without knowing an explicit geometric description.


### Things to improve on

1. Got completely overwhelmed and paralyzed by too many choices after getting stuck on degree-4 SoS.

## 12/24/19

1. Wrote down the outlines below.
2. Extracted relevant ideas from Vershynin Chapters 7-8 and Wainwright Chapters 4-5 on how to calculate Gaussian widths. First, one should think of Gaussian processes in terms of the canonical metric they induce (which roughly corresponds with variance). The main tool is that the max of $N$ standard Gaussians is roughly $\sqrt{\log N}$. One can then extend this to control suprema of more complicated Gaussian processes via a union bound over a net + approximation argument. Sudakov's Minoration inequality gives a lower bound on the sup in terms of metric entropy. Dudley's Inequality and chaining are multiscale versions of this. Generic chaining chooses the chain adaptively; it is a harder tool to use, but always gives correct answer. I don't know of an example where generic chaining (or even Dudley's inequality) is actually necessary. Another technique is to use comparison inequalities (Slepian, Sudakov): compare complicated GP to a simpler one whose sup can be calculate explicitly. Interestingly, these can be used to prove both upper and lower bounds; I expect this will be the most useful tool for my application.
3. Started to revisit what is known about tensor PCA, but didn't get far.
4. Started skimming first chapter of Gyorfi book; seems like the first two chapters should be an easy read. Obviously, nonparametrics provide a natural perspective (less assumptions) on prediction and regression; why else should I care about nonparametrics?

### Things to improve upon

1. I don't actually have a concrete problem digested yet. I think I would feel better if I have an explicit technical problem fully loaded into my mind. For tomorrow, let me try to solve the tensor operation case. There are two potential outcomes. First, it is easy to recover existing tensor PCA results; this would be an interesting way to massively simplify previous work. Second, I run into some unanticipated difficulties; in this scenario, I would have discovered an actually difficult problem to solve.

### Deliverables for IBC

- Complete catalogue.
- Understand exact characterization of MSE from [Chatterjee](https://arxiv.org/abs/1402.0830).
- Understand localized complexity from [Wei, Fang and Wainwright](https://arxiv.org/abs/1803.07763). In particular, are there examples where we might expect richer complexity landscapes?
  - See also [Wei, Wainwright, Guntuboyina](https://arxiv.org/abs/1703.06810)
- Understand what "adaptivity" means in these contexts. See, for example, [Cai, Guntuboyina, Wei](https://arxiv.org/abs/1508.03744).
- Learn more about shape constrained inference (esp. high dimensional and computational aspects) in general:
  - See [Ilias paper](https://arxiv.org/abs/1907.08306) on poly. time algorithm for log-concave MLE.
  - Is there such a thing as MLE theory? How to know when MLE is optimal, what optimal even means, and when MLE is not the "right" estimator to use? Maybe it is called "parametric theory"?
- Understand the nonparametric side of things:
  - Why do people care about nonparametrics so much?
  - Starting point: Gyorfi book (first two chapter).
  - Next stop: revisit first few chapters of Johnstone book.

### Deliverables for Natesh Pillai

- Explain SoS via perspective of [Fleming, Kothari, Pitassi survey](https://eccc.weizmann.ac.il/report/2019/106/).
  - In particular, explain application of SoS to mixture models.
  - Also, discuss perspective on identifiability from [Raghavendra, Schramm, Steurer survey](https://arxiv.org/abs/1807.11419).
  - Briefly explain how UGC fits into this context. See [Weyl Lectures by Irit Dinur](https://www.ias.edu/events/hermann-weyl-lectures-23).
- Read [Nhat Ho's papers on mixture models](https://people.eecs.berkeley.edu/~minhnhat/publications_topics.html).
  - Learn about MLE in this context, its non-convexity, and what is the "optimal" estimator here.
  - Learn more about "parametric theory" here.
  - Learn about identifiability from the statistics perspective.
  - Place Bayesian nonparametrics in this context.
  - Identify some concrete questions.
- Continue to develop Bayesian perspective by working through "The Bayesian Choice".
- Try to get a sense of recent work on variational inference.
 - How does this relate to [recent work](https://math.mit.edu/~risteski/) on using hierarchies to calculate partition functions?
 - Recent work that seems to suggest non-log-concave sampling may be easier than non-convex optimization in some cases?


## 12/23/19

- \[0:25\]: Thought about linear regression and stupid mistake I made. This is why mastering the fundamentals is so important - it can save hours of time.
- \[1:30\]: After dithering around for a few hours, resorted to administrative work due to burn out.
- \[1:00\]: Had an epiphany, see below.

Have been waking up at 7:30am and sleeping at 10:30pm.

### An epiphany

Read [essay](http://paulgraham.com/lesson.html) by Paul Graham: I realized that I reached the point I am at today primarily by "hacking" tests and admissions. The vast majority of my studies are undertaken with a specific goal in mind; if I do X, then I get Y which will help with my long term to achieve Z. I have fallen into this same trap even in my research efforts; I am doing research to publish many important papers to win recognition of those around me, *not* to learn.

I have been spending a lot of time and effort thinking about the "research process" (how many hours per day, where to work, how to organize notes, how to allocate time, and other such "strategies"). I mistakenly thought that these things are the cause and high quality research is the effect. However, this is wrong: high quality research is the cause, the other things are just consequences. So, no matter how well I optimize my schedule, it can never have a significant impact on the quality of my research.

In this context, Paul Graham would say that the recipe to having a successful PhD is very, very simple: do high quality research. Any brain power I have to spare should be spent attacking the research problem. Stop wasting time on strategizing or other "meta"-type things. Each day, the focus should be only on learning *something*. (However, I do *not* want to focus on "maximizing" the amount I learn or "optimizing" in any way.)

Whenever I am not actively working on research, it is of the utmost importance that I calm my mind and stop thinking about research. This has two effects: I am more peaceful AND the subconscious parts of my brain can start to work on the research while my conscious brain rests. In fact, the subconscious parts are where all the good ideas come from.

Another realization I had is that for creative endeavors like research, one can never succeed with a "top-down" approach. It just never works if one tries to follow a rigid set of rules or design an "algorithm" for outputting research. The process is very qualitative and can't be made quantitative; one has to go off instinct alone.

For these reasons, I am going to stop recording times from now. Instead, I will just write down the things I learned and the challenges I faced. If I want to make sure I am on track, I should just choose a random day and record the time for that day (sort of like random drug tests in sports; the whole point is that you can't prepare ahead of time).

In terms of the notes I take when reading, I need to remind myself that the notes are not important on their own; their only purpose is to help me learn. This might involve being less verbose and more succinct, recording only the bare minimum I need to rederive things from first principles.

I also realized that most problems are not that hard to solve, once I understand them thoroughly. So, the hard part is actually getting to that state of understanding. This should direct my approach each day: aim to clear away uncertainty/fogginess and make the problem and its surroundings more clear.

In terms of my capabilities and imposter-syndrome stuff: I am confident I can come up with high-quality ideas. In fact, I think one of my strengths is drawing analogies between disparate ideas. I just need to set myself up to be able to use my strength.

I have always spent so much time strategizing and wondering why others don't do the same. It is probably because I have overcomplicated things.

In summary, my only goal is to *understand*; nothing else.

After this, no more epiphanies.

## 12/22/19

- \[0:15\]: Wrote down logs for past few days.
- \[2:00\]: Watched [video](https://www.youtube.com/watch?v=zvrcyqcN9Wo) of tutorial on causal inference; interesting subject, hope to return in future.
- \[0:30\]: Watched [video](http://www.birs.ca/events/2018/5-day-workshops/18w5112) of panel on shape-constrained inference. Lots of golden opportunities here: computational complexity, high-dimensionality, and complexity of problem at different points/instances. Ironically, they are looking to recruit CS people to work on these problems - definitely need to take advantage of this. Need to understand nonparametric aspects and why it is a trending topic, then talk to Nilanjana Laha and Rajarshi Mukherjee. If we get some basic results on IBC project, then should definitely reach out to Bodhisattva Sen.

Wasn't too focused today, spent a lot of time reading interviews and such. Found a nice [checklist](https://www.stat.cmu.edu/~aramdas/checklists/aadi-balance-checklist.pdf) by Aaditya Ramdas, definitely need to reflect on this every once in a while.

Why does [Leo Breiman think all these theoretical topics are useless](https://www.taylorfrancis.com/books/e/9780429492525/chapters/10.1201/9780429492525-2)?     

## 12/21/19

- \[2:20\]: Started reading Chapter 1 of "The Bayesian Choice"; I like this book because it includes philosophy.
- \[1:32\]: Learned about selective inference. Started watching [video](https://www.youtube.com/watch?v=89NsJv5x8RI) of lecture by J. Taylor, but didn't think the talk was delivered well. Then, started watching [video](https://www.youtube.com/watch?v=qofrkW-DL7c) from Simons Institute for a few minutes, which was much better. Started reading the [PoSI paper](https://arxiv.org/abs/1306.1059); I think there is an interesting computational problem in here, but need to understand more clearly.

A thought about selective inference in practice: it seems like people typically prefer not to change their existing behavior; can valid selective inference be automated into their existing workflow?

Remember: strategy is different when at home and when on campus. When at home, need to get an early start since working day is more compressed. Additionally, need to really make use of the breaks.

Also, from now on, will take off weekends to just learn about interesting topics that broaden perspective.


## 12/20/19

Essentially the same as yesterday.

## 12/19/19

Didn't record time, but spent about 1-2 hours. Thought about long term plan and skills I want to learn. Read a [commencement address](http://statistics.berkeley.edu/memory/leo-breiman/commencement-speech) by Leo Breiman. An interesting question: what types of people decide to become statisticians? No child ever grows up wanting to be a statistician; which is contrast with other professions. The people who study statistics often come from diverse backgrounds and only chose to study it relatively late in life. I really think statistics (and its associated way of thinking) is the most important subject in the modern age,

## 12/18/19

- \[2:00\]: Watched some clips from interviews on MSR YouTube channel. I had two main takeaways. First, multiple interviewees gave the advice that you should not worry too much about disciplinary boundaries; just pick an important problem and go wherever it takes you. Second, David Blei discussed how he got started working on LDA - it was inspired by an applied, practical problem he encountered while at an internship. Also, thought about climate change - see below.
- \[1:00\]: Chatted with Preetum on Slack.
- \[0:16\]: Brain dump below.

Further reflections: I was thinking more about the distinction between "practical" and "theoretical". Up to this point, I have been purely theoretical and have avoided developing practical skills at all costs. My skills are very narrow and even from talking to others, it is very difficult to explain and justify my work. One common justification for theoretical work is that it is hard to predict, but often has unforeseen practical consequences (example: Einstein -> relativity -> GPS). If you are a theorist, then I think you need to commit and be devoted completely to dreaming up magical ideas. I am pretty sure I don't fall in this camp - who cares if we can't prove P != NP?

On the other hand, being a practitioner with not enough technical ability to understand the basic theory is no good either. As with all things, one needs to find the right balance.

Since almost all of academic research is useless, I then thought to myself: what is the most important problem faced by society in which science might play a role? My answer is addressing climate change. Society is at a point that we don't have any time to waste on solving this problem. It might have been justifiable to be a theorist 100 years ago, but no longer in the current context.

Clearly, it is impractical to drop what I am doing and study atmospheric science, or chemistry, or materials science. Instead, I have to find something in my vicinity that can still have some impact.

Moving forward, I want to develop a strong set of statistical modelling skills (both theory AND practice). This can be of service to climate science (and beyond). In the past, "inference" was a problem contained within the domain of statistics; in modern times, it is really just another computational problem, as computation is always relevant.

In particular, I want to think more about following topics: Bayesian inference and modelling, probabilistic programming, data science, variational inference, blackbox inference.

In the spring, I plan to talk to more people (Natesh, people at MIT, Youssef Marzouk, Jonathan Huggins, Jeff Miller, and people in other departments in Harvard (such as the climate people in the neihboring building!)). As per the advice above, I shouldn't worry that whether this new direction is relevant to my past work. Also, having a practical challenge in mind might inspire some interesting theoretical problems.


## 12/18/19

- \[0:15\]: Studied for probability exam.
- \[3:05\]: Completed probability exam.
- \[1:05\]: Talked with Preetum again. Have some concrete calculations to do; hopefully we can move quick and learn a lot.

Flew back to Baltimore for winter break.

## 12/17/19

- \[0:10\]: Looked more into double descent.
- \[0:15\]: Studied for probability exam.
- \[1:50\]: Studied for probability exam.
- \[1:32\]: Studied for probability exam.
- \[2:25\]: Studied for probability exam.

## 12/16/19

- \[0:15\]: Briefly thought about high-dimensional linear regression.
- \[1:20\]: Read lecture 3 in Percy Liang's [lecture notes](https://github.com/percyliang/cs229t/blob/master/lectures/notes.pdf); had some good insights.
- \[2:15\]: Continued studying fixed design linear regression.
- \[2:30\]: Met with Preetum and Tengyu and then talked more with Preetum. Had some simple ideas and concrete calculations to do.

For some reason, my brain stops working when meeting with others. I also realized that I don't _truly understand_ any of the basic tools that are relevant. I feel that even with just a solid foundation, one can make huge strides in research, without having to be a genius. As Richard Hamming said, my understanding of them is completely confined to the limited context in which I learned them. Somehow, I need to find a systematic way of deepening my understanding. Currently, my approach is to just find some lecture notes, read them, and then hand-write notes. I need to do something extra to burn it into my memory and make it feel like second nature. When thinking and talking on the fly, this is the only type of knowledge that one can rely on.

I need to make a habit of writing down what I am thinking to clarify my own thoughts (translate thoughts to symbols).

During the meeting, I noticed how Tengyu's understanding of the basic foundations is deep and nuanced. He really seemed to understand the guiding principles and how they were relevant to our context. This allowed him to reason in a principled manner about answers to the many small, intermediate questions that popped up.

## 12/15/19

- \[1:35\]: Continued with linear regression but wasn't all that effective. Was rushed and overwhelmed by too many resources. My approach was to try to start from fundamentals and then work up to more advanced things. I think a better approach is just start from the highest quality reference (even if doesn't cover the full picture) and build knowledge from there.
- \[0:15\]: Teaching responsibilities.
- \[2:00\]: Met with Preetum to discuss high-dimensional linear regression. Identified some tractable questions; should definitely be possible to make quick progress and learn a lot.
- \[1:00\]: Teaching responsibilities. Finished last one of the semester.

## 12/14/19

- \[0:45\]: Administrative work.
- \[2:08\]: Studied linear regression from various lecture notes (mainly from CMU). Plan to stick on this for the next two days.
- \[1:50\]: Talked with collaborator on Hangouts. As Richard Hamming suggested, will try to learn and explain to sharpen my ideas.
- \[0:20\]: Continued with linear regression.

## 12/13/19

- \[1:00\]: Started reading about Gaussian width in relevant papers and Vershynin book.
- \[1:55\]: Continued through with Chapter 7 of Vershynin book. Learned about how to think of Gaussian processes (in terms of covariance function, increments, and geometry induced by this metric) and comparison technique; went through a few examples and was able to prove simple result for tensoring operation.
- \[1:05\]: Continued skimming through rest of Chapter 7. Also skimmed chapter in Wainwright book. Shouldn't be too hard to develop a good working knowledge of this material; keep lots of examples in mind. I think these types of problems can be solved by reusing the same tools. I think main challenge will be in calculating local Gaussian widths (which is of independent interest) and calculating Gaussian width for the sets we are interested in. This would involve developing a better understanding of these sets.

Got off to a slow start and showed up quite late. Went quite slow, but stayed focused on the same thing. Can at least say I made some small progress and laid down some meaningful groundwork. I think I was most productive in the afternoon session (as in previous few days as well).

## 12/12/19

- \[1:14\]: Teaching responsibilities.
- \[1:05\]: Prepared for meeting on instance-based complexity. Don't have much to show. Need to think carefully about how to handle these scenarios.
- \[0:30\]: Continued preparing for meeting.
- \[1:20\]: Grading final exam.
- \[1:20\]: Meeting to discuss instance-based complexity. Wasn't so productive, but now that I have time to work on it, can be more prepared for next time. However, no more mistakes and no more chances.
- \[1:15\]: Grading final exam.
- \[0:15\]: Wrote up some notes from meeting.

## 12/11/19

- \[1:28\]: Started typing up handwritten notes on instance-based complexity.
- \[2:30\]: Watched [video](https://www.youtube.com/watch?v=GDyq86FQ7sI) of lecture on average case complexity. Was not as relevant as expected, but will digest it over time. Took notes.
- \[0:30\]: Started reading section by Paul Beame about proof complexity in a book about complexity theory.

Took longer break after afternoon run. Tried to implement Richard Hamming's advice on saturation, but just reverted back to old routing. Spread my time too thinly, so ended up not understanding things at deeper level than before. Was on track in morning session, but got distracted in afternoon by average-case complexity talk. Next thing I need to practice doing: just pick one main thing each day and spend almost all of time on it (it is OK to divert a small amount of time to other matters). Will try to repeat a few days and see what happens.

## 12/10/19

- \[1:53\]: Worked on final homework.
- \[3:34\]: Finished on final homework.

As usual, homework should be super easy but took way more time than it should have. Need to improve speed when it comes to problem solving. Just need more focused practice.

## 12/9/19

- \[1:35\]: Worked on writing up STOC review.
- \[0:48\]: Continued with STOC review.
- \[1:00\]: Teaching responsibilities.
- \[0:08\]: Administrative work.
- \[0:35\]: Teaching responsibilities.
- \[0:10\]: Finished up STOC review.
- \[1:06\]: Discussed homework with class mates. Figured out basically all that I will submit tomorrow.
- \[0:15\]: Discussed next semester's courses with officemates.
- \[0:03\]: Started on writing up homework. Typing is probably much faster than handwriting.

Interesting observation: showed up late and left early and did exercise and took breaks, but still put in more hours than before. Looks like bringing a packed lunch is a big timesaver.

## 12/8/19

- \[0:53\]: Watched another [video](https://www.youtube.com/watch?v=FlTybZvds0U) of talk by Hamming. Wrote some notes and had some good reflections.
- \[1:15\]: Watched another [video](https://www.youtube.com/watch?v=KWNBzAgAiMc) of talk aby Hamming. Took more notes.
- \[0:40\]: Started setting up infrastructure for organizing knowledge.

## 12/7/19

- \[1:33\]: Watched [video](https://www.youtube.com/watch?v=eIEWMuxt2c8) of lecture by Irit Dinur on PCP Theorem.
- \[0:15\]: Tried to watch part of video of lecture, but got completely burnt out. Physical energy was good, mental energy was absent.
- \[0:20\]: Continued reading advice of Richard Hamming, here are some takeaways. It is impossible to learn everything; if you spend too much time reading, then you will be conditioned to think the way others did, which stifles creativity. Read just enough to develop a good enough understanding of the problem that you can think about it on your own. In other words, accumulate a critical mass of information, but no more. Find the shortest path to this state of understanding the essence. Then, just let it cook over time. Good books and surveys are essential for getting to the frontier quickly. Pick up tools when you need them and be aware of what you don't know. One of the things I want to do is be more widely read. By this, I mean that I want to know what are the fundamental problems in several areas and why existing approaches can't solve them. This will make it much easier to talk to people and learn from them. Also, I spend a lot of time thinking about potential connections between different areas, but I really have no idea if there is any real substance. Solidifying my knowledge can help me think in ways that actually have a non-zero chance of materializing.. Currently, I know so little that it is hard to learn effectively from others. But, if I do a bit of background preparation, the rest is downhill - learning from people (under the above conditions) is really the best way to learn.


Brought packed lunch, then cooked fresh in evening.

## 12/6/19

- \[1:33\]: Finished half of probability homework. Not planning to do the other half.
- \[0:10\]: Started to think about instance based complexity again, but wasn't focused so left early for lunch.
- \[0:20\]: Over time teaching responsibilities. Got tired and distracted by holiday part, ended up not doing much.
- \[1:30\]: Talked with Chi-Ning about research and learning; got some good advice. Learning can be classified into two types. In the first, the goal is to learn tools and tricks to solve the current research problem at hand. The goal is not to develop a fundamentally deep understanding, but just to learn enough to solve the problem. Over time, these types of tools will accumulate and help smoothen out the progress. This kind of learning can be achieved in a relatively short amount of time by just studying the relevant resources carefully. The second type of learning is for the purpose of broadening one's perspective and changing one's style of thinking in a fundamental way. An example is learning the correct "language" to express certain ideas in a succinct way. This type of learning is much slower and is a long-run investment.

Have been waking up late because going to sleep late (~10:30). Major lesson for the future: _never_ commit so much time unless the investment is worth the reward. So, don't take classes that give homework assignments - writing it up and submitting are huge wastes of time (especially for slow people). For me, material is best learnt in a pressure-free, nonobligatory setting. More generally, before investing time, _always_ question whether the investment is truly worth it.

## 12/5/19

- \[0:58\]: Started reading CRPW12 paper to understand how to calculate Gaussian widths of convex cones.
- \[0:35\]: Continued with CRPW12; understood duality idea for the most part, but would like to review duality some time. Next step is to understand a few examples of characterizing normal cones.
- \[0:15\]: Continued with SoS matrix concentration lemma in STOC review.
- \[1:10\]: Attended CS colloquium talk by Rediet Abebe. Again, emphasizes importance of Hamming's message: most important thing is to pick the right problem. Simple solutions to important problems (as in her talk) are better than complicated solutions to unimportant questions.
- \[1:30\]: Worked on probability homework; couldn't focus too well.

Ate lunch at buffet; messed up feeling and caused major disruption to work (although it save lots of time in the short run). Felt extremely tired during and after colloquium. In future, there is no need to attend any event that is being video recorded. Can always pick up the main ideas much faster and with much less exertion by just skimming. Only purpose of going to talks in person is to talk in-person with speaker or the information in the talk is not available anywhere else (or would take a much longer time to learn independently).

## 12/4/19

- \[0:52\]: Resumed instance based complexity project. Wrote down summary of last meeting. Read through Chandrasekaran-Jordan paper more carefully.
- \[0:04\]: Watched part of video of panel discussion in which Michael Jordan talked about inferential thinking. The future is about _decisions with consequences_ (which differs from just prediction and the style of work done by big tech companies). A special case of this: how to make decisions with constraints on computational power?
- \[1:35\]: Continued reading through CJ13 paper; have a clearer understanding. The paper is actually not so complicated. Main challenge will be to track changes in Gaussian complexity under operations.
- \[0:07\]: Continued with STOC review. Main ideas are fairly clear, just need to verify (potentially tricky) technical calculations.
- \[1:05\]: Went to [talk](https://stat.mit.edu/calendar/flexible-perturbation-models-for-robustness-to-misspecification/) at MIT by Jeffrey Miller (HSPH). Definitely revisit papers; different perspective on robustness that might be closer to Natesh Pillai's interests. While some of the results were not so convincing, there are a lot of important unaddressed questions in this area (robust Bayesian inference). Moreover, there are many strong arguments why these are really important challenges to solve, especially in modern context. See also the final chapter of Huber's book.
- \[0:30\]: Started on final probability homework.


Went to sleep late and woke up late. Didn't sleep well either.

## 12/3/19

- \[0:30\]: Read paper about connections between differential privacy and robust statistics. Definitely hope to look into Huber's book to understand influence functions and see how they relate to recent developments. Wasn't too focused, but stress low and energy level reasonable. Feel well rested.
- \[0:15\]: Administrative work and planning.
Got tired in class. Felt better after lunch.
- \[0:45\]: Teaching responsibilities. Felt very fatigued (physically and mentally) due to sitting down. Basically didn't get anything done afterwards.
- \[0:50\]: Watched [video](https://www.youtube.com/watch?v=a1zDuOPkMSw) of talk by Hamming. As soon as semester finishes, need to implement his suggestions on robust statistics project.
- \[0:06\]: Thought briefly about instance based complexity. Need to look into Parrilo book.
- \[0:51\]: Resumed STOC paper reviewing. Quite hilarious that we could have gotten the exact same results (or even stronger) with a bit more focus and discipline. We let a bunch of small mistakes, details, lack of confidence and thorough knowledge of SoS basics get in the way of our intuitions (which pointed in the right direction).

Took a full 9 hour block for sleep. Didn't rush in the morning, yet still arrived at the same time. Question - how/when to handle email/slack/arXiv/etc. so that it doesn't disrupt flow?

## 12/2/19

- \[1:00\]: Administrative work.
- \[1:00\]: Continued reading about sparse linear models in Wainwright book, while on plane. Seems like the constrained/restricted eigenvalue problem is at the center of several other problems (linear regression, SSE, denoising).
- \[0:10\]: Planning.
- \[0:45\]: Talked with someone about research process.

Flew back to Boston. Last day of probability class (couldn't make it to lecture).

## 12/1/19

Took a break. Had slight epiphany: why even do a PhD? Answer - it is just an experiment on whether anyone with the right discipline can elevate their ability to formulate and solve challenging questions. Can improving physical and mental health turbocharge research output? If so, then the former can be achieved by discipline alone (eating, sleeping, physical an spiritual exercise). From now on, the goal of this log is to document this experiment. In particular, document energy levels and physical status throughout day.
