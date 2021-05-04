Building deep learning model to detect emotions from an audio dataset by converting them to spectrogram images.
When we are given an audio dataset, the usual approach would be to extrct the features from each audio, (like mfcc, mel stft) and train a neural network  with these features. 
Here, an attempt is made to convert these audio data to image data (spectrograms) and let the CNN take care of feature extraction and the neural network is trained based on these features.

About the dataset
-------------------
The dataset used here is Ravdees dataset, which is a collection of audio samples recorded by 24 different actors. Out of these, 12 are male voices and 12 female voices. 
These audio samples show different emotions such as happiness, anger, fearful etc.
70% of the dataset is set as the training data and 15% each for validation and test set.
