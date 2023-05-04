Download Link: https://assignmentchef.com/product/solved-cs6313-mini-project-3
<br>
<ol>

 <li> Suppose we would like to estimate the parameter <em>θ</em>(<em>&gt; </em>0) of a Uniform (0<em>,θ</em>) population based on a random sample <em>X</em><sub>1</sub><em>,…,X<sub>n </sub></em>from the population. In the class, we have discussed two estimators for <em>θ </em>— the maximum likelihood estimator, <em>θ</em><sup>ˆ</sup><sub>1 </sub>= <em>X</em><sub>(<em>n</em>)</sub>, where <em>X</em><sub>(<em>n</em>) </sub>is the maximum of the sample, and the method of moments</li>

</ol>

estimator, <em>θ</em><sup>ˆ</sup><sub>2 </sub>= 2<em>X</em>, where <em>X </em>is the sample mean. The goal of this exercise is to compare the mean squared errors of the two estimators to determine which estimator is better. Recall that the <em>mean squared error </em>of an estimator <em>θ</em><sup>ˆ </sup>of a parameter <em>θ </em>is defined as <em>E</em>{(<em>θ</em><sup>ˆ</sup>−<em>θ</em>)<sup>2</sup>}. For the comparison, we will focus on <em>n </em>= 1<em>,</em>2<em>,</em>3<em>,</em>5<em>,</em>10<em>,</em>30 and <em>θ </em>= 1<em>,</em>5<em>,</em>50<em>,</em>100.

1

<ul>

 <li>Explain how you will compute the mean squared error of an estimator usingMonte Carlo simulation.</li>

 <li>For a given combination of (<em>n,θ</em>), compute the mean squared errors of both <em>θ</em><sup>ˆ</sup><sub>1 </sub>and <em>θ</em><sup>ˆ</sup><sub>2 </sub>using Monte Carlo simulation with <em>N </em>= 1000 replications. <em>Be sure to compute both estimates from the same data.</em></li>

 <li>Repeat (b) for the remaining combinations of (<em>n,θ</em>). Summarize your results graphically.</li>

 <li>Based on (c), which estimator is better? Does the answer depend on <em>n </em>or <em>θ</em>? Explain. Provide justification for all your conclusions.</li>

</ul>

<ol start="2">

 <li> Suppose the lifetime, in years, of an electronic component can be modeled by a continuous random variable with probability density function</li>

</ol>

where <em>θ &gt; </em>0 is an unknown parameter. Let <em>X</em><sub>1</sub><em>,…,X<sub>n </sub></em>be a random sample of size <em>n </em>from this population.

<ul>

 <li>Derive an expression for maximum likelihood estimator of <em>θ</em>.</li>

 <li>Suppose <em>n </em>= 5 and the sample values are <em>x</em><sub>1 </sub>= 21<em>.</em>72<em>,x</em><sub>2 </sub>= 14<em>.</em>65<em>,x</em><sub>3 </sub>= 50<em>.</em>42<em>,x</em><sub>4 </sub>= 28<em>.</em>78<em>,x</em><sub>5 </sub>= 11<em>.</em> Use the expression in (a) to provide the maximum likelihood estimate for <em>θ </em>based on these data.</li>

 <li>Even though we know the maximum likelihood estimate from (b), use the data in(b) to obtain the estimate by <em>numerically </em>maximizing the log-likelihood function using optim function in R. Do your answers match?</li>

 <li>Use the output of numerical maximization in (c) to provide an approximatestandard error of the maximum likelihood estimate and an approximate 95% confidence interval for <em>θ</em>. Are these approximations going to be good? Justify your answer.</li>

</ul>