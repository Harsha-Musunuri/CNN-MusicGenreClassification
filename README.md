# CNN-MusicGenreClassification
CNN implementation of Music Genre Classification using GTZAN music genre collection dataset
# Datasets:
https://drive.google.com/open?id=1pK1EENnsPcDpkhIHCD_XH9ep4DeisEiH

# Implementation:
1. use Librosa package to extract the features -> Mel-frequency cepstral coefficients (MFCC)(20 in number), Spectral Centroid, Zero Crossing Rate, Chroma Frequencies, Spectral Roll-off.
conda install -c conda-forge librosa - to Install
2. After Feature extractio and Preprocessing - Train a CNN using TF,Keras

# Evaluation
Compare Actual genres vs Predicted genres via Confusion matrix, RMSE, MAE, etc.

# Web App
Tensoflow Js: use to deploy the model

# To Run the WebApp
1. Install Web Server for Chrome plugin
2. Open Web Server and choose the code folder
3. You get to see a localhost, launch the site
4. Backend is tensorflow.js that provides random tensor to the trained model, which is used to predict the genre!

