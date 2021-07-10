# Sign-Language-to-Text-Conversion
Deep Learning Assignment for conversion of American Sign Language to Text format

# Documentation Folder
1) Research Papers I follow to Complete Project
2) Project Stage 1 & Stage 2 Report 
3) Project Stage 1 & Stage 2 Presentation

# Source Code Folder 
1) Model Folder Contains the Json and h5 files of trained CNN model
2) Pics folder Contains Sign Language of All Character
3) 5 Files to Execute the Project

# Importance of Each file
1) Collect-data.py file: I was not able to find the correct dataset. Then I decided to create my own dataset. Using this file Own Dataset for each Character will be created
2) Image_processing.py & preprocessing.py files: To improve the accuracy of the project I converted the RGB Images to Black & white Image. After Conversion I applied Gaussian Blur Filter which focuses on Boundry of the Sign Language. 
3) train.py file: File contains the code of model training 
4) app.py File: Contains the code of Front End which is created using TKinter. 

# Steps to Execute: 
1) I have uploaded dataset. Execute Collect data file first and Create your own Dataset for each character. 
2) Execute Image processing and Preprocessing files. So the Black & White Images of your dataset will be created.
3) Execute train.py file so json & h5 files for your dataset will be created 
4) Execute the App.py file so the frontend will be loaded & conversion of each sign language will be displayed 

# How frontend Works 
1) Once the Frontend is loaded. 
2) Show the Sign language of character you wanted to translate
3) For the 50 frames predicted text conversion will be stored in backend and most predicted character will be displayed in front of character. 
4) When all the characters will be predicted don't show any sign language in screen. When Model finds blank screen it predicts word is completed. 
5) After Predicting all characters it will be shifted in front of word and if blank screen continues it will be shifted in front of sentence.

# Images of Project
Image 1) Login Page

![](images/Frontend.png)
