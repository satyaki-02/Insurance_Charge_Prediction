**Insurance cost prediction using Regression.**

The purpose of this project was to apply regression and predict the cost of insurance.

After taking the dataset from **<a href = 'https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset' target = 'blank'>Kaggle</a>**, some pre-processing was done and the duplicates were removed keeping only the first instances of these duplicates.

After that an extensive data exploration was done visualizing the effects of different factors on charges.

Initially I fitted a linear regression mode. After that using backward elimintion, a number of factors were removed in an attempt to improve the adjusted $R^2$ score. After that I fitted a polynomial regression and again applied backward elimination.

Finally the $R^2$ score of the polynomial regression was almost similar to that of the linear regression. So, we will stick with the linear regression model due to its better explainability.
