# Logistic-Regression
In statistics, the logistic model is used to model the probability of a certain class or event existing such as pass/fail, win/lose, alive/dead or healthy/sick. This can be extended to model several classes of events such as determining whether an image contains a cat, dog, lion, etc. Each object being detected in the image would be assigned a probability between 0 and 1 and the sum adding to one.
Logistic regression is used to describe data and to explain the relationship between one dependent binary variable and one or more nominal, ordinal, interval or ratio-level independent variables.

I have a real world dataset of Weather forcast of Szeged which is third largest city of Hungary.
This dataset contain the category values of predicted variable (dependent variable), so I have decided to apply Logistic Regression on it.

According to my working style, I have applied the preprocessing on the dataset which includes;
1. Data Cleaning
2. Features Representation
3. Feature Extraction
4. Feature Selection.

During preprocessing, I have also used seaborn library and matplotlib library to draw graphs.
Graphs are very important to gain knowledge about the problem.
"A picture speaks louder than words"

Finding corelation is also very important so I cannot ignore this and applied it in this problem.

After finding corelation, i have assigned a threashold of 0.1 and extracted those features who's corelation is greater than 0.1.

I have also detected outliers, removed them.

This dataset is mixture of both numerical data and categorical data. For categorical data, encoding is very necessory. So, I have used One Hot Encoding.

To calculate Variance Inflation Factor(VIF) of each Iindependent Variable, we need to ignore the real Dependent Variable and make each Independent Variable our target feature. For this purpose we perform Auxillary Regression.

After applying regression model, it is time to check whether the model is good or not.

I have applied the following error finding techniques:
1. R-Square value
2. Root Mean Square Error
3. Mean Absolute Error
4. Root Mean Absolute Error
5. Training and Test Score

all the above error finding techniques shows the goodness of the model which mean model is good.

Regularization of the model is important, so I have used Cross Validation method, then applied the regression equation and find out a expected result.


