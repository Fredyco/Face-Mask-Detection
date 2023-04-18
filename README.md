# Face Mask Detection

This repository contains a machine learning project for detecting whether a person is wearing a face mask or not, with an accuracy of 96%. The model can be used in various settings to help enforce public health guidelines and reduce the spread of COVID-19.

## Table of Contents
- [Project Overview](#project-overview)
- [Tools and Technologies](#tools-and-technologies)
- [File Descriptions](#file-descriptions)
- [Results](#results)
- [Model Deployment](#model-deployment)
- [Model Inference](#model-inference)
- [Acknowledgements](#acknowledgements)

## Project Overview
The Face Mask Detection project uses deep learning techniques to detect whether a person is wearing a face mask or not. By analyzing images of people, the model can identify whether the person is wearing a mask and output a prediction. The project involves data cleaning and preprocessing, model training and evaluation, and the creation of a predictive model.

## Tools and Technologies
- Python
- Jupyter Notebook
- TensorFlow
- Keras
- OpenCV
- Streamlit

## File Descriptions
- `model/`: Folder containing the trained model weights and architecture
- `model_deployment/`: Folder containing the code for deploying the trained model in a web application using Streamlit
- `model_inference/`: Folder containing code for testing the trained model and performing inference on new images
- `Test_folder/`: Folder containing test images for model inference
- `facemask_project`: Jupyter Notebook containing the code used for data cleaning, model training, and evaluation
- `url_dataset.txt`: Text file containing the URL for the dataset used in this project

## Results
The Face Mask Detection project was able to successfully detect whether a person is wearing a face mask or not, with an accuracy of 96%. The project identified the most important features that contribute to face mask detection and created a predictive model that can be used to assess whether a person is wearing a face mask or not. These insights can be used to help enforce public health guidelines and reduce the spread of COVID-19.

## Model Deployment
The `model_deployment/` folder contains the code required for deploying the trained model in a web application using Streamlit. The deployment code includes instructions for setting up the necessary infrastructure and integrating the model with a web application.

## Model Inference
The `model_inference/` folder contains code for testing the deployed model and verifying that it is working as expected. The `Test_folder/` folder contains test images for model inference.

## Acknowledgements
Special thanks to the creators of the dataset used in this project, and to the TensorFlow and Keras libraries for providing the foundational tools required to build this project.