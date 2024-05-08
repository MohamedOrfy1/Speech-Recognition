# Speech-Recognition
Recognize the number from 0 to 9 using CNN 
## Overview

The project involves the following steps:

1. **Data Preprocessing**: Audio files are converted to Mel-frequency cepstral coefficients (MFCCs), which are then transformed into log-mel spectrograms for feature extraction.

2. **Model Building**: A CNN model is constructed using TensorFlow and Keras to classify the log-mel spectrograms into the corresponding digit classes.

3. **Model Training**: The model is trained on the preprocessed data with early stopping and learning rate reduction callbacks to prevent overfitting and improve convergence.

4. **Evaluation**: The trained model is evaluated on a separate test set to measure its performance in terms of accuracy and loss.

## Prerequisites

Before running the code, ensure you have the following dependencies installed:

- Python 3.x
- TensorFlow
- Keras
- Librosa
- NumPy
- tqdm
- Matplotlib
- scikit-learn
