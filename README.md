# CNN-Tensorflow

## Introduction
In this project, I will use tensorflow to construct a Convolutional Neural Network (CNN) for image recognition by using Food-11 dataset. 

## Dataset
- Food-11 Dataset
https://mmspg.epfl.ch/food-image-datasets
- some examples
<img src="https://github.com/ChristophWu/CNN-Tensorflow/blob/master/material/dataset.png" width="600"/>

## Implementation
First, I reshape all the pictures to 98x98x3 in order to make training faster. This model is consist of three layers of convolution, three layers of max pooling and two layers of FC.

## Results
- learning curve
<img src="https://github.com/ChristophWu/CNN-Tensorflow/blob/master/material/learning_curve.png" width="500"/>

- some examples of detected and undetected images
<img src="https://github.com/ChristophWu/CNN-Tensorflow/blob/master/material/right_prediction.png" width="300"/>
<img src="https://github.com/ChristophWu/CNN-Tensorflow/blob/master/material/wrong_prediction.png" width="300"/>

- feaure map of detected picture
<img src="https://github.com/ChristophWu/CNN-Tensorflow/blob/master/material/feature_right.png" width="500"/>

- feaure map of undetected picture
<img src="https://github.com/ChristophWu/CNN-Tensorflow/blob/master/material/feature_wrong.png" width="500"/>
