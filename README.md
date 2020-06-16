# PyTorch-Data
Understand the functioning of data loading and how important it is to successfully implement any deep learning model.


Pytorch includes data loaders for several datasets to help you get started. The torch.dataloader is the class used for loading datasets. The following is a list of the included torch datasets and a brief description:

MNIST

Handwritten digits 1–9. A subset of NIST dataset of handwritten characters. Contains a training set of 60,000 test images and a test set of 10,000.

Fashion- MNIST

A drop-in dataset for MNIST. Contains images of fashion items; for example, T-shirt, trousers, pullover.

EMNIST

Based on NIST handwritten characters, including letters and numbers and split for 47, 26, and 10 class classification problems.

COCO

Over 100,000 images classified into everyday objects; for example, person, backpack, and bicycle. Each image can have more than one class.

LSUN

Used for large-scale scene classification of images; for example, bedroom, bridge, church.

Imagenet-12

Large-scale visual recognition dataset containing 1.2 million images and 1,000 categories. Implemented with ImageFolder class, where each class is in a folder.

CIFAR

60,000 low-res (32 32) color images in 10 mutually exclusive classes; for example, airplane, truck, and car.

STL10

Similar to CIFAR but with higher resolution and larger number of unlabeled images.

SVHN

600,000 images of street numbers obtained from Google Street View. Used for recognition of digits in real-world settings.

PhotoTour

Learning Local Image descriptors. Consists of gray scale images composed of 126 patches accompanied with a descriptor text file. Used for pattern recognition.



