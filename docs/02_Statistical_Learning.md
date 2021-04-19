# Statistical Learning

## Conceptual Exercises

**Question 1: Flexible and inflexible statistical learning methods.**

*(a):* If sample size (n) is very large and the number of predictors is small (p) I would expect a flexible statistical learning method to perform better than an inflexible method. This is where sample sizes are large one can assume that the variance will be a lesser contributor to the irreducible error than bias. And, the bias of the more flexible method will be lower than the bias of the more flexible method.

*(b):* If there is a large number of predictors (p) and a small number of data points (n) I would expect a flexible statistical learning method to perform worse than an inflexible method. This is because a flexible method would be likely to have high variance (i.e. the component of the reducible error associated with the differences between model prediction over different training sets). Hence, the more flexible method would be more prone to overfitting the small number of training data points (than the inflexible method) and in turn be likely to return worse results. This is of course a generalisation and the performance of flexible vs. inflexible methods varies from dataset to dataset.

*(c):* If the relationship between the response variable and the predictor variables is highly non linear I would expect a flexible statistical learning method to perform better than an inflexible method. This is because a relatively inflexible methods (such as linear regression) tend to have assumptions around linearity embedded within them, whereas more flexible methods do not (e.g. splines).

*(d):* If the variance of the error terms is extremely high I would expect a flexible statistical learning method to perform worse than an inflexible method. This is because with a flexible model there would a tendency to overfit the large amount noise (i.e. very high variance in error terms) in the data. Whereas, the less flexible method would be less sensitive to the noise and in many cases could well do a better job of extracting the signal (i.e. relationship) between the predictors and the response variable.

**Question 2: Regression or classification problems.**

*(a):*

-   Problem type: regression (salary is a continuous variable);

-   n = 500;

-   and, p = 3.

*(b):*

-   Problem type: classification (success or failure is a binary variable);

-   n = 20;

-   and, p = 13.

*(c):*

-   Problem type - regression (% change is a continuous variable);

-   n = 52;

-   and, p = 3.

## Applied Exercises
