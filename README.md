# Urban-Sound-Classification-Project
It is an Audio Classification project that creates a Neural network-based model to classify various sounds using their unique spectrogram into classes such as Dog Barking, Sirens, Street Music, etc.

## Description

* The UrbanSound8k dataset contains 8732 labeled sound excerpts (<=4s) of urban sounds from 10 classes: air_conditioner, car_horn, children_playing, dog_bark, drilling, enginge_idling, gun_shot, jackhammer, siren, and street_music. The classes are drawn from the urban sound taxonomy.

* 8732 audio files of urban sounds (see description above) in WAV format. The sampling rate, bit depth, and number of channels are the same as those of the original file uploaded to Freesound (and hence may vary from file to file).
The UrbanSound8k dataset used for model training, can be downloaded from the following link: https://urbansounddataset.weebly.com/

### Librosa
Librosa is a python package for music and audio analysis. It provides the building blocks necessary to create music information retrieval systems. It is used for data preprocessing and feature extraction.Features used:
##### MFCC

* The Mel-Frequency Cepstral Coefficients(MFCC) summarises the frequency distribution across the window size, so it is possible to analyse
both the frequency and time characteristics of the sound. These audio representations will allow
us to identify features for classification. It will try to convert the audio into some kind of features based on the frequency and time characteristics which will   help us to do the classification.

* MFCC does nothing but extracting patterns based on the frequency and time characterstics. This will uniquely able to identify that particular audio signal like in which class it actually belongs to because this audio signal will be later used in  deep learning Techniques.


### Technology Used

* Artificial Neural Networks
* Librosa
* Scipy
* Mel-Frequency Cepstral Coefficients(MFCC)
* TensorFlow
* keras
* NumPy
* pandas


