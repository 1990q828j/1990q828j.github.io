---
layout: post
title:  Jeklyll for study post - Math and Code
date:   2016-3-4 13:46
categories: jekyll update
---

Jekyll plus Github Pages can build a powerful personal blog. There is almost one year since I first used it.

It is especially useful for math presentation and code and graphs. In the class of Geo 597, there are so many proofs and calculations, rules and principles needed to be taken in notes. Review them, or estabilsh the proofs by myself would largely improve the understandings.

#### Math like this:

Weighted linear combination:

$$
\begin{equation}
\hat{V} = \sum_{i=0}^n w_i V_i\\

\end{equation}
$$

$$
% gather means group and center
\begin{gather}
\hat{V} = \sum_{i=0}^n w_i V_i\\
\\
\mbox{Union: }  A\cup B = \{x\mid x\in A \mbox{ or } x\in B\} \\
\mbox{Concatenation: }  A\circ B  = \{xy\mid x\in A \mbox{ and } y\in B\} \\
\mbox{Star: }  A^\star  = \{x_1x_2\ldots x_k \mid  k\geq 0 \mbox{ and each } x_i\in A\} \\

\sin A \cos B = \frac{1}{2}\left[ \sin(A-B)+\sin(A+B) \right] \\
\sin A \sin B = \frac{1}{2}\left[ \sin(A-B)-\cos(A+B) \right] \\
\cos A \cos B = \frac{1}{2}\left[ \cos(A-B)+\cos(A+B) \right] \\

\frac{d}{dx}\left( \int_{0}^{x} f(u)\,du\right)=f(x)\\
f(x,h) = \frac{A x}{1 + B x}\\
\end{gather}
$$

#### Code like this:
{% highlight r %}
## Clear the workspace and load package dependencies: 
rm(list=ls())   
require(pdgControl)
require(reshape2)
require(ggplot2)
require(data.table)
v = 1:10
mean(v)
min(v)
max(v)
range(v)
v = c(4,2,3,9,1)
length(v)
l = c(TRUE, FALSE, FALSE, TRUE)
any(l)
all(l)
l = c(TRUE, FALSE, FALSE, TRUE)
sum(l)
{% endhighlight r %}


**And tables and graphs to continue adding here...**

**Also useful for taking notes of useful links...**



whatever is welcome to be post here! 