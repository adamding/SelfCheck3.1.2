---
title       : Self-Check Questions (ungraded)
subtitle    : Discrete and Continuous pdf
author      : Aidong Adam Ding
job         : Made using Slidify in R. (Click mouse then right arrow key for next slide.)
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : solarized_dark      # 
widgets     : [mathjax, quiz, bootstrap]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

--- &multitext
## Find probability


The pdf of a discrete random variable Y is 
$$
f(y) = \frac{y^2 - 1}{26},\quad y =  - 2, \ 3,\ 4.
$$

1. What is $P(0< Y \leq 5.1)$? 


*** .hint
Find all cases of $0< Y \leq 5.1$, then add up their probabilities.

*** .explanation
1. <span class="answer">0.8846</span>

Two out of the three possible values are $>0$ and $\leq 5.1$: Y=3 and Y=4. 

Hence the probability is  sum over these two cases: 

f(3)+f(4)=8/26+15/26=23/26= 0.8846154

--- &multitext
## Find probability


A continuous random variable Y has the pdf: 
$$
\begin{aligned}
f(y) = \frac{y^2}{9},\quad 0 \leqslant y \leqslant 3 
\end{aligned}
$$

1. Please calculate P(1<Y<2).

*** .hint
This is a continuous random variable. So you integrate the pdf between 1 and 2. 

*** .explanation
1. <span class="answer">0.2593</span>

This is a continuous random variable. So 
P(1<Y<2) = $\int_1^2 \frac{y^2}{9}dy =0.2592593$


