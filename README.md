# Voice Emotion Recognition Using Hybrid Deep Learning

#### This project implements a hybrid deep learning model capable of recognizing emotions in human speech by analyzing acoustic characteristics of audio signals. Manual classification of emotions in voice recordings is time-consuming, inconsistent, and lacks scalability. Our system automates this process by detecting emotions such as anger, happiness, sadness, fear, disgust, and neutral through audio analysis.

The emotion classifier uses a hybrid neural network architecture combining:

#####Convolutional Neural Networks (CNNs): Capture local spectral patterns from features like MFCCs.

#####Bidirectional Long Short-Term Memory (BiLSTM) networks: Learn temporal dependencies across time to understand long-term emotional dynamics.

This combination allows the model to interpret both short-term spectral changes and long-term emotion patterns in speech. The model is trained on a training set and evaluated on a testing set using standard metrics such as accuracy, precision, recall, and F1-score.

##Dataset

We use the CREMA-D (Crowd-Sourced Emotional Multimodal Actors Dataset) for training and evaluation. CREMA-D is widely recognized for speech-based emotion recognition and provides diverse, high-quality audio samples.

###Key Features of CREMA-D:

Emotion Diversity: Six emotional expressions — Angry, Disgust, Fear, Happy, Neutral, Sad.

Audio Samples: 7,442 audio clips performed by 91 actors (48 male, 43 female), covering 12 standardized sentences in different emotional tones and intensities.

Speaker Variation: Voices from actors of varying age, gender, and ethnicity, aiding model generalization.

Intensity Levels: Low and High intensity for each emotion, capturing subtle variations in expression.

Format and Quality: WAV files sampled at 16 kHz for consistent clarity.
