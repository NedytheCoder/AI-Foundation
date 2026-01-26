### Machine Learning run through
Machine learning is simply the ability of a machine to learn and replicate human behaviour based of data. In essence, when we say we're modelling or creating a model, we're simply feeding selected learning algorithms with necessary data to perform the desired action

## Machine Learning ML/Deep learning DL/Artificial Intelligence AI
These 3 are often used interchangeably but there's a subtle nuance to each of them
# ML
- Simply an algorithm that learns and performs based of the data exposed to it. Typical ML 

# DL
- Layers of neural networks built with ML algorithms, aka ML's elder and more complex sibling

# AI
- Leverages ML and DL techniques to solve problems, so it's basically just a blanket term for everything that consist of machines that learn

## ML Algorithms
These are just a set of instructions used to solve problems. They aid in predicting, classifying, improving performance of any software application, etc. As I said earlier, ML learns through data, so PERFORMANCE OF THE ALGORITHM is evaluated based on the quality of input data.

# Real life applications include:
Predict weather forecast, determine traffic rules, CO2 emission, etc

## Types of ML
ML is literally about learning via data. Now I just learned that this learning goes on in 3 different ways and they are:
# Supervised Learning
- Inputs and outputs are known and are used to train and evaluate accuracy of the model
- A lot like being supervised by a supervisor. 
- Algorithms: Classification and Regression 
- Common example methods are: Linear and logistic regression, Support Vector Machines, Decision Trees, etc. 
- Application: Predicting year-wise temperature rise and fall while being armed with previous year-wise data
- You'll see supervised learning on problems that needs to be classified or regressed

# Unsupervised Learning
- Complete opposite of the above.
- Ain't nobody knows the desired output
- We simply want the algorithm to find patterns and recognize relationships between data points
- Application: Identification of user groups based on commonalities

# Reinforcement Learning
- Learns from previous errors
- Application: Youtube recommendation

## What an ML pipeline
Seqential steps taken to automate ML workflows to produce ML models. These steps includes data extraction, raw data input, preprocessing, features, outputs, model parameters, model training, deployment, predicting outputs

Tensor flow, aesara based on theano, scipy, scikitlearn, keras, pytorch

## Data Preprocessing
This is what we do to data even before the model uses it for learning. This includes:
- Filling or removing NANs
- Encoding categories or strings(pd.get_dummies)
- Scaling
- Parse dates
- Clean texts
- Outlier removal, etc

## Important terms and their meaning
# Bias:
How accurate our data predicts its own training data
# Variance:
The difference in accuracy of the training data prediction and the test data prediction
# Overfitting:
Sometimes when our model knows a lil bit too much about our training data to the point its basically memorized which reduces accuracy in new data predictions.
# Underfitting:
When the model doesn't learn much about the data that it's simply too dumb to be reliable

### Linear regression
A supervised learning algorithm used for predicting continuous values. It models the relationship between a dependent variable and one or more independent variables by fitting a linear equation to observed data. 
## Types
# Linear
- Uses the least squares criterion for estimation 
# Polynomial
- A form of linear
- The relationship between x and y is an nth degree polynomial  
# Support Vector
- Creates max data points within boundary lines and the hyperplane
- Can be used for both regression and classification 
# Decision Tree
- Literally as it sounds
# Random Forest
- An ensemble learning method that uses bagging or bootstrap aggregation techniques 
- Uses multiple decision trees in parallel and not interacting with one another to define the output
# Ridge 
- Shrinks the coefficient towards zero to reduce the complexity of data
- Deals with multicollinearity data
- Minimizes the variance of the data without increasing bias
- Regularization technique uses a loss function Residual Sum of Squares(RSS)
# Lasso 
- Least Absolute Shrinkage and Selection Operation
# Logistic

### Linear
Linear regression is a parametric approach where one makes assumptions of data for analysis. Successful regression is validating the assumptions made. These assumption include:
- The dependent and independent variables have a linear and additive relationship
- Error terms are normally distributed
- Independent variables are not correlated i.e multicollinearity doesn't exist
- Error residual terms aren't correlated i.e autocorrelation are absent
- Error terms show constant variance i.e homoscedasticity. Opposite is hetero..

### Logistics
Used to predict values based on prior observation of a dataset. It finds the relationship between qualitative discrete dependent variables and several independent variables. Primarily used for classification problems.
- A sigmoid function is used here
## Types
# Binary
For just 0 or 1
# Multinomial
For more that 2 classification i.e 0, 1 or 2, ...

### Polynomial
Linear's more complex elder bro who uses exponents(curves) rather than a straight line to fit complex data relationships

### Regularization, Algorithm

### Classifiers
Classification Algorithms
- Data that these algorithms use can either be structured or unstructured
## Classification types
- Binary classification - a, b, c, d, and SVM are typically used for this 
- Multi-class - a, c, d, f, and Gradient boost are typically used for this
- Multi-label - Multiple label c, f, and Gradient boost are typically used for this
- Imbalanced - Literally binary classification but the traditional class is way more in observations - Random Undersampling and SMOTE Oversampling techniques are typically used here
## Algorithm types
- Naive Bayes
- Linear classifier: Logistic Regression
- Decision tree classifier
- K-nearest neighbors
- Stochastic gradient descent(SDG) classifier
- Random forests 
# To decide which classifier to be used, you take into account the nature of the input data and then a classifier is determined

## How to select performance parameters
- Chose features while applying classifiers to the data set under consideration. T - True, F - False, P - Positive, N - Negative
- Looking at a confusion matrix is one way to evaluate the performance of a classifier
# The 4 metrics used for evaluation with a confusion matrix are:
- Accuracy (TN + TP)/(TN + TP + FP + FN)
- Precision (TN)/(TN + FN) OR (TP)/(TP + FP)
- Specificity 
- Recall or sensitivity (TN)/(TN + FP) OR (TP)/(TP + FN)

## Naive Bayes
- Types include Multinomial Naive bayes, gaussian and bernoulli
- Uses the principle of contingent probability, i.e Measuring the probability of an event occuring based on something else that has already occured
- Based on the bayes theorem
- Segregates different objects on the basis of certain features of variables

## Stochastic gradient descent(SDG) classifier
- Forms the basis of neural network
- It iterates through the function over and over again till we find the x where y is the smallest
- Step size = Learning rate * gradient