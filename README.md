## Classifying Positive and Negative Restaurant Reviews

(Source : https://archive.ics.uci.edu/ml/datasets/wine+quality)

The Wine dataset consists of 3 different classes where each row correspond to a particular wine sample. Linear Discriminant Analysis (LDA) is used to model wine quality based on physicochemical tests. Principal Component Analysis (PCA) find only the axes with maximum variances where the data is most spread, within a class. However, LDA are additionally maximizing the spread between classes.


Data Set Information:

The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. 


Attribute Information:

Input variables (based on physicochemical tests):
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol
Output variable (based on sensory data):
12 - quality (score between 0 and 10)


Relevant Paper:

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties.
In Decision Support Systems, Elsevier, 47(4):547-553, 2009.


### Apply Linear Discriminant Analysis (LDA) 

The accuracy of 73 % is obtained.


