# HCMV Capsid Detection using Tensorflow



## How to Run

Require [Python 3.5+](https://www.python.org/ftp/python/3.6.4/python-3.6.4.exe) installed.
Fork and clone this repository to your local machine.


### Install required libraries
Install all the required dependencies stated in the requirements.txt file


### Step 1: Add your custom images
- Your custom images should ideally with have `jpg` extensions.

- Train/test split those files into two directories, `./data/images/train` and `./data/images/test`

- Store `xml` files inside `./data/images/train` and `./data/images/test` folders. 

- Commit and push your annotated images and xml files (`./data/images/train` and `./data/images/test`) to your forked repository.

### Step 2: Run Colab file
- Open 'tensorflow_object_detection_training_colab.ipynb' notebook in colab
- Replace the repository's url to yours and run it.
- Yu can also opt to run this file locally in Jupyter notebook.


