# Glasses Detection Deep Learning

The goal of this project is to build a neural network model that uses image data to predict whether someone is wearing a glasses or not.

To start with,  the images have been preprocessed by resizing the images from 1024x1024 to 256x256 and converting the into arrays. 
Then, the baseline model has been chosen to be simple neural network with one hidden layer and the accuracy was 0.4715 for the training and 0.3648 for the validation.
Which means accuracy is too low and there is an overfit on the model and to overcome the problem more hidden layers has been added to
increase the accuracy and the number of epochs has been decreased to reduce the overfit.


![image](https://user-images.githubusercontent.com/90555117/144274078-d623ce04-9b5c-4f0d-9807-9187ebafb4e7.png)


The above figure shows the accuracy for both training and validation for each epoch. 
The blue line represents the training accuracy and the orange line represents the validation accuracy. From the figure it is clear that as the number of epochs increase
the training accuracy increase and the gap between training and validation accuracy increases as will.

The next steps, more neural network models will be tested such as convolutional neural network (CNN), 
convolutional neural network with a Transferred Base and, classification models will be examined as will.


