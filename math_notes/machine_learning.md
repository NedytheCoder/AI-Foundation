# Machine Learning run through
Machine learning is simply the ability of a machine to learn and replicate human behaviour based of data. In essence, when we say we're modelling or creating a model, we're simply feeding selected learning algorithms with necessary data to perform the desired action

## Machine Learning ML/Deep learning DL/Artificial Intelligence AI
These 3 are often used interchangeably but there's a subtle nuance to each of them
### ML
- Simply an algorithm that learns and performs based of the data exposed to it. Typical ML 

### DL
- Layers of neural networks built with ML algorithms, aka ML's elder and more complex sibling

### AI
- Leverages ML and DL techniques to solve problems, so it's basically just a blanket term for everything that consist of machines that learn

## ML Algorithms
These are just a set of instructions used to solve problems. They aid in predicting, classifying, improving performance of any software application, etc. As I said earlier, ML learns through data, so PERFORMANCE OF THE ALGORITHM is evaluated based on the quality of input data.

## Real life applications include:
Predict weather forecast, determine traffic rules, CO2 emission, etc

# Types of ML
ML is literally about learning via data. Now I just learned that this learning goes on in 3 different ways and they are:
## Supervised Learning
- Inputs and outputs are known and are used to train and evaluate accuracy of the model
- A lot like being supervised by a supervisor. 
- Algorithms: Classification and Regression 
- Common example methods are: Linear and logistic regression, Support Vector Machines, Decision Trees, etc. 
- Application: Predicting year-wise temperature rise and fall while being armed with previous year-wise data
- You'll see supervised learning on problems that needs to be classified or regressed

## Unsupervised Learning
- Complete opposite of the above.
- Ain't nobody knows the desired output
- We simply want the algorithm to find patterns and recognize relationships between data points
- Application: Identification of user groups based on commonalities

## Reinforcement Learning
- Learns from previous errors
- Application: Youtube recommendation

# What an ML pipeline
Seqential steps taken to automate ML workflows to produce ML models. These steps includes data extraction, raw data input, preprocessing, features, outputs, model parameters, model training, deployment, predicting outputs

Tensor flow, aesara based on theano, scipy, scikitlearn, keras, pytorch

# Data Preprocessing
This is what we do to data even before the model uses it for learning. This includes:
- Filling or removing NANs
- Encoding categories or strings(pd.get_dummies)
- Scaling
- Parse dates
- Clean texts
- Outlier removal, etc

# Important terms and their meaning
## Bias:
How accurate our data predicts its own training data
## Variance:
The difference in accuracy of the training data prediction and the test data prediction
## Overfitting:
Sometimes when our model knows a lil bit too much about our training data to the point its basically memorized which reduces accuracy in new data predictions.
## Underfitting:
When the model doesn't learn much about the data that it's simply too dumb to be reliable