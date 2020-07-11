# Image-CLEF-Medical-Caption-2019
In terms of the course **Applied Machine Learning** under the supervision of [Panos Louridas](https://github.com/louridas), this repository contains a large-scale multi-label classification task aiming to identify medical terms (concepts) in radiology images.

## Classification

The assignment consists of **1 main Section**, which is explicitly stated in the [Assignment Description](https://github.com/nickosfra/Data-Analysis-on-Members-of-the-European-Parliament-Tweets/blob/master/twitter_meps.ipynb). Briefly, the project focuses on:
- building a neural network that learns from the individual components/characteristics from which captions are composed
- classifying the images of a dataset - containing random radiology images - to a concept

The classification task can be found [here](https://github.com/nickosfra/Image-CLEF-Medical-Caption-2019/blob/master/ImageCLEF_Medical_Caption_2019-Classification.ipynb).

## Dataset

The training data exist in Google Drive. You can download the training and validation data from https://drive.google.com/uc?id=1UOccw0VNCiRTwaQSEJMhiYWXhizvKptX and the test data from https://drive.google.com/uc?id=1diO2apPPFJeTH8CGcd3S55OUNTXtJVu2.

- The data are organized as follows:
  - `training-set`: 56,629 training images.
  - `validation-set`: 14,157 validation images.
  - `Last`; rename it to test-set: 10,000 images used for testing. The test images have no annotations. They will be used for assessment.
  - `train_concepts.csv`: the image IDs of the training set with their gold (i.e., known correct) tags, separated with `;`.
  - `val_concepts.csv`: the validation image IDs with their gold tags, separated with `;`.
  - `string_concepts.csv`: all the available tag IDs and their corresponding name, separated with tabs.


## Tools
- Jupyter Notebook
- Python
- Tensor-Flow & Keras
- Pandas Library
- NumPy
- MatPlotLib
- Scikit-learn

## Author
[Nikolaos Fragkomanolis](https://github.com/nickosfra) - Undergraduate student at the Department of Management Science and Technology (Athens University of Economics and Business)
