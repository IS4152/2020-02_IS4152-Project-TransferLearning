# Introduction
<p style="text-align: justify; text-justify">Facial expressions recognition (FER) has many beneficial applications in the real world, ranging from education to healthcare and even the service industry. Therefore, there has been an increasing amount of research done to build powerful models that can accurately predict the emotion one is currently feeling. In this project, we aim to access different transfer learning methods to build a FER model that predicts one of the 7 basic emotions (neutral, anger, disgust, fear, happy, saddness and surprise). We pooled a total of 4 datasets (CK+, FER-2013, AffectNet and Aff-Wild2) and used it to train 5 different models (AlexNet, VGG, ResNet, VGGFace and VGGFace2) in 3 different ways (Fine-tuning the entire model, Freezing the Layer Weights and Progressive Transfer Learning)</p>

# Code description
Our codes are split into 2 main files, Data Preprocessing.ipynb and Model Pipelines.ipynb.<br/>
Data Preprocessing.ipynb cotains all our data cleaning and preparation steps, while Model Pipelines.ipynb contains our codes to run the experiments for the various models

# Demo
We also have a demo application, live_cam_best.py <br/>
This application is a live videostream which will read data from the facial features detecting by the camera, and predict the emotion expressed on the face in real time.
The demo application will require loads our best model to make the predictions, however we have not made this model available publically, as such the demo application will not work as intended.

# Absence of data
The various datasets have not been provided in this github repository for privacy and copyright reasons
