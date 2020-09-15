###  HCMV Capsid Detection using Tensorflow

Detection of HCMV capsid envelopment stages using Faster R-CNN
Feature Extractor: ResNet101

### Requirements

Python 3.5 or above
Tensorflow 1.14.0 and above
Install all the required dependencies stated in the requirements.txt file
Best to run on a GPU 

### Dataset

Please use your own Electron Microscopy image dataset.
Images used in this project will be provided upon request.
For image request, please contact: kavitha.shaga-devan@uni-ulm.de


## Usage

1) Fork and clone this repository.

2) Generate synthetic images
- Change the current working directory into the SinGAN folder
- Install all the required dependencies stated in the requirements.txt file in the SinGAN folder
- To train SinGAN model on your own image, put the desire training image under Input/Images, and run

'python main_train.py --input_name <input_file_name>'

- Please refer to https://github.com/tamarott/SinGAN for more information on the generation of synthetic images

3) Add your custom images
- Ensure that your current working directory is the main repository
- Your custom images should ideally  have `jpg` extensions
- Annotate your images using any annotation tool that generate xml files
- Train/test split the image files into two directories, `./data/images/train` and `./data/images/test` according to the desired train/test split ratio
- Store the corresponding `xml` files inside `./data/images/train` and `./data/images/test` folders
- Commit and push your annotated images and xml files (`./data/images/train` and `./data/images/test`) to your forked repository

4) Run Colab file
- Open 'tensorflow_object_detection_training_colab.ipynb' notebook in colab
- Replace the repository's url to yours and run it
- You can also opt to run this file locally in Jupyter notebook


The synthetic image generator in this repository has been obtained from https://github.com/tamarott/SinGAN.

