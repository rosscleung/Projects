## Custom Transformer, Pipeline, and FeatureUnion
* A short example on how to build your own SciKit-Learn transformer. 
* Sometimes you want to do some custom data pre-processing before running it through a model. To add these steps into a pipeline, you will need to wrap those custom pre-processing steps into a custom transformer.
* To combine multiple custom pre-processing transformers, a SciKit-Learn function called FeatureUnion comese in handy. 
* With the combination of custom transformers and FeatureUnion, you can build multi-layer pipelines.

## Nested Cross Validation
* In search for optimal hyperparameters, a handy SciKit-Learn function called GridSearchCV can be used.
* One downside to just using GridSearchCV is that you are using the same data used to search for the optimal hyperparameters to estimate these parameter generlization error.
* The best practice is to use a nested cross validation technique to use different data sets during hyperparameter searching and estimating their generalization error.



## Unsupervised Learning Performance - Silhouette Score Analysis
* In unsupervised learning, usually you don't have "target answers" to compare the model's identified clusters.
* In this exercise, I will show how to use unsupervised learning to identify clusters and assess the quality of such clusters using a score called the Silhouette score

## Multi-Label Classification
* This notebook shows how to do multi-label (not simply multi-class) classification with algorithms that are both ready / not ready out of the SciKit-Learn box. 
