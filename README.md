# Cifar-10-CNN
CNN model using 3 VGG layers trained on the Cifar-10 data set.

<h3>The CIFAR-10 dataset</h3>
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.<br>
<h3>CNN model</h3>
Using 3 layers of the VGG CNN model along with dropout layers, we have trained the CNN on the Cifar-10 dataset.<br>
We observed that batch normalization improves the performance from 82 to 83.83%.
The model finally achieved a test accuracy of 83.83%.
