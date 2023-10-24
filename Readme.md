# Genomics Deep Learning

This repository is maintained by MariAyanami and it contains Jupyter notebooks and notes for deep learning in the field of genomics. The key libraries we work with include keras and scikit-learn, but we also utilize others such as joblib, ray, tune, hyperas, and hyperopt.

# Focus: Prediction of DNA Transcription Factor Binding Sites

## Data Exploration Phase

* DNA transcription binding site data set exploration:
    * [Jupyter notebook: data_exploration_dna_transcription.ipynb](data_exploration_dna_transcription.ipynb)
    * [Google CoLab notebook: data_exploration_dna_transcription.ipynb](https://colab.research.google.com/github/MariAyanami/genomics-deep-learning/blob/master/data_exploration_dna_transcription.ipynb#)

## Keras 1D Convolutional Neural Network

### Network Creation

* Keras 1D CNN for prediction of DNA transcription binding sites:
    * [Jupyter notebook: keras_cnn1d_dna_transcription.ipynb](keras_cnn1d_dna_transcription.ipynb)
    * [Google CoLab notebook: keras_cnn1d_dna_transcription.ipynb](https://colab.research.google.com/github/MariAyanami/genomics-deep-learning/blob/master/keras_cnn1d_dna_transcription.ipynb#)

* Cross-validated Keras 1D CNN with Scikit-learn for DNA transcription factor bind site predictions:
    * [Jupyter notebook: keras_sklearn_cnn1d_dna_transcription.ipynb](keras_sklearn_cnn1d_dna_transcription.ipynb)
    * [Google CoLab notebook: keras_sklearn_cnn1d_dna_transcription.ipynb](https://colab.research.google.com/github/MariAyanami/genomics-deep-learning/blob/master/keras_sklearn_cnn1d_dna_transcription.ipynb#)

### Data Transformations

In addition to utilizing various variants of CNN architectures, we also perform diverse transformations on Chromatin Data as listed below.

[...]
* Quantile Transform:
    * [Jupyter notebook: keras_sklearn_cnn1d_dna_transcription_quantx.ipynb](keras_sklearn_cnn1d_dna_transcription_quantx.ipynb)
    * [Google CoLab notebook: keras_sklearn_cnn1d_dna_transcription_quantx.ipynb](https://colab.research.google.com/github/MariAyanami/genomics-deep-learning/blob/master/keras_sklearn_cnn1d_dna_transcription_quantx.ipynb)

### Hyperparameter Optimization

For optimizing the performance of our models, we rely on techniques such as Hyperas and Ray/Tune for Hyperparameter Optimization of Cross-Validated 1D CNN.

[...]
* Ray/Tune for Hyperparameter Optimization (Work in Progress):
    * [Jupyter notebook: ray_tune_cnn1d_dna_transcription.ipynb](ray_tune_cnn1d_dna_transcription.ipynb)
    * [Google CoLab notebook: ray_tune_cnn1d_dna_transcription.ipynb](https://colab.research.google.com/github/MariAyanami/genomics-deep-learning/blob/master/ray_tune_cnn1d_dna_transcription.ipynb#)