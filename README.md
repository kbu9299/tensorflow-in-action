# TensorFlow 2 in Action

Wokring Environment

```bash
conda create --name tf2 python=3.7
conda activate tf2
conda install pip numpy scipy pandas matplotlib ipython jupyter seaborn pillow h5py
pip install tensorflow-gpu==2.0 gdown
```


## TensorFlow In Practice by deeplearning.ai
Introduction to TensorFlow
* [simple house price prediction](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c01e01_house_price.ipynb)
* [fashion mnist with simple neural network](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c01e02_fashion_MNIST.ipynb)
* [basic image convolution and pooling](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c01e03_basic_convolution.ipynb)
* [neural network with convoluions](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c01e04_neural_network_with_convolutions.ipynb)
* [binary classification: horse or human](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c1e05_binary_classification_horse_or_human.ipynb)
  * all images are synthesized with computer graphics.
  * ImageDataGenerator for managing dataset and feeding them into training pipeline in a systematic way. 
* [horse or human with validtation](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c01e06_horse_or_human_with_validation.ipynb)
  * add the validation dataset in the training process.
* [happy or sad](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c01e07_happy_or_sad.ipynb)

Convolutional Neural Networks in TensorFlow
* [Cats or Dogs - Filtered](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c02_covolutional_neural_network/w0101_cats_or_dogs_filtered.ipynb)
* [Cats or Dogs - Full](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c02_covolutional_neural_network/w0102_cats_or_dogs_full.ipynb)
* [Cats or Dogs - Augmented](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c02_covolutional_neural_network/w0201_cats_or_dogs_augmentation.ipynb)
* [Horse or Human -Augmentation](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c02_covolutional_neural_network/w0202_horse_or_human_with_augmentation.ipynb)
* [Horse or Human - InceptionV3](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c02_covolutional_neural_network/w0203_excercise.ipynb)
* [Transfer Learning](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c02_covolutional_neural_network/w0301_transfer_learning.ipynb)
* [Transfer Learning: Human or Horse](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c02_covolutional_neural_network/w0302_exercise_humand_transfer_lerarning.ipynb)
* [Rock Paper Scissor](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c02_covolutional_neural_network/w0401_rock_paper_scissors.ipynb)
* [Sign Lanugage Classifier](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c02_covolutional_neural_network/w0402_excercise_sign_language_classifier.ipynb)


Natural Language Processing in TensorFlow
* [BBC News](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c03_natural_language_processing/c3w1e1_excercise_bbc_news.ipynb)
* [IMDB Review](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c03_natural_language_processing/c3w2e1_imdb_review.ipynb)
* [BBC excercise](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c03_natural_language_processing/c3w2e2_excercise_bbc.ipynb)
* [IMDB Subworkds 8k with Single Layer LSTM](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c03_natural_language_processing/c3w3e1a_imdb_subwords_8k_single_layer_lstm.ipynb)
* [IMDB Subworkds 8k with Multi Layer LSTM](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c03_natural_language_processing/c3w3e1b_imdb_subwords_8k_multi_layer_lstm.ipynb)
* [IMDB Subworkds 8k with 1D Convolutional Layer](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c03_natural_language_processing/c3w3e1c_imdb_subwords_8k_1d_convolutional_layer.ipynb)
* [Sarcasm Bidirectional LSTM](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c03_natural_language_processing/c3w3e1e_sarcasm_bidirectional_lstm.ipynb)
* [Sarcasm 1D Convolutional Layer](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c03_natural_language_processing/c3w3e1f_saecasm_1d_convolutional_layer.ipynb)
* [IMDB Review GRU](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c03_natural_language_processing/c3w3e1g_imdb_review_gru.ipynb)
* [Exploring Overfitting](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c03_natural_language_processing/c3w3e2_excercise_exploring_overfitting.ipynb)
* [Shapespeare](https://nbviewer.jupyter.org/github/kbu9299/tensorflow-in-action/blob/master/tensorflow-in-practice/c03_natural_language_processing/c3w4e2_excercise_shakespeare.ipynb)




Sequences, Time Series and Prediction
