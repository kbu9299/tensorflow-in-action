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

Natural Language Processing in TensorFlow

Sequences, Time Series and Prediction
