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
Use Flask to deploy

