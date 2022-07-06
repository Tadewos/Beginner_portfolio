# ML Beginner Projects

### Project 1: CIFAR

This is an introductory computer vision project using the CIFAR-10 image dataset that is built into Tensorflow. It contains 60,000 32x32 pixel images equally divided into 10 classes. Conv2D and MaxPooling2D layers are used to extract features from images. Dense layers are added on top of the convolutional base. Model has less than 70% accuracy. It can be improved through Data Augmentation or implementing pre-trained models.

### Project 2: MNIST

This project is one of the most common introductory machine learning projects that uses the MNIST Fashion Dataset included in keras (Tensorflow). The dataset includes 60,000 images for training and 10,000 images for validation/testing. The objective is to build a neural network model that trains from labeled images (under 10 categories including dress, shirt, ..etc) and can later categorize images from test data. Test data are also labeled making it simple to evaluate if the model performs well. Three layers were applied in this NN.
* Input Layer - uses flatten layer to convert 28x28 pixel data into 784 neurons
* Hidden Layer - uses dense layer along with Relu activation
* Output Layer - uses dense layer with 10 neurons for the 10 categories of clothing

### Project 3: FeedForward Neural Network

This is a simple diabetes detection model using a feedforward (dense) neural network There's no real correlation between given data and outcome (diabetes test) as shown in histogram (in ipynb file); hence, it'll be useful to implement a machine learning model that can draw a relationship for us.

