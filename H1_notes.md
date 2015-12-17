# H1 notes

<sup><sup>*NOTE:* render with [markmon](https://github.com/yyjhao/sublime-text-markmon)  
*Course pages* (include videos and other material): [Statistics 110: Probability](http://projects.iq.harvard.edu/stat110/)</sup></sup>

## Practice

1. Fill in <, > or =
	a) P(sum of 4 = 21) ? P(sum of 4 = 22)  
	sum could be from (4, 24)  
	21: 24-3, so (6,6,6,3), (6,6,5,4) and (6,5,5,5) are new sets
	we have $\frac{4!}{3!\cdot 1!}=4$, $\frac{4!}{2!\cdot 1!\cdot 1!}=12$ and $\frac{4!}{3!\cdot 1!}=4$  
	22: 24-2, so (6,6,6,4) and (6,6,5,5) are new sets for counting
	we can have $\frac{4!}{3!\cdot 1!}=4$ of first and $\frac{4!}{2!\cdot 2!}=6$  
	A > B  
	b) P(2 letter word palindrom) ? P(3 letter word palindrom)  
	first and last char are the same  
	2: 2 same chars out of 24 = $\binom{24}{1}\cdot \binom{24}{1}$  
	3: 3 chars first and last same, middle any char = $\binom{24}{1}\cdot \binom{24}{24}\cdot \binom{24}{1}$  
	A = B  
2. 5 out of 52 cards  
	a) flush (all 5 of same suit, excluding royal flush) = $\frac{4\cdot (\binom{13}{5}-1)}{\binom{52}{5}}$  
	b) two pair (two pairs and other card)  
	there are 13 pairs, we draw 2 of them, so 13C2, for each pair we need 2 same cards from 4 possible flavour, 4C2	$\frac{\binom{13}{2}\binom{4}{2}^2\cdot\binom{11}{1}\binom{4}{1}}{\binom{52}{5}}$   
3.  




## Homework