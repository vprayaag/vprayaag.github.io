---
layout: default
---



---
# BRAIN DUMP BELOW
---

2. A collection of problems related to construction of RIP matrices

See chapter 5 of these notes by Bandeira: https://cims.nyu.edu/~bandeira/TenLecturesFortyTwoProblems.pdf. RIP matrices are useful in several contexts. It is known that they exist. In fact, a random matrix often posseses RIP. One (hard) open problem is to give an explicit, deterministic construction of RIP matrices.

Another problem is given a matrix, test if it has RIP. If such an algorithm existed, one could design a randomized algorithm for producing RIP matrices, which is partial progress towards the first problem.

It is known that a random Gaussian matrix often has RIP. In practical settings, like compressed sensing, it is hard for people to implement measurement matrices according to such distributions. There are other random matrices, like random Fourier matrices, which are easier to implement. However, the easier to implement distributions may require more measurements to guarantee RIP. See the lecture notes for details on tightening up bounds.

Here are some useful resources:
-https://cims.nyu.edu/~bandeira/TenLecturesFortyTwoProblems.pdf
-http://people.seas.harvard.edu/~minilek/cs229r/fall15/lec.html videos
-http://people.seas.harvard.edu/~minilek/madalgo2015/index.html notes

Additionally, in Bandeira's notes, the following problems are related and/or interesting: 3.2, 6.1, 6.4, 10.1

3. Some problems related to power method

In particular, 10.1 and 3.2 seem to be related to the power method, another algorithm which is practical, but (maybe?) not so many provable results are known (or, it performs poorly in theory, but well in practice). There may be some open directions in "fixing" or "improving" the power method. Problem 10.1 seems like it may have some connections to AM 254
