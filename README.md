# Overview
Here are my data science and machine learning sample projects, using python packages such as Pandas and SciKit-Learn! 

## Biologics Outlier Detection:
* Pharmaceutical production outlier detection
* Used data visualization and supervised machine learning to characterize the probability of an outlier occuring (Logistic Regression)

## Biologics Yield Study:
* Comprehensive study on what impacts a drug's production yield
* Used feature selection, regression models, and classification models to study the data

## Data mining:
* Python script used in conjunction with SQL to process and clean data, no machine learning here

## NLP - Classifying email authors
* A fun, quick exercise to show how a commonly used NLP classifer (Naive Bayes) can identify the author of an email from two of my colleagues.
* This technique can be applied to more than just identifying authors. It can be used to develop a model to identify spam emails or do sentiment analysis.

## Predicting Market Demand
* A regression exercise to fill in missing market demand data that is essential in an investment decision
 
## Custom Transformer, Pipeline, and FeatureUnion
* A short example on how to build your own SciKit-Learn transformer. 
* Sometimes you want to do some custom data pre-processing before running it through a model. To add these steps into a pipeline, you will need to wrap those custom pre-processing steps into a custom transformer.
* To combine multiple custom pre-processing transformers, a SciKit-Learn function called FeatureUnion comese in handy. 
* With the combination of custom transformers and FeatureUnion, you can build multi-layer pipelines.

## Nested Cross Validation
* In search for optimal hyperparameters, a handy SciKit-Learn function called GridSearchCV can be used.
* One downside to just using GridSearchCV is that you are using the same data used to search for the optimal hyperparameters to estimate these parameter generlization error.
* The best practice is to use a nested cross validation technique to use different data sets during hyperparameter searching and estimating their generalization error.

## SKLearn Neural Network
* An example showing a multi-layer perceptron (back propagation neural network) algorithm that is newly added to SciKit-Learn 0.18.
* This notebook shows a neural network identifying images with numerical digits from the famous MNIST data set.

## Unsupervised Learning Performance - Silhouette Score Analysis
* In unsupervised learning, usually you don't have "target answers" to compare the model's identified clusters.
* In this exercise, I will show how to use unsupervised learning to identify clusters and assess the quality of such clusters using a score called the Silhouette score

## Multi-Label Classification
* This notebook shows how to do multi-label (not simply multi-class) classification with algorithms that are both ready / not ready out of the SciKit-Learn box. 
