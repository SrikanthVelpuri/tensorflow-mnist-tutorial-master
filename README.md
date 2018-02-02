# tensorflow-mnist-tutorial-master
    The graphs shown in images are
    Accuracy - Trainig acuracy and testing accuracy is represented against no. of sample images.
    Cross entropy loss - cross entropy losses are represented during the training and testing processes.
    Weights,Biases and their variation are also shown in two different graphs during the training proccess.
    In Test digits graph the red coloured part represents the images which are not recognised properly.

These are steps used for improving the accuracy on MNIST Data.

##### 1.MNIST using Simple Softmax layer (Test Accuracy - 0.92) ![mnist_1 0_softmax](https://user-images.githubusercontent.com/19996897/35729711-9b17ef4a-0835-11e8-894f-f82848cb8153.png)

##### 2.MNIST using five layers of sigmoid (Test accuracy - 0.9746)![mnist_2 0_five_layers_sigmoid](https://user-images.githubusercontent.com/19996897/35729726-aac9b2c0-0835-11e8-95a9-85620b035758.png)

##### 3.MNIST using five layers of RELU and using learning rate decay (Test Accuracy -0.978)![mnist_using_layers_relu_lrdecay_dropout](https://user-images.githubusercontent.com/19996897/35729848-fd5db680-0835-11e8-8f5a-4689d53f627c.png)

##### 4.MNIST using five layyers of RELU ,learning rate decay and dropout technique (Test Accuracy-0.985)![mnist_using__five_layers_relu_lrdecay](https://user-images.githubusercontent.com/19996897/35729796-dadf5802-0835-11e8-9935-77a692f8f271.png)

##### 5.MNIST using Convolutional Layers and Dropout technique (Testing Accuracy - 0.992)![mnist_using_convolutional_bigger_dropout](https://user-images.githubusercontent.com/19996897/35729823-f0c2bbf0-0835-11e8-87ee-84890681e0ee.png)

##### 6.MNIST using Convolutional Layers and batch Normalization technique (Testing Accuracy - 0.995)![mnist_using_batchnorm_convolutional](https://user-images.githubusercontent.com/19996897/35729803-e449e740-0835-11e8-976b-11f3193205a8.png)

This is done with the help of Martin Gorner tutorial.For codes please refer the directory.
