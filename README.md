# MNIST-Image-Classification


MNIST ("Modified National Institute of Standards and Technology") is the de facto “Hello World” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

The dataset consists of two files:

1.) mnist_train.csv

2.) mnist_test.csv

The mnist_train.csv file contains the 60,000 training examples and labels.

The mnist_test.csv contains 10,000 test examples and labels.
Each row consists of 785 values: the first value is the label (a number from 0 to 9) and the remaining 784 values are the pixel values (a number from 0 to 255).


Here, we are using Keras (with TensorFlow as our backend) as the main package to create a simple neural network to predict digits from handwritten images, as accurately as we can. 
