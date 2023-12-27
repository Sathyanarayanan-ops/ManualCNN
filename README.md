# ManualCNN

The objective of this project is to learn how a cnn works,by manualy implementing a few layers of cnn, we can see how to exactly build one 
First we use hardcoded functions in pytorch on CIFAR10 dataset and do a multiclass classification 
Then we tune hyperparameters in order to improve the accruacy of the predictions 

Going through the jupyer notebook will provide a better understanding as proper line by line documentation has been provided 

After which we manually design our own neural network 


# Loading CIFAR10 , basic pre-processing and running first neural networks # 

In this initial part of the project, we load the dataset from the web and run a pre processing procedure such as normalizing the pixels 
Then we train a simple neural network, use appropriate loss functions and gradient descent. 
We get an accuracy of 52% 


# Tuning hyperparameters # 
Basic hyperparameter tuning is done in order to improve the accuracy of the model from 52% to 72% 

Noticing carefully the comments, it can be seen that after careful debugging, a trial and error process was done to get the best results 


# Building manual neural network # 
A neural network works by passing filters and convolving them appropriately to extract information 
This is done manually in this code by using the scipy.signal.correlate2d which essentially convolves and gives the output 
This operation mimics the convolution process by summing the products of input and kernel values across spatial locations.

This concludes the filtering part of the process
Below is the before and after of the effect of this forward pass step 
![image](https://github.com/Sathyanarayanan-ops/ManualCNN/assets/57038667/f6c92693-0476-43aa-addd-2f4e3570db32)

![image](https://github.com/Sathyanarayanan-ops/ManualCNN/assets/57038667/ba086539-7ca6-4972-9b3f-96ce375a1826)


Next the back propagation is done where gradient is taken wrt to input image, kernel and bias 

<img width="988" alt="Screenshot 2023-12-26 at 9 53 28 PM" src="https://github.com/Sathyanarayanan-ops/ManualCNN/assets/57038667/7b0c4ec8-35ed-479e-8780-55a33843114c">





