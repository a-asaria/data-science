# data-science
Repository for all my DS/ML experiments, with folders separating each project. For the moment I'm enjoying experimenting with different techniques and seeing how they affect model performance

## Projects summary

### 2501-Playing with Tensorflow and MNIST
**Description:** Making some basic neural networks with Tensorflow to categorise handwritten digits from the MNIST dataset. I will return to this problem with more complex convolutional neural networks once I have picked up PyTorch, given the current trend towards that library

**Version history**
* [V1](https://github.com/a-asaria/data-science/blob/main/2501-MNIST-Tensorflow/250114-minst-initial-play-around-score-0-931.ipynb)
   * **Approach:** Basic network with dense layers, playing with regularisation
   * **Score:** 93.1%
* [V2](https://github.com/a-asaria/data-science/blob/main/2501-MNIST-Tensorflow/250116-v2-adding-convolutional-layer-data-augmentation.ipynb)
   * **Approach:** Data augmentaion to increase size of training dataset, seeing performance of adding single convolutional layer
   * **Score:** 98.478% (+5.378% accuracy)

### 2501-Titanic
**Description:** The classic Kaggle supervised  problem of predicting whether a set of passengers on the Titanic will survive

**Version history**
* [V1](https://github.com/a-asaria/data-science/blob/main/2501-Titanic/250110-titanic-tutorial.ipynb)
   * **Approach:** Familiarise myself with platform, using the Kaggle tutorial RF model with simple set of features
   * **Score:** 77.511%
* [V2](https://github.com/a-asaria/data-science/blob/main/2501-Titanic/250113-titanic-random-forest-h-parameter-tuning.ipynb)
   * **Approach:** Add additional features, EDA to decide how to impute incomplete feature data, using GridSearchCV to tune hyperparameters
   * **Score:** 78.708% (+1.19% accuracy, Top 15% of submissions)


