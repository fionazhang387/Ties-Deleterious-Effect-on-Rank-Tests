# Ties-Deleterious-Effect-on-Rank-Based-Tests

Research Objectives:
1. To study Type I and Type II error in tie-breaking methods in rank-based statistical tests using simulation. 
2. To determine a graphical representation similar to the one in Bellera (2010) for rank-based statistics with ties.
3. To examine the Type I and Type II error for discrete data, particularly those based on rankings, relative to the t-test.

 From Jeannene Duenas (1957). Methods of accounting for ties include
 1.	Mid-ranks (average of the ranks that would have been assigned to the values had there been no ties)
 2.	Assign ranks randomly with equal probability the ranks that correspond to a set of tied observations
 3.	Omit the tied observations
 4.	Break the ties in all possible ways, and use the average probability to determine whether to reject the null hypothesis.

Variables: 
1. Sample sizes used: 3 - 20, inclusive
2. Tests examined: Wilcoxon rank sum test, two-sample t-test
3. Distributions used: Normal, t, Gamma, Exponential, Cauchy, LaPlace
4. Percentage of ties: 10%, 25%, 50%
5. Presence of ties: within one sample, within each sample, across samples
6. Shift alternative: delta = 0 (null is true), 2, 5, 10

Response:
1. Type I error (probability of rejection if null is true)
2. Type II error (under various shift alternatives)

