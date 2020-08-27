# March 2020

## March 23, 2020

Today, I started working through the interesting problems from Chapters 2-6 of the Boyd and Vandenberghe book. I think if I can do all of the hard problems, that will give me a very strong foundation. Finally, I feel ready to slow down and just learn it properly. After that, I want to read the SoS book, Pablo Parrilo's lecture notes and Venkat Chandrasekaran's SAGE paper.

## March 21, 2020

- I ended up not reading all that much of the O'Donnell-Zhou paper. I spent most of my time learning about basics of hardness of approximation; I found that to be more interesting. However, I think this is alright; I will just set a nominal goal to give me some direction and reduce the effect of paradox of choice.
- Boaz suggested I just make IBC the subject of my qual exam. I am quite happy with this. At the very least, I can just give a talk similar to [one by Alex Wein on LDLR](https://www.youtube.com/watch?v=6iP2hs4zhNU).
- I realized what fundamental theme keeps showing up: *local vs. global*. This is common to PCPs, HoA, quantum information, statistical inference, statistical physics, SoS, MCMC, convex optimization and beyond. This can be a guiding force; I am interested in anything that promotes this idea or even (seeming) counterexamples. This idea, even though it is "abstract" or "useless", has actually been extremely fruitful. Moreover, it has an interesting philosophical interpretation (due to Nassim Taleb). "Locality", in the real-world, is more robust and in general, better. Locality ~ simplicity ~ natural (as in Nature) ~ bottom up (vs top down).
- I have been using the iPad + OneNote + Apple Pencil for a few days; I like it a lot and it gives me psychological reassurance that I am making progress. Just keep pecking away.

I am a broken record:

- Who will have contributed more to humanity: Richard Hamming or Cedric Villani? Obviously, Hamming. Hamming isn't 1/10th the mathematician as Villani and I am sure he doesn't understand the "grand" picture, but in the end it doesn't matter.
- Nassim Taleb would object to the whole premise of the previous point. Nowadays, (privileged) young people like to say "I want to make the world a better place" or "contribute to humanity". However, this is all BS with no skin in the game. The best thing a young person in such a situation can do is to take as much risk as possible, on behalf of the rest of society. See below for my particular situation.
- Clearly, I can never compete with "purists" or "basic scientists" and trying to do so will lead to self-destruction. Instead, the only thing I can do is related  to what Feynman has said. First, I like to learn about a huge diversity of topics. For me, there are no boundaries and my mind jumps around by nature. Today I am fascinated by OT, tomorrow by MCMC, etc... So, let me survey, at a fairly shallow level, as many subjects as I can; just enough to be able to talk to experts, be conversant and recognize opportunities. Once I can be conversant, then the rest is easy; talking to others has the _potential to be_ more productive than even the most productive reading/thinking session by myself. Then, I just make as many connections as possible. To make connections, I need the tools and materials to build bridges. Almost all bridges are built from the same few materials and same few techniques. In my case, the tools and materials are the fundamental subjects like optimization and probability. I want these to be at the tips of my fingers; it is like extending one's vocabulary and grammar in a new language - it will allow me to be more expressive of vague ideas floating in my head. Many times, formulation of the problem in the correct way is all that is needed to solve it. If formulated thoroughly, then I can actually solicit help from others.
  - As an example, particle filters are sampling algorithms for Bayesian inference. What about using them as algorithms for sampling problems that TCS and statistical physics people care about?
- Yuval Filmus says the most efficient way to learn is by doing challenging problems. Continuing the previous point, I should focus more on doing challenging problems on the fundamental subjects. In particular, I don't want to waste more time than necessary on exercises; instead, I want problems which show how to apply the ideas in novel ways. This is exactly the skill I want to train: how to recognize the basic ideas in unexpected contexts. Fortunately, for these fundamental subjects, there are lots of good resources (e.g. Wainwright). On the other hand, when I read some recent research paper, exercises (basic lemmas and concepts) are enough. I don't want to waste too much time digging into the details of the paper because most papers are raw and not well-digested anyways.  When I read a paper, my approach should be to quickly match it to whatever techniques I have learned in the fundamental subjects and then identify what is new. For example, at least half of the papers by Wainwright and his students just build off ideas from his HDS book.
- Some examples: A few weeks ago, I smashed through a few chapters of Wainwright's book on HDS. I wrote ~10 pages of neat notes; that was quite draining and took up ~15 hours. Today, almost all of that material has fallen out of my head. Hilariously, my plan was to type up those notes, which I still haven't done. The more effective *and* efficient way of learning this material would have been to do the problems at the end of the chapters, which are actually quite high-quality. This would give a much deeper and nuanced understanding of the material. The actual chapter is so well-written and pre-digested, it is a waste of time to write down anything more than a high-level outline (which is really just a visual aid/mental crutch). There isn't really anything I can do to explain the material any better than he already has. Compare this with my learning of linear algebra. I don't have any notes from that class (MATH 405), yet I still remember so much and use it every day. The reason is that I did a decent number of good problems, over a whole semester and continued to use the language frequently. In fact, I don't even remember spending massive amounts of time on the class, since I would have had other classes and activities going on at the same time. Another lesson learned is to not be a perfectionist on things that don't matter. Writing an exposition of an already polished textbook chapter is a waste of effort and time and provides no value. But, writing a clean, unified presentation of a messy, not well-understood body of research is more worthwhile.
- Fundamental subjects and relevant resources:
  - Anything by Wainwright (HDS + optimization, soon)
  - Anything by O'Donnell (analysis of Boolean functions)
  - sumofsquares.org
  - Convex Optimization: Boyd and Vandenberghe
  - High-dimensional Probability (Vershynin, Boucheron et al.)
  - Convex geometry (how to think about high dimensions)
  - Complexity theory (Arora-Barak)
  - Markov chains (LPW book)
  - Stochastic processes (martingales, Brownian motion, empirical processes)
  - Spectral graph theory
  - Information theoretic methods in statistics/for purpose of analyzing random processes
  - Control theory/dynamical systems? Some basic usage of differential equations to describe a system? From an optimization perspective?
  - Some aspects of approximation algorithms, like rounding and primal-dual method (Shmoys-Williamson book)
  - "Geometry" (Boumal book should suffice)

Most of the above was with theoretical/mathematical research in my mind; I will have to think about practical/inferential/methodological skills later.

## March 13, 2020

- I changed my goal; I want to read ["Approximability and Proof Complexity" by O'Donnell and Zhou. In particular, they ask about constant degree SoS proofs of the CLT; I believe this may be connected to SoS certifiability of hypercontractivity of distributions (with applications in robust statistics). See also certifiable anti-concentration for list-decodable robust learning (see Pravesh work). I think there are some very interesting ideas here and an opportunity to learn a lot. It seems like this area surrounding KLS conjecture will stall on the mathematical side. The interesting part is to explore the computational implications of these developments in convex geometry.  What kinds of computational problems can we solve related to log-concave distributions (MLE, robust estimation, density estimation).
- Yesterday, I watched a [talk on the KLS conjecture](https://www.youtube.com/watch?v=9zqVIrj9PUk) and realized that this is actually quite an accessible research area. I believe there are indeed connections to SoS. I also realized how even though TCS people write papers on these "math" topics, very few actually have a deep understanding. I noticed how narrow their expertise is and that they make progress without understanding the big picture. Basically, TCS people are good at solving specific technical problems. I noticed this even after watching a talk by Yin Tat on sampling.
- Spend more time reading high-quality papers from high-quality writers (like Ryan O'Donnell). Don't waste time reading poorly written things.
- Nassim Taleb says something along the lines of "Academics are most useful when they try to be useless, but useless, or even dangerous, when they try to be useful." I have been thinking more about what science/technology can do to improve the world. These types of questions are ingrained into our minds growing up, but I am not sure this a correct view. It seems a bit arrogant to have this mindset.  Previously, I was thinking that all good theoretical research stems from practical applications. However, most applied/practically motivated work is actually useless too.
- So, what is the purpose of graduate school? Perhaps it is better after all to just work on purely theoretical questions, while learning practical skills on the side. There are two ways for research to have an impact on the real world. The first is for very theoretical ideas to trickle down; but this only happens on a timescale of decades or longer. Actively trying to force theoretical work to be practical is basically futile. The only useful thing that can be done in a short timespan is to build connections/bridges between areas and solve some technical problems along the way. The second way to have an impact is to find a challenging real-world problem and then try to turn it into a technical research problem. This is almost always useless and fake. Unfortunately, writing a paper is never going to be a satisfactory solution. If you want to have real-world impact, you have to design a solution which is ad-hoc, specialized and tailored to the domain. You can't solve these problems from a distance: skin-in-the-game is necessary. The best way to solve these problems is to just embed yourself in the real world and actually do the work for real. The only value academia can provide is basic tools and principles. In the best case scenario, there is a feedback cycle. In the real world, we figure out what stuff in academia is useless and what is missing. Then, academics can try to think more deeply. As I progress in my studies, I shouldn't obsess about publishing/doing research directly on these topics. Instead, just learn and collect a variety of experiences and tools. Talk to a lot of people. Read a lot of examples and case studies.
- Maybe I should just solve UGC?

## March 11, 2020

My goal for this week is to learn as much as I can from [Ben Recht's survey](https://arxiv.org/abs/1806.09460) on RL from a control perspective.


### Plan

Now that classes are basically cancelled, here are a list of topics I want to learn before next fall. Each week, I hope to pick off a random topic that interests me and read a chapter about it. I want to slowly make progress but also be genuinely curious about what I am reading. My goal is to just get some of the main concepts and understand the big branches of the tree; let me not try to be a perfectionist. I just want to be able to learn the basic language, scratch just below the surface and develop an appreciation for modern challenges. Like Natesh says, let's try to keep a balance between mathematics and applications. To dive into some of these areas, it may be easier to read a few chapters from a thesis, rather than jump into a textbook (which often gives no context). One approach might be to read a paper + surrounding theory per week. At the end of the week, just write up your thoughts.

- Control and RL
  - Basic bandits
  - Contextual bandits
  - Online algorithms, Primal-dual
- Optimization
  - Fundamentals of convex geometry
  - First order methods
  - Continuous time analysis, discretization approach, connection to dynamical systems
  - Mirror descent, proximal methods
  - Duality perspective
  - Interior point methods
  - How to recognize and apply these methods (Madry, Kelner work)
  - Hyperbolic optimization
  - Geodesically convex optimization and differential geometry approach
- Probability
  - Martingales and applications
  - Brownian motion, SDE and applications
  - Markov chains and convergence
  - Convex geometry and connection to HDP
  - Optimal transport and applications
  - Stochastic processes
  - Diffusions
  - Review of measure theory and other fundamentals. (Pollard)
  - Review of CLTs
  - Fourier and functional analysis?
- Statistics
  - Knockoffs, multiple testing, p-values, FDR control, Selective inference
  - Bootstrap
  - Adaptive data analysis
  - Stein's method
  - Model selection
  - Log concave MLE. Log concave robust estimation
  - Bayesian methods
    - Empirical Bayes
    - Sequential Monte Carlo
    - MCMC
      - Convergence rates
      - HMC
      - KLS conjecture
  - Shape constrained estimation
  - Exponential families and graphical models
  - Algebraic statistics
  - More on maximum likelihood theory, Fisher information, LAN
  - Basics of nonparametrics
  - Robustness - Steinhardt notes
- Sum of squares
  - Connection to quantum information
- Hardness of approximation
  - Analysis of Boolean functions
  - CSPs
  - Polymorphisms
- Geometry of polynomials
  - Spectral sparsification
  - Kadison-Singer
- HDX
- Statistical physics
  - OGP, RSB
  - Sampling
  - Permanent vs determinant
- Lattices
  - Connections to convex geometry

## March 7, 2020

After a long hiatus, I wanted to write down some reflections. While writing this, I am a bit burnt out and as a result, seditious.

- The most important thing is to have a strong and healthy mind. This naturally requires a strong and healthy body. Recently, I have been generating immense amounts of internal stress, which is taking a significant toll on my health.
- I like [these thoughts by Andrew Gelman](https://statmodeling.stat.columbia.edu/2012/10/03/advice-thats-so-eminently-sensible-but-so-difficult-to-follow/). What is the point of advice if I can't actually follow it? How do I implement this advice so that it has a lasting effect? I think one answer is to be more mindful and present. This relates back to the above point; a healthy and strong mind can observe itself and recognize, in real-time, whether it is doing things in the right way. It seems to be a common experience to "focus" on work for a few hours, only to realize at the end that the manner of work wasn't right. So, *be mindful*.
- I recently watched Randy Pausch's lecture on "Time Management". Here are some takeaways:
  - Be *absolutely ruthless* in allocating your time.
  - Use Google Calendar to reduce mental burden.
  - Do anything possible to reduce stress related to time.
  - Don't do anything that isn't important.
  - Think very carefully about what is important.
  - Don't do the wrong things the right way; do the right things, even moderately well. This relates to being a perfectionist. Don't try to make everything perfect; only try on the things that matter. This relates back to the 80/20 rule. I need to identify the 80 and 20 in my own career (see below).
  - Find the time of day when you are most creative and defend it. Outside of this window, who cares?
  - Batch draining activities like email, bureaucracy, arXiv, etc... into mental deadzones.
  - Don't do the same thing multiple times; it is soul-crushing. For example, how many times have I tried to "learn" SoS? Do it once and do it properly.
  - Break big tasks into small pieces. This is an important skill that relates to the point below. Whenever you show up during the creative time window, you should already know what the plan is. Don't show up and spend the first 30 minutes "planning". That drains all the momentum.
  - How is the POTUS able to manage stress? Others manage all the small details and his schedule; his only job is to listen to his secretary on where to be and then give his full attention to that particular task. I don't have a secretary, so I have to invent an imaginary one in my head that schedules my day. My only job is to follow the schedule.
- Poincare and the French engineers.
  - One of Poincare's key principles was to exploit the subconscious; I don't think I do this enough. If you consciously overthink something, you will damage your mind. Instead, while you are making conscious progress, keep at it. Once you get stuck, just give it up and move on to something else which is more entertaining. This is why it is possible to work on multiple projects at once; eventually they will all come to fruition, but you can waste less time being stuck. At any given time, just work hard on what makes you satisfied. Don't worry about spreading yourself too thin; the only thing that matters is learning and having momentum. However, do maintain a good system for organizing knowledge and practice. That way, you can make sure to pick up right where you left off.
  - A few hundred years ago, many of the "great" French "mathematicians" were actually engineers. Only 100+ years later, was it realized that the tools they developed to solve real-world engineering problems had a deeper theory. Nowadays, I think we have too many "pure scientists" (pure math, TCS, theoretical statistics, theoretical physics). To be frank, I don't care that much about science. I just want to develop some skills which might allow me to solve some problems that help other people, so that I give something back to society and don't just consume. Very few great scientific ideas are actually recognized during the lifetime of the inventor. So, if you want to become famous in a theoretical discipline during your PhD, you are almost guaranteed to fail unless you are some once-in-a-generation genius. Hence, the only justification for doing research in these disciplines is the selfish one. The only people who really succeed in these disciplines do it because they find it naturally "fun" (which I don't). Paul Graham would say that these people like [collecting bus tickets](http://paulgraham.com/genius.html).
  - So how can I make the best of my graduate studies? I need to find some concrete, applied problem that I want to solve. One option might be related to control/RL/energy markets. Build the theory needed to solve this problem. Then, the only potential outcome of my PhD is a win: regardless of what happens after the PhD, I will have learned many useful, practical skills and made some progress on an important real-world problem. On the other hand, if you work on theory alone, you are almost guaranteed to fail. Since I don't find it fun, the only way that I will be satisfied is if I produce some "nice" ideas. But, this is unlikely (for the reasons above). So, in the end, I will have also failed in learning any useful skills.
  - Most of the trending ideas in TCS (and theory in general) are absolute BS that will be forgotten in 10 years. Yet, the gatekeepers reward the select few who work on these things. If you put your sense of worth in the hands of others (who aren't particularly wise people), then you are setting yourself up to be unhappy.
- Sadhguru talked about inertia (tamas). Fighting inertia is difficult and damaging, so don't do it in the first place. Don't allow the inertia to develop and actively work to eliminate it each day (through rest, relaxation, meditation, sleep, food, etc...). Why is it that I can read 200 pages of a fiction book in a day and follow the plot, but I can't even do 20 pages from a textbook? Connecting to the points above, a healthy body and mind will allow one to sustain energy and focus over several hours.
- I have a misconception that I should always be disciplined and do exactly 2 hours on IBC, 1.5 hours on qual, 1 hour on learning, etc... I don't think this works very well over a long period of time (> 1 week). It crushes the inspiration and motivation and leads to accumulation of inertia. While discipline is important, discipline applied in the wrong way will dull your knife (and grind it to dust). Discipline should only be used to eliminate bad habits; once the bad has been eliminated, the good should follow without having being forced.
- Don't inflate/exaggerate things in your mind. Things in the future look big and scary in the present, but aren't so when they are actually realized. For example, I keep worrying about the qual exam and how I need to spend 900 hours preparing (2 hours every day for ... days/weeks/months/...) and so on. If I really wanted to, I could knock out the preparations in one week.
- It is OK not to understand everything deeply. Just learn something.
- I like [these essays by Bertrand Russell](https://en.wikipedia.org/wiki/In_Praise_of_Idleness_and_Other_Essays) on idleness. Why should we kill ourselves with work?


### Concrete technical ideas

Let me become an applied mathematician. I recognize that math is important to solve real problems and sometimes there is value in developing the surrounding theory. But, in the long term, I don't care too much where it goes. I view math as a decentralized project; it will never be solved fully. Instead, we just locally develop those areas which help us on a day-to-day basis.

Based on what I have studied so far I think SoS is a good starting point. It is centrally located and can connect me to different subjects (statistics, TCS, control, optimization, algebra, convex geometry). I want to explore all these connected areas. Why isn't it more widely acknowledged? I think one of its major drawbacks is implementability.

I want to collect a variety of tools and know how and when to apply them. I also want to learn how to build big systems and work with data.
