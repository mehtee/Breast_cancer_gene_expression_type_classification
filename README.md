# Breast Cancer Type Classification using Gene Expression Dataset
I have used a breast cancer gene expression dataset from CuMiDa (Dataset GSE45827), containing 6 classes, 54676 genes (or features) and 151 samples. It can be found [here](https://www.kaggle.com/datasets/brunogrisci/breast-cancer-gene-expression-cumida), in Kaggle. This dataset has a challenge of dimensionality as the number of features are a lot. As a result, I applied different methods including ANOVA to reduce it. It became much less, but it was not enough. Additionally, I used [Autoencoder](https://en.wikipedia.org/wiki/Autoencoder) to compress the input. I applied Random Forests to evaluate each method I used during the experiment.
