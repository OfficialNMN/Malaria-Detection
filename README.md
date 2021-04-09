# Malaria-Detection using VGG-19

This Web Application is made using Convolutional Neural Networks and Transfer Learning Techniques (VGG19) to predict whether the blood sample taken from the patient is infected or not. The trained model takes image of cell extracted from blood sample using medical techniques as an input from the flask server which gets converted into an array of pixels to recognise malaria parasite from human blood sample.

### Model created is saved in a malaria_vgg.h5 file for further use.

#### TransferLearning.ipynb
This ipynb file has the whole tensorflow and kers code where the images are preprocessed, model is created, trained, compiled and then saved.

#### WebApplication is to be created using Flask server as backend and HTML/CSS on frontend
1. templates/ ----> base.html, index.html
2. static/    ----> style.css, main.js

#### Requirements.txt
requirements.txt file contains all the libraries/modules to be installed for running this project on cloud/local system.

#### App.py
This python file contains the flask app written which contains routes for runnning it on web and also containing keras preproceesing where the image uploaded is first converted to an array of pixels which is then given to the loaded model.

#### Procfile
This tells browser what file to execute while running the app.
