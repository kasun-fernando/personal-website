---
layout: page
permalink: /Research/
---
Broadly speaking, the prime focus of my research is the interplay between probability theory, dynamical systems and statistics. I investigate 
- statistical properties of dynamical systems and Markov processes,
- inferential statistics in the context of dynamical systems, and 
- higher order asymptotics for limit theorems    

using spectral theory and a combination of techniques from classical probability theory, stochastic analysis, statistics and dynamical systems. Recently, I have started looking at      
- applications of machine learning to solve related problems. 

Below, I have listed some of my research interests, the motivation behind them and the collaborators I work with. If you find the problems interesting and would like to discuss, don't hesitate to write to me.                     

1. Extension of the classical theory of Edgeworth expansions to non-lattice discrete random variables (Classical Probability Theory)          
                                      
In applications, the dynamically generated data available to us are always finite-time observations. Hence, one key problem is to control the error of approximation of asymptotic behaviour. When the observations are independent identically distributed (iid), a uniform asymptotic expansion called the Edgeworth Expansion is used to describe the error of normal approximation in the Central Limit Theorem (CLT). The classical theory about these expansions is far from complete and does not discuss discrete random variables. As the first step, we extended the existing theory to include typical discrete random variables.                             

As the next few steps, we have some questions in mind. Is it possible to describe the error in the CLT when we pick a particular discrete random variable instead of describing the typical error? In particular, how do the Diophantine properties of the support of the discrete random variable affect this error? Also, in the absence of uniform error estimates, can we describe the error in weaker norms?                               

Collaborators: <a href="https://www.math.umd.edu/~dolgop/">Dmitry Dolgopyat</a>.

2. Error terms in the local and the central limit theorem for weakly dependent random variables (Dynamical Systems and Stochastic Processes)                  

In practice, sequences of experimental observations are never iid! So, we introduced a general theory of Edgeworth expansions for weakly dependent (possibly unbounded) random variables. As a direct application of this theory, we obtain error estimates of the CLTs for a large class of hyperbolic dynamical systems and Markov chains. The hyperbolic systems that we discuss like Sinai billiards and piecewise expanding maps are natural models in many applications -- billiard models in optics, acoustics and classical mechanics, and expanding maps in random number generators, biological and medical models to name a few. 

There are many interesting problems in this direction. There are interesting examples of non-Gaussian stable laws in dynamical systems. Is it possible to describe the error terms in other stable laws? Earlier, we were able to obtain exact limit theorems for random matrix products. Drawing parallels with random matrix products, can we obtain similar statistical properties for deterministic cocycles with sufficient decorrelation in the base dynamics?           

Collaborators: <a href="https://www.mat.uniroma2.it/~liverani/">Carlangelo Liverani</a>, <a href="http://lmba.math.univ-brest.fr/perso/francoise.pene/">Fran&ccedil;oise P&egrave;ne</a>                       
  
3. Inferential statistics for dynamically generated data (Statistics and Dynamical Systems)                     

Parameter estimation problems in dynamical systems arise naturally in many areas, including machine learning, physics, econometrics, and engineering. Moreover, one should be able to apply tools from statistics to limited dynamically generated data and obtain meaningful inferences. Therefore, it is imperative that we investigate inferential statistics in the context of dynamical systems. However, since dynamically generated data are not iid, it is not straightforward to show the accuracy of statistical techniques. So, there must be rigorous justifications for tools like maximal likelihood methods and the Bootstrap when used in such contexts.                               
  
We introduced A generic bootstrap methods for dynamical systems. Under some general conditions, using a novel continuous Edgeworth expansions, we establish not only the consistency but also the higher-order accuracy the bootstrap. We also study the empirical performance of the bootstrap methods using computer simulations.     
  
This area of research is widely open. For the pivoted bootstrap algorithm to work, either we should know the asymptotic variance or we should be able to readily estimate it. As far as we know, there is no theoretically-justified estimator for the asymptotic variance in a dynamical context. To solve this problem, can we find a good estimator for asymptotic variance? If so, what is the theoretical and empirical behavior of the pivoted bootstrap method based on this estimator? 
  
Collaborators:  <a href="https://sites.google.com/site/nzoupersonal/home">Nan Zou</a>.<p></p>
  

