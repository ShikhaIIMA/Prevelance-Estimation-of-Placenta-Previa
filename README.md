# Prevelance-Estimation-of-Placenta-Previa
The objective is to determine the proportion/probability of female births in women having an unusual medical condition during pregnancy called Placenta Previa. In Germany, out of total 980 placenta previa births, 437 were found to be female. The problem is to determine that how much evidence this data lends to the claim that proportion of female births in placenta previa cases is less than that in general population (0.485)

Procedure steps For Bayesian Update & Inference:
1. Uniform prior [0,1] is considered for the unknown proportion parameter and data likelihood is binomial in nature. So, posterior is Beta(438,544). Simulate 1000 draws from posterior distribution. Obtain summary of simulations in form of mean, median, standard deviation and 95% central posterior interval 
2. Obtain summary of the logit and odds transformation of the parameter. 
3. Assess sensitivity of the posterior distribution by changing values of α and β while keeping the prior mean same(α/α+β). Inference: 1.
