# ImageCLEF-Medical-Caption-Task-2019
ImageCLEF Medical Caption Task 2019 with Scikit-learn &amp; Tensorflow

This repository will serve as a place where the project from the course **Applied Machine Learning** will be uploaded. The course is part of the curriculum of the Department of Management Science and Technology from the Athens University of Economics and Business and the project is assigned by [Panos Louridas](https://github.com/louridas).

## Dataset

The [Image CLEF 2019 Concept Detection Task](https://www.imageclef.org/2019/medical/caption/) is a large-scale multi-label classification task aiming to identify medical terms (concepts) in radiology images. Implement a system to classify a medical image based on several abnormalities represented by [Unified Medical Language System (UMLS)](https://www.nlm.nih.gov/research/umls/index.html) concept IDs.

The training data exists in Google Drive.

You can download the training and validation data from https://drive.google.com/uc?id=1UOccw0VNCiRTwaQSEJMhiYWXhizvKptX and the test data from https://drive.google.com/uc?id=1diO2apPPFJeTH8CGcd3S55OUNTXtJVu2. Alternatively, you can use the gdown utility; the file IDs are 1UOccw0VNCiRTwaQSEJMhiYWXhizvKptX and 1diO2apPPFJeTH8CGcd3S55OUNTXtJVu2.

The data are organised as follows:

* training-set: 56,629 training images.
* validation-set: 14,157 validation images.
* test-set: 10,000 images used for testing. The test images have no annotations. They will be used for assessment.
* train_concepts.csv: the image IDs of the training set with their gold (i.e., known correct) tags, separated with ;.
* val_concepts.csv: the validation image IDs with their gold tags, separated with ;.
* string_concepts.csv: all the available tag IDs and their corresponding name, separated with tabs.

## Assignment

The Assignment Instructions can be found [here](https://github.com/kbabetas/ImageCLEF-Medical-Caption-Task-2019/blob/master/Assignment%20Instructions/imageclef.ipynb).

The aim of the project is to Build a Neural Network to classify a medical image based on the UMLS Concept IDs.

## Project

The project can be found [here](https://github.com/kbabetas/Clustering-and-Classification-of-MEPs-Tweets/blob/master/Babetas_Konstantinos_8160078_3rd_Assignment.ipynb).

## Tools

* Pandas Library
* Scikit-Learn
* Python
* Jupyter notebook

## Authors

* [Konstantinos Babetas](https://www.linkedin.com/in/kbabetas/) - Student at the Department of Management Science & Technology at the Athens University of Economics and Business
