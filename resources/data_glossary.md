Sebastian Raschka  
last updated: 07/21/2014

# Data Science definitions in less than 50 words

I'd be happy about contributions or to hear your comments and suggestions. 
Please feel free to drop me a note via
[twitter](https://twitter.com/rasbt), [email](mailto:bluewoodtree@gmail.com), or [google+](https://plus.google.com/+SebastianRaschka).


<a class="mk-toclify" id="table-of-contents"></a>

#Table of Contents

- [Curse of dimensionality](#curse-of-dimensionality)
- [Data mining](#data-mining)
- [Decision rule](#decision-rule)
- [Feature Selection Algorithms](#feature-selection-algorithms)
- [Kernel Density Estimation](#kernel-density-estimation)
- [Linear Discriminant Analysis (LDA)](#linear-discriminant-analysis-lda)
- [Machine learning](#machine-learning)
- [Naive Bayes Classifier](#naive-bayes-classifier)
- [Maximum Likelihood Estimates (MLE)](#maximum-likelihood-estimates-mle)
- [Objective function](#objective-function)
- [Overfitting](#overfitting)
- [Parzen-Rosenblatt Window technique](#parzen-rosenblatt-window-technique)
- [Pattern classification](#pattern-classification)
- [Principal Component Analysis (PCA)](#principal-component-analysis-pca)





<br>
<br>

<a class="mk-toclify" id="curse-of-dimensionality"></a>
#### Curse of dimensionality
[[back to top](#table-of-contents)]

For a fixed number of training samples, the curse of dimensionality describes the increased error rate for a large number of dimensions (or features) due to imprecise parameter estimations.

<br>
<br>

<a class="mk-toclify" id="data-mining"></a>
#### Data mining
[[back to top](#table-of-contents)]

A field that is closely related to machine learning and pattern classification. The focus of data mining is often on the collection of data and combines different techniques the data in order to extract meaningful information out of data.

<br>
<br>


<a class="mk-toclify" id="decision-rule"></a>
#### Decision rule
[[back to top](#table-of-contents)]

A function in pattern classification tasks of making an "action", e.g., assigning a certain class label to an observation or pattern.

<br>
<br>

<a class="mk-toclify" id="feature-selection-algorithms"></a>
#### Feature Selection Algorithms
[[back to top](#table-of-contents)]

Algorithmic approaches as alternative to projection-based techniques like Principal Component and Linear Discriminant Analysis for dimensionality reduction of a dataset via the selection a "sufficiently reduced" feature subsets with minimal decline of the recognition rate of a classifier.

<br>
<br>

<a class="mk-toclify" id="kernel-density-estimation"></a>
#### Kernel Density Estimation
[[back to top](#table-of-contents)]

Non-parametric techniques to estimate probability densities from the available data without requiring prior knowledge of the underlying model of the probability distribution.

<br>
<br>

<a class="mk-toclify" id="linear-discriminant-analysis-lda"></a>
#### Linear Discriminant Analysis (LDA)
[[back to top](#table-of-contents)]

A linear transformation technique (related to Principal Component Analysis) that is commonly used to project a dataset onto a new feature space or feature subspace, where the new component axes maximize the spread between multiple classes, or for classification of data.

<br>
<br>

<a class="mk-toclify" id="machine-learning"></a>
#### Machine learning

[[back to top](#table-of-contents)]

A set of algorithmic instructions for discovering and learning patterns from data e.g., to train a classifier for a pattern classification task.


<br>
<br>

<a class="mk-toclify" id="maximum-likelihood-estimates-mle"></a>
#### Maximum Likelihood Estimates (MLE)

[[back to top](#table-of-contents)]

A technique to estimate the parameters that have been fit to a model by maximizing a known likelihood function. One common application is the estimation of "mean" and "variance" for a Gaussian distribution.

<br>
<br>



<a class="mk-toclify" id="naive-bayes-classifier"></a>
#### Naive Bayes Classifier
[[back to top](#table-of-contents)]

A classifier based on a statistical model (i.e., Bayes theorem: calculating posterior probabilities based on the prior probability and the so-called likelihood) in the field of pattern classification. It is based on the assumption that all features are i.i.d. (independent and identically distributed). 

<br>
<br>

<a class="mk-toclify" id="objective-function"></a>
#### Objective function
[[back to top](#table-of-contents)]

A function that is to be optimized (minimizing or maximizing a numerical value depending on a particular task or problem), for example, an objective function in pattern classification tasks could be to minimize the error rate of a classifier.

<br>
<br>

<a class="mk-toclify" id="overfitting"></a>
#### Overfitting
[[back to top](#table-of-contents)]

The result of using to many parameters that are necessary to describe a given model and thereby a detrimental increase of the complexity of the model.
A good indicator for overfitting is a high prediction accuracy on a training dataset but a low prediction accuracy on a test dataset.

<br>
<br>

<a class="mk-toclify" id="parzen-rosenblatt-window-technique"></a>
#### Parzen-Rosenblatt Window technique
[[back to top](#table-of-contents)]

A non-parametric kernel density estimation technique for probability densities of random variables if the underlying distribution/model is unknown. A so-called window function is used to count samples within hypercubes or Gaussian kernels of a specified volume to estimate the probability density.

<br>
<br>

<a class="mk-toclify" id="pattern-classification"></a>

#### Pattern classification

[[back to top](#table-of-contents)]

The usage of patterns in datasets to discriminate between classes, i.e., to assign a class label to a new observation based on inference.

<br>
<br>

<a class="mk-toclify" id="principal-component-analysis-pca"></a>
#### Principal Component Analysis (PCA)
[[back to top](#table-of-contents)]

A linear transformation technique that is commonly used to project a given dataset onto a new feature space  or feature subspace (for dimensionality reduction) where the new component axes are the directions that maximize the variance/spread of the data.


