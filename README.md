Project Name : Detection of Stress using Machine Learning

Description:
The goal of this project is to develop a stress detection system using CNN. The stress level is calculated based on the facial expressions i.e.,eyebrow and lip movement. The displacement of eyebrow and lip coordinates are calculated and normalized through which the stress level and value are calculated, and furher a suggestion is provided.

Procedure:
This project has three major parts:
1. Training the dataset using CNN.
2. Testing the model using live stream.
3. Deploying the model using Flask API
For each input image four steps are involved:
Image Pre-processing, Eyebrow Detection, Lips Detection, Stress Detection

Dataset:
kaggle FER2013 dataset - It contains the grayscale images of seven different emotions. The dataset has 35,887 images. The emotions are Happy, Angry, Sad, Disgust, Surprise, Fear and Neutral. 

TechStack:
imutils
keras 
opencv
flask
dlib

Team Members:
M. Aradya - 19WH1A0525
D. Geetika - 19WH1A0530
Nazmeen Begum - 19WH1A0541
