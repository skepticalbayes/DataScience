## Bayesian vs Frequentist

p(**theta**|y) = p(y|**theta**)*p(**theta**)/p(y)

In bayesian we straight away assume a distribution of **theta**(p(**theta**)) given our beliefs called the prior; in frequentist we bootstrap from our sample adn find a distribution of **theta**. Even though in frequentist we dont have a fixed theta we need a distribution to do our inference. 
 
In bayesian the posterior(p(**theta**|y)) depends on the data ie. the likelihood(p(y|**theta**)) and the prior(p(**theta**)); now if the prior belief is dogmatic we need a large data set to converge to the truth of the population. Also if the data is not telling us anyhting concrete ie. has a high variance and samll size, the prior knowledge dominates and similarly if the prior is uninformative ie. has a high variance the information form the data dominates.
