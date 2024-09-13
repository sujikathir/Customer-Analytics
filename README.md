# Customer-Analytics: Project 1

![](https://github.com/AkilsuryaS/Customer-Analytics/blob/main/images/Cover%20pic.jpeg)

### Datasets
• billboard.csv
• khakichinos.csv 
• books.csv

### Models used:
* **Poisson Model** - A statistical model that describes the number of events occurring within a fixed interval of time or space. It assumes that these events happen independently of each other and at a constant average rate. The Poisson distribution is used to model count data.
* **Negative Binomial Distribution Model** - A statistical model that extends the Poisson model to account for over-dispersion, where the variance exceeds the mean. The NBD model introduces a parameter to handle this extra variability, making it suitable for count data with more dispersion than the Poisson model can handle.
* **Poisson Regression Model** - A type of generalized linear model (GLM) used to predict a count dependent variable based on one or more independent variables. It assumes the response variable follows a Poisson distribution, and the logarithm of its expected value is a linear combination of the predictor variables.
* **NBD Regression Model** - Similar to the Poisson regression model but used when the count data shows over-dispersion. It incorporates an extra parameter to account for the greater variability, providing a more flexible approach for modeling count data when the Poisson assumptions do not hold.

### Task
To write a code for the following models and predict it's MAximum Likelihood Estimation (MLE), compare between models and explain which is better and why. Also, provide some managerial takeaways if possible.

# Customer-Analytics: Project 2

### Datasets
• candy.csv
• articles.csv

### Models used:
**(a) the Poisson model**
**(b) the NBD model**
**(c) the Zero Inflated NBD model:** Zero Inflated Negative Binomial (NBD) model is used for count data that has an excess of zero counts, which is not well captured by standard count models like Poisson or regular NBD. This model combines a standard count model (like NBD) with a point mass at zero, essentially allowing for two processes: one that generates zeros and another that generates counts following an NBD distribution.

**Components:**
Zero-inflation: Models the probability of an excess zero.
NBD: Models the counts (including zeros that are not excess).

**(d) Finite Mixture models for 2, 3, and 4 segments:** Finite Mixture Models assume that the population is a mixture of several distinct subpopulations, each described by its own distribution. The data is assumed to come from these different subpopulations or segments. 

**Components:**
`Subpopulations:` Each segment has its own distribution parameters.
`Mixing Proportions:` Probabilities that an observation belongs to a particular subpopulation.

`For 2, 3, and 4 segments:`
`2 Segments:` The data is modeled as a combination of two distinct subpopulations.
`3 Segments:` The data is modeled as a combination of three distinct subpopulations.
`4 Segments:` The data is modeled as a combination of four distinct subpopulations.


