# Ensemble-Learning-Bagging-and-Boosting

Ensemble is a machine learning concept in which multiple models are trained using the same learning algorithm. Bagging is a way to decrease the variance in the prediction by generating additional data for training from dataset using combinations with repetitions to produce multi-sets of the original data. Boosting is an iterative technique which adjusts the weight of an observation based on the last classification. If an observation was classified incorrectly, it tries to increase the weight of this observation. Boosting in general builds strong predictive models.

**In this repository we have applied bagging and gradient boosting on decision trees on MNIST datasets and have obtained the accuracy of 90%**
## Bagging 
Bagging is used when the goal is to reduce the variance of a decision tree classifier. Here the objective is to create several subsets of data from training sample chosen randomly with replacement. Each collection of subset data is used to train their decision trees. As a result, we get an ensemble of different models. Average of all the predictions from different trees are used which is more robust than a single decision tree classifier
 ![Bagging](https://www.simplilearn.com/ice9/free_resources_article_thumb/Bagging.PNG)
**To know more about Bagging technique | [Bagging](https://analyticsindiamag.com/primer-ensemble-learning-bagging-boosting/#:~:text=Bagging%20is%20a%20way%20to,based%20on%20the%20last%20classification.)**

## Gradient Boosting
Gradient Boosting is a popular boosting algorithm. In gradient boosting, each predictor corrects its predecessor’s error. In contrast to Adaboost, the weights of the training instances are not tweaked, instead, each predictor is trained using the residual errors of predecessor as labels.
 ![Boosting](https://miro.medium.com/max/788/1*pEu2LNmxf9ttXHIALPcEBw.png)
 ![Boosting](https://miro.medium.com/max/720/1*7EhjRtzxSj5whkHf-MxjLA.png)
**To know more about Gradient Boosting | [Boosting](https://blog.paperspace.com/gradient-boosting-for-classification/)**


## MNIST and FMNIST Dataset
### MNIST Dataset
The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning.
 ![MNIST](https://global-uploads.webflow.com/5ef788f07804fb7d78a4127a/61d68ea1ff1ea298fdcc6555_mnist%20dataset-min.png)
**To know more about MNIST dataset | [MNIST](https://www.engati.com/glossary/mnist-dataset)**

### FMNIST Dataset
The Fashion MNIST dataset is an alternative to the standard MNIST dataset. Instead of handwritten digits, it contains 70000 28x28 grayscale images of ten types of fashion items.
 ![FMNIST](https://machinelearningmastery.com/wp-content/uploads/2019/02/Plot-of-a-Subset-of-Images-from-the-Fashion-MNIST-Dataset-1024x768.png)
**To know more about FMNIST dataset | [FMNIST](https://www.educative.io/edpresso/what-is-the-fashion-mnist-dataset-in-keras)**


