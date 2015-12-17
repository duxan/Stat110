# L1 notes

<sup><sup>*NOTE:* render with [markmon](https://github.com/yyjhao/sublime-text-markmon)  
*Course pages* (include videos and other material): [Statistics 110: Probability](http://projects.iq.harvard.edu/stat110/)</sup></sup>

## Defs:
**Sample space** is the set of all possible outcomes of an experiment  
**Event** is a subset of a sample space  

*Naive def of probability*:  

$$ P(A)=\frac{\#\ Favorable\ events\ regarding\ A}{\#\ Possible\ events,\ i.e.\ Sample\ space\ size} $$

Assumes:  
- all outcomes equally likely  
- finite sample space

Problem: How to count events (favorable or in whole sample space) 

## Counting:  
1. Multiplication rule:  
If we have $n_1$ possible outcomes of an experiment and for each outcome of 1st experiment there are $n_2$ possible outcomes, and for each outcome of 2nd experiment there are ..., and for each outcome of an r-th experiment there are $n_r$ outcomes, then there is $n_1\cdot n_2\cdot\ldots\cdot n_r$ possible outcomes.

But counting may be with replacement (counted events are returned in *pool*) or w/out replacement. Also, order of counted events may matter or not. 

$$ \binom{n}{k} \buildrel\text{def}\over{=} \frac{n!}{k!(n-k)!} $$

Sampling table (choose $k$ objects out of $n$, should follow directly from multiplication rule):

$\,$ | Order | NO order
 --- | --- | ---
**Replace** | $n^k$ | $\binom{n+k-1}{k}$
**No replace** | $n\cdot (n-1) \ldots (n-k +1)$ | $\binom{n}{k}$

Ordered combinations = permutations


