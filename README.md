# AI-loan-risk-detector

This is an AI Risk detector, which is modeled on part of a project for my Certification Course for Data Analysis.

The dataset used is compiled of 3 csv files taken from a competition created by HOME CREDIT GROUP about [Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk/data). The data is analyzed using `Unsupervised Machine Learning` and `Principal Component Analysis`, or PCA. I used Unsupervised Learning in order to avoid possible human biases that influence the decision about a loan, and to see if a machine can pick up on subtle differences.

Comparing the Machine Model to the actual assesment of the loan applications, the Model tended to classify some loans assesed as `Safe` to be `Risky`. This is likely due to the model being more risk-averse to uncertainty in potential losses.


