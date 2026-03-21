# Music Genre Detection using Deep Learning (CNN)

##  Overview

This project focuses on classifying music into different genres using Deep Learning techniques. The model uses Convolutional Neural Networks (CNN) to analyze audio signals by converting them into spectrogram images and learning patterns from them.



## Features

*  Automatic music genre classification
*  Deep Learning model using CNN
*  Spectrogram-based audio representation
*  High accuracy compared to traditional ML methods



## Dataset

* **GTZAN Dataset**

  * 10 genres (Pop, Rock, Jazz, Classical, etc.)
  * 100 audio files per genre
  * Each audio clip is 30 seconds long


## Tech Stack

* Python
* Librosa (audio processing)
* NumPy & Pandas
* TensorFlow / Keras
* Matplotlib 


## Methodology

1. Load audio files
2. Convert audio → Mel Spectrogram
3. Normalize and preprocess data
4. Train CNN model on spectrogram images
5. Evaluate model performance
6. Predict genre for new audio files


## Model Architecture

* Convolutional Layers (feature extraction)
* Max Pooling Layers
* Fully Connected Layers
* Softmax output for genre classification


## Results

* Achieved accuracy of ~85–90% using CNN
* Better performance compared to traditional ML models


## How to Run

```bash
git clone https://github.com/AdarshBhoutekar/music-genre-classification
cd music-genre-classification
pip install -r requirements.txt
jupyter notebook Train_Music_Genre.ipynb
```


## Spectrogram Representation

Audio signals are converted into spectrograms which act as input for the CNN model.


## Future Improvements

*  Real-time genre detection
*  Web application integration
*  Mobile deployment using TensorFlow Lite

---

## Contribution

Feel free to fork this repository and contribute!

