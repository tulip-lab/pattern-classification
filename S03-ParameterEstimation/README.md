[![GitHub watchers](https://img.shields.io/badge/tulip--lab-Pattern--Classification-brightgreen)](../README.md)
[![GitHub watchers](https://img.shields.io/badge/Module-Parameter--Estimation-orange)](README.md)

# Parameter Estimation

`Maximum Likelihood Estimation` (MLE) and `Maximum A Posteriori` (MAP) are commonly used methods for parameter estimation in statistical modeling.

- MLE aims to find the values of model parameters that maximize the likelihood function, which measures the probability of observing the given data under the assumed model. It assumes that the data points are independent and identically distributed (i.i.d.). MLE provides an estimate that is most likely to have generated the observed data. It is often used when there is no prior knowledge or assumption about the parameters. MLE estimation involves finding the parameter values that maximize the likelihood function, typically through optimization algorithms.

- On the other hand, MAP estimation incorporates prior knowledge or assumptions about the parameters by incorporating a prior distribution. It aims to find the parameter values that maximize the posterior probability of the parameters given the observed data. MAP estimation combines the likelihood function with a prior probability distribution, which represents our initial beliefs about the parameters before observing the data. By incorporating the prior, MAP estimation can provide more robust estimates, especially when the data is limited or noisy.


- The `Expectation-Maximization`  (EM) algorithm is an iterative method for finding maximum likelihood estimates of parameters in statistical models that depend on unobserved latent variables. The EM algorithm allows maximum likelihood estimation in contexts where a closed-form solution is difficult or impossible to obtain directly. It has applications in many areas, including mixture models, hidden Markov models, and fitting neural network weights. A key benefit is the ability to handle missing or hidden data in a probabilistic framework.

In summary, MLE finds the parameters that best fit just the data, while MAP finds the parameters that best fit the data given our prior beliefs about the parameter distribution. MAP can be seen as a regularized version of MLE. 


In this session, we will cover the concepts of MLE and MAP, respectively, together with the famous EM algorithm.  


## :notebook_with_decorative_cover: Lecture Slides Handouts

- [Lecture A: Parameter Estimation (1)](https://github.com/tulip-lab/handouts/blob/main/PR/PR-S03A.pdf)
- [Lecture B: Parameter Estimation (2)](https://github.com/tulip-lab/handouts/blob/main/PR/PR-S03B.pdf) 

## :writing_hand: Practicals

- [EM Algorithm](https://github.com/tulip-lab/flip01/blob/master/F1A-02-EM.ipynb)