# Dog Images Classifier using a pre-trained CNN model

Exercise from the [Udacity's AI Programming with Python Nanodegree program](https://eu.udacity.com/course/ai-programming-python-nanodegree--nd089).

Classifies pet images using a pre-trained CNN model, compares these classifications to the true identity of the pets in the images, and summarizes how well the CNN performed on the image classification task.
The true identity of the pet (or object) in the image is indicated by the filename of the image. Therefore, the program extract first the pet image label from the filename before classifying the images using the pre-trained CNN model. With this program you can compare the performance of 3 different CNN model (vgg, alexnet, resnet) architectures to determine which provides the 'best' classification.

## Usage
The following instructions assume that you:
1. Have git installed on your machine. If not, you can click [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) to set it up.
2. Have a package manager installed. The following instructions use [conda](https://docs.conda.io/en/latest/) but [pip](https://pypi.org/project/pip/) works just as well.


First, clone the repository with git:

`git clone https://github.com/ge0ra/ExerciseDogImageClassifier.git`

Then, open your terminal and change the current working directory into the repository

`cd ../ExerciseDogImageClassifier`

Install the following packages:
1. Python 3.7: `conda install python==3.7`
2. Pytorch 1.1: `conda install pytorch=1.1`
3. Torchvision 0.3: `conda install torchvision=0.3`


## How to use

`python check_images.py`

Here is a list of all of the arguments you can use along with some examples:

1. --dir:
- The relative path to the image folder containing the images.
2. --arch:
- The architecture you would like to use for the training. This can either be 'resnet', 'alexnet' or 'vgg'
3. --dogfile:
- The file containing the names of all the recognized dogs



## Licence
[MIT](https://opensource.org/licenses/MIT)
