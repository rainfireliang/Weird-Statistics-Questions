# <div align="center">Weird Statistics Questions</div>

Hai Liang </br>
hailiang@cuhk.edu.hk </br>
The Chinese University of Hong Kong </br>
[Answers to some "weird" statistics questions with R code.](https://drhailiang.com/files/Weird-Statistics-Questions-V1.html)

### I.	Descriptive Statistics
#### 1. How do we represent and summarize a variable? Why do we calculate the mean and standard deviation for a variable? How about if the variable is skewed or discrete?
#### 2. We use correlation coefficients (why plural?) to quantify the (linear) relationships between two continuous variables; how can we show the relationships involving categorical/rank variables?
### II.	Inferential Statistics (Tests)
#### 3. Why can we use a sample to infer the population under what conditions? What is a sampling distribution? Is it observable? Why does large sample size work?
#### 4. What are the relationships between standard errors, sampling errors, confidence intervals, and confidence levels?
#### 5. What are the differences among T-test, Z-test, F-test, χ<sup>2</sup>-test, etc.?
#### 6. What are distribution-free tests (non-parametric tests)? We test the difference between means; can we test the difference between medians/variances? Can we test the difference between two categorical variables?
### III.	Regression (OLS)
#### 7. Can regression models (why plural?) replace all the above-mentioned tests in section II?
#### 8. What is the degree of freedom? Can a regression model be fitted with R<sup>2</sup>=1? What is over-fitting? Why should we avoid over-fitting?
#### 9. How to interpret regression coefficients (direction, magnitude/strength, significance, form)? How do we interpret when predictors are categorical? How to compare regression coefficients?
#### 10. Why is the I.I.D. assumption essential? 
#### 11.	What if residuals are normally distributed, but the dependent variable is not? Is this possible?
#### 12.	Why effect size is important? Is it true that larger coefficients indicate larger effect sizes? How do we measure the unique effect of an independent variable on the dependent variable without any confounding effects of other independent variables (or can stepwise regression models solve the problem)?
#### 13.	Is estimating the main effects from a regression model with interaction terms possible? 
### IV.	Regression (GLM)
#### 14. How do we deal with non-normally distributed dependent variables? How do we interpret the coefficients?
#### 15. Can we model the variance (instead of the mean) of the dependent variable? E.g., the variance in the salary of older people is smaller than that of young people, given equal salary.
#### 16. What is wrong with using Z-statistics (and associated p-values) of the coefficient of a multiplicative term to test for a statistical interaction in nonlinear models with categorical dependent variables (e.g., logistic regression)?
### V.	Regression (Causal Inference)
#### 17. Everyone knows that correlation is not causation, when regression coefficients could be interpreted as causal effects? Is including the lagged explanatory variable a solution?
#### 18. Is a random experiment always better than other methods to identify causality? Why or why not?
#### 19. Is it always better to control more variables than less? Should we remove non-significant variables from the regression?
#### 20.	Should we control for mediators to estimate the treatment effect?
