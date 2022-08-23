---
layout: page   
title: Research        
permalink: /Research/          
---
Broadly speaking, the prime focus of my research is the interplay between probability theory, dynamical systems and statistics. I investigate 
- statistical properties of dynamical systems and Markov processes,
- inferential statistics in the context of dynamical systems, and 
- higher order asymptotics for limit theorems    

using spectral theory and a combination of techniques from classical probability theory, stochastic analysis, statistics and dynamical systems. Recently, I have started looking at      
- applications of machine learning to solve related problems. 

Below, I discuss some of my research interests, the motivation behind them and the collaborators I work with. If you find the problems interesting and would like to discuss, don't hesitate to write to me.                     

### Extension of the classical theory of Edgeworth expansions to non-lattice discrete random variables       
(Classical Probability Theory)                   

In applications, the dynamically generated data available to us are always finite-time observations. Hence, one key problem is to control the error of approximation of asymptotic behaviour. When the observations are independent identically distributed (iid), a uniform asymptotic expansion called the Edgeworth Expansion is used to describe the error of normal approximation in the Central Limit Theorem (CLT). The classical theory about these expansions is far from complete and does not discuss discrete random variables. As the first step, we extended the existing theory to include typical discrete random variables.                             

As the next few steps, we have some questions in mind. Is it possible to describe the error in the CLT when we pick a particular discrete random variable instead of describing the typical error? In particular, how do the Diophantine properties of the support of the discrete random variable affect this error? Also, in the absence of uniform error estimates, can we describe the error in weaker norms?                               

Collaborators: <a href="https://www.math.umd.edu/~dolgop/" target="_blank">Dmitry Dolgopyat</a>.

### Error terms in the local and the central limit theorem for weakly dependent random variables    
(Dynamical Systems and Stochastic Processes)                  

In practice, sequences of experimental observations are never iid! So, we introduced a general theory of Edgeworth expansions for weakly dependent (possibly unbounded) random variables. As a direct application of this theory, we obtain error estimates of the CLTs for a large class of hyperbolic dynamical systems and Markov chains. The hyperbolic systems that we discuss like Sinai billiards and piecewise expanding maps are natural models in many applications -- billiard models in optics, acoustics and classical mechanics, and expanding maps in random number generators, biological and medical models to name a few. 

There are many interesting problems in this direction. There are interesting examples of non-Gaussian stable laws in dynamical systems. Is it possible to describe the error terms in other stable laws? Earlier, we were able to obtain exact limit theorems for random matrix products. Drawing parallels with random matrix products, can we obtain similar statistical properties for deterministic cocycles with sufficient decorrelation in the base dynamics?           

Collaborators: <a href="https://www.mat.uniroma2.it/~liverani/" target="_blank">Carlangelo Liverani</a>, <a href="http://lmba.math.univ-brest.fr/perso/francoise.pene/" target="_blank">Fran&ccedil;oise P&egrave;ne</a>                       
  
### Inferential statistics for dynamically generated data        
(Statistics and Dynamical Systems)                     

Parameter estimation problems in dynamical systems arise naturally in many areas, including machine learning, physics, econometrics, and engineering. Moreover, one should be able to apply tools from statistics to limited dynamically generated data and obtain meaningful inferences. Therefore, it is imperative that we investigate inferential statistics in the context of dynamical systems. However, since dynamically generated data are not iid, it is not straightforward to show the accuracy of statistical techniques. So, there must be rigorous justifications for tools like maximal likelihood methods and the Bootstrap when used in such contexts.                               
  
We introduced A generic bootstrap methods for dynamical systems. Under some general conditions, using a novel continuous Edgeworth expansions, we establish not only the consistency but also the higher-order accuracy the bootstrap. We also study the empirical performance of the bootstrap methods using computer simulations.     
  
This area of research is widely open. For the pivoted bootstrap algorithm to work, either we should know the asymptotic variance or we should be able to readily estimate it. As far as we know, there is no theoretically-justified estimator for the asymptotic variance in a dynamical context. To solve this problem, can we find a good estimator for asymptotic variance? If so, what is the theoretical and empirical behavior of the pivoted bootstrap method based on this estimator? 
  
Collaborators:  <a href="https://sites.google.com/site/nzoupersonal/home" target="_blank">Nan Zou</a>.
  
### Density estimation via robust normalizing flows      
(Machine Learning and Probability)

In the recent years, with the proliferation of machine learning research, modeling and prediction of real-world phenomena have progressed to the next level. There are numerous problems connected to statistics, probability theory, and dynamical systems that can be solved using machine learning. The problem of modeling an unknown probability distribution using sample data is one such example. A Normalizing flow (NF) in machine learning is a supervised learning procedure that determines the probability distribution of sample data by performing a maximum likelihood optimization.

We introduced a triangular NFs on euclidean spaces using Bernstein polynomials as coupling functions. Our NF model is robust under perturbations, ideal for compactly supported densities and can approximate any density even the ones that are multimodal and have sharp jumps. There are many real-world applications in nonlinear geometries (circular, spherical, etc.); for instance, applications in robotics and molecular modeling. Can we formulate robust normalizing flows in such non-linear geometries?

Collaborators:  <a href="https://scholar.google.com/citations?user=-j0m9aMAAAAJ&hl=en" target="_blank">Sameera Ramasinghe</a>.

### Error terms in the large deviations for weakly dependent random variables      
(Dynamical Systems and Stochastic Processes)      

For parabolic PDEs (with non-degeneracy assumptions) the fundamental solution is the transition density of the related diffusion process. Therefore, studying the long-term behaviour of fundamental solutions is the same as studying asymptotics of Markov probability densities. For a reasonable analysis, one must obtain LDPs which describe the solution at linear distances from the effective drift. A finer analysis is possible if higher order asymptotics is available. We introduced the required asymptotic expansions for probability distribution functions.     

The first term of the large deviation asymptotics of the density of a branching process is obtained in a work of Hebbar, Koralov and Nolan. Is it possible to derive higher order expansions for densities of Markov processes? Moreover, our results do not apply to lattice valued processes but techniques for lattice-valued case in our previous work extend to this setting naturally. So, is it possible to obtain similar results in the lattice-valued case?        

Collaborators: <a href="https://sites.google.com/view/pratimahebbar" target="_blank">Pratima Hebbar</a>.     

### Statistical properties of mostly expanding fast-slow partially hyperbolic systems           
(Smooth Ergodic Theory)

When systems are partially hyperbolic, as demonstrated in the series of recent influential work of De Simoi, Liverani and coauthors, the study of statistical properties becomes challenging. They demonstrate metastable behaviour in a deterministic setting for the first time by considering an open class of fast-slow partially hyperbolic systems with mostly contracting centre directions. They also study the existence of SRB measures, their rate of decay of correlations, LLTs and LDPs.        

There are some interesting questions related that require further exploration. What statistical properties are retained if the fast-slow partially hyperbolic systems considered there have mostly expanding centre directions? In particular, what conditions guarantee the existence of SRB measures and do they have exponential decay of correlations?    

Collaborators: <a href="http://www.math.toronto.edu/jacopods/" target="_blank">Jacopo De Simoi</a>.<p></p></li>