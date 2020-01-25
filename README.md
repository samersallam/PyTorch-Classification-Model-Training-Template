# PyTorch-Classification-Model-Training-Template

![image](https://cdn-images-1.medium.com/max/1000/1*aqNgmfyBIStLrf9k7d9cng.jpeg)

This code is to help you train and evaluate PyTorch classification model easily and quickly

- In order to run this code you need a GPU. If you do not have one, refer to https://colab.research.google.com/

- The main target of this template is to help during building your classification model where:
1.	It helps load the dataset whether the dataset in one directory or multiple directories
2.	It shows the dataset details once the dataset directory has been specified 
3.	It helps know the available GPU devices and pick one to use easily 
4.	It helps get a pre-trained model for you with the last layer updated with or without a dropout layer and initialized  by an algorithm you choose from the most common initialization algorithms
5.	It helps know the GPU memory usage of your model
6.	It helps understand the timing of different steps during model training
7.	It helps find the best learning rate using the new algorithm published by Leslie N. Smith in the paper Cyclical Learning Rates for Training Neural Networks. The original code from https://github.com/davidtvs/pytorch-lr-finder
8.	It provides a dashboard to monitor your model during the training process
9.	It helps track the metric that you choose to find the best model for your problem
10.	It provides a compressed version of your model to be used for deployment purpose

- In order to use the code do the following steps (refer to the main.ipynb to see some code snippet about how to use this template):
1.	Download the code
2.	Create a directory (or multiple directories if you have more than one dataset)and put your dataset inside each directory using the following structure:
-	Class 1 (directory)
-	Class 2 (directory)
-	Class N (directory)
3.	Update the dataset_dir variable by a string (directory name) if you have only one dataset, and by a list of strings if you have more than one dataset

