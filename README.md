# Inception-Google-Net_Image_Classification

![image](https://user-images.githubusercontent.com/101316217/211372103-c4bafc56-ca7b-4e74-a7e5-1bc2995c7634.png)

# Introduction 

we will be building Inception or GoogleNet. We are building this CNN from scratch in PyTorch, and will also see how it performs on a real-world dataset.

We will start by exploring the architecture of Inception. We will then load and analyze our dataset, CIFAR-10, using the provided class from torchvision. Using PyTorch, we will build our Inception from scratch and train it on our data. Finally, we will see how the model performs on the unseen test data.


![image](https://user-images.githubusercontent.com/101316217/211371905-ea108076-6d6c-4051-97cd-ebd072081d39.png)



![image](https://user-images.githubusercontent.com/101316217/211372251-36356085-99d1-42da-9121-d00f6b5a814a.png)



# Dataset 

we will be using the famous CIFAR-10 dataset, which has become one of the the most common choice for beginner computer vision datasets. The dataset is a labeled subset of the 80 million tiny images dataset. They were collected by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton. The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class. The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, and things of that sort. "Truck" includes only big trucks. Neither includes pickup trucks.

Here are the classes in the dataset, as well as 10 random images from each:

![image](https://user-images.githubusercontent.com/101316217/211432959-d7837b6e-72be-446a-b04b-2d3a76869bc6.png)



# Tools

PyTorch

Colab

# Future Work

You can try using different datasets.

You can experiment with different hyperparameters and see the best combination of them for the model.
