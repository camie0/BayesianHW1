


Bayesian Analysis HW 1
========================================================

1. (Bolstad 4.8) Two dice are rolled. The red die has been loaded. Its probabilities are P(1) = P(2) = P(3) = P(4) = 1/5 and P(5) = P(6) = 1/10. The green die is fair. Let the event A be "the sum of the faces showing is an even number." Let the event B be "the sum of the faces showing is divisible by 3". </br> </br>
a. List the outcomes in A and find P(A).


```
   Die.1 Die.2       Probability.of.A
1      1     1  (1/5)*(1/6) = 0.03333
2      1     3  (1/5)*(1/6) = 0.03333
3      1     5  (1/5)*(1/6) = 0.03333
4      2     2  (1/5)*(1/6) = 0.03333
5      2     4  (1/5)*(1/6) = 0.03333
6      2     6  (1/5)*(1/6) = 0.03333
7      3     1  (1/5)*(1/6) = 0.03333
8      3     3  (1/5)*(1/6) = 0.03333
9      3     5  (1/5)*(1/6) = 0.03333
10     4     2  (1/5)*(1/6) = 0.03333
11     4     4  (1/5)*(1/6) = 0.03333
12     4     6  (1/5)*(1/6) = 0.03333
13     5     1 (1/10)*(1/6) = 0.01667
14     5     3 (1/10)*(1/6) = 0.01667
15     5     5 (1/10)*(1/6) = 0.01667
16     6     2 (1/10)*(1/6) = 0.01667
17     6     4 (1/10)*(1/6) = 0.01667
18     6     6 (1/10)*(1/6) = 0.01667
```


b. List the outcomes in B and find P(B).


```
   Die.1 Die.2       Probability.of.B
1      1     2  (1/5)*(1/6) = 0.03333
2      1     5  (1/5)*(1/6) = 0.03333
3      2     1  (1/5)*(1/6) = 0.03333
4      2     4  (1/5)*(1/6) = 0.03333
5      3     3  (1/5)*(1/6) = 0.03333
6      3     6  (1/5)*(1/6) = 0.03333
7      4     2  (1/5)*(1/6) = 0.03333
8      4     5  (1/5)*(1/6) = 0.03333
9      5     1 (1/10)*(1/6) = 0.01667
10     5     4 (1/10)*(1/6) = 0.01667
11     6     3 (1/10)*(1/6) = 0.01667
12     6     6 (1/10)*(1/6) = 0.01667
```


c. List the outcomes in A and B, and find P(A and B).


```
  Die.1 Die.2 Probability.of.A.and.B
1     1     5  (1/5)*(1/6) = 0.03333
2     2     4  (1/5)*(1/6) = 0.03333
3     3     3  (1/5)*(1/6) = 0.03333
4     4     2  (1/5)*(1/6) = 0.03333
5     5     1 (1/10)*(1/6) = 0.01667
6     6     6 (1/10)*(1/6) = 0.01667
```


d. Are the events A and B independent? Explain why or why not. </br> </br>
No, if A and B were independent then the P(A and B) = P(A)*P(B), while in this situation P(A and B) = P(A) = P(B)


2. (Carlin and Louis problem 1.1) Let $\theta$ be the true proportion of men over the age of 40 in your community with hypertension. Consider the following "thought experiment": </br> </br>
a. Though you may have little or no expertise in this area, give an initial point estimate of "$\theta$"
