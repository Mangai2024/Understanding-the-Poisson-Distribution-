# Understanding-the-Poisson-Distribution-
Poisson Distribution
Overview
The Poisson Distribution is a probability distribution used to model the number of events occurring within a fixed interval of time, space, or another dimension, where these events occur independently of each other and at a constant average rate.

Key Characteristics
Discrete Distribution: It deals with discrete events (e.g., the number of occurrences).
Parameters: Defined by a single parameter, λ (lambda), which represents the average number of occurrences in the interval.
Independence: Events occur independently of each other.
Probability Mass Function (PMF)
The formula to calculate the probability of exactly 
k
k events in a given interval is:

P
(
X
=
k
)
=
λ
k
e
−
λ
k
!
P(X=k)= 
k!
λ 
k
 e 
−λ
 
​
 
Where:

X
X: Number of events
λ
λ: Average number of events
e
e: Euler’s number (~2.71828)
k
!
k!: Factorial of 
k
k
Applications
The Poisson Distribution is widely used in various fields such as:

Queueing Theory: Number of customers arriving at a service point.
Telecommunications: Number of calls received at a call center.
Biology: Number of mutations in a DNA sequence.
Traffic Flow: Number of cars passing through a toll gate.
Finance: Number of insurance claims in a time period.
Properties
Mean: 
E
[
X
]
=
λ
E[X]=λ
Variance: 
Var
(
X
)
=
λ
Var(X)=λ
Skewness: 
Skew
(
X
)
=
1
λ
Skew(X)= 
λ
​
 
1
​
 
Kurtosis: 
Kurt
(
X
)
=
1
λ
Kurt(X)= 
λ
1
​
 
Example
Suppose a call center receives an average of 5 calls per hour (
λ
=
5
λ=5).

What is the probability of receiving exactly 3 calls in an hour?
Using the PMF formula:

P
(
X
=
3
)
=
5
3
e
−
5
3
!
=
125
⋅
0.00674
6
≈
0.1404
P(X=3)= 
3!
5 
3
 e 
−5
 
​
 = 
6
125⋅0.00674
​
 ≈0.1404
Thus, the probability is approximately 14.04%.

**Visualization**
The shape of the Poisson distribution varies with 
λ
λ:

For small 
λ
λ, the distribution is highly skewed.
As 
λ
λ increases, it becomes more symmetric and approaches a normal distribution.
