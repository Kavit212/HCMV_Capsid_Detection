###  HCMV Capsid Detection using Tensorflow

Detection of HCMV capsid envelopment stages using Faster R-CNN
Feature Extractor: ResNet101

### Requirements

Python 3.5 or above
Tensorflow 1.14.0 and above
Install all the required dependencies stated in the requirements.txt file
Best to run on a GPU 

### Dataset

Please use your own TEM image dataset



## Usage

1) Fork and clone this repository.

2) Add your custom images
- Your custom images should ideally with have `jpg` extensions.

- Train/test split those files into two directories, `./data/images/train` and `./data/images/test`

- Store `xml` files inside `./data/images/train` and `./data/images/test` folders. 

- Commit and push your annotated images and xml files (`./data/images/train` and `./data/images/test`) to your forked repository.

3) Run Colab file
- Open 'tensorflow_object_detection_training_colab.ipynb' notebook in colab
- Replace the repository's url to yours and run it.
- Yu can also opt to run this file locally in Jupyter notebook.


