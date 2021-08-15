# CIFAR-10-classification-with-ConvNet-Architecture

In this notebook I am trying to create a CNN model for popular CIFAR-10 dataset with using keras api.

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.
The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.


<p align="center">
  <img src="https://user-images.githubusercontent.com/55941654/129481552-226c415d-67e6-4e48-a178-9c092ce7f818.png" />
</p>

## Results
I create a custom CNN network with the help of a Sequential model, and as an optimizer, I use the famous Adam's optimizer. I also normalize data to help the optimizer converge minimum.
The model trained on three epochs and got over 80% accuracy, and you may also train with more epochs ( e.g., 30) and get over 95% accuracy.
Loss and accuracy plots are shown below.

<p align="center">
  <dev> <img src="https://user-images.githubusercontent.com/55941654/129481753-a8623cb7-03bc-4753-8100-f97bf7cdef2d.png" /></dev>
  <dev> <img src="https://user-images.githubusercontent.com/55941654/129481762-7f5c92a5-4377-4b0d-a407-44897e33b282.png" /></dev>
</p>
## Model summary
This a summary of the model, which is created by model.summary
<p align="center">
  <img src="https://user-images.githubusercontent.com/55941654/129481937-ae025467-80c3-420d-90c1-7d533419bad6.png" />
</p>
## Error Display


