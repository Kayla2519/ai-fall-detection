AI Fall Detection Using Audio Classification

Overview

This project explores how machine learning can identify potential falls by classifying audio recordings as either fall or non-fall events. The goal is to investigate a possible approach for smart-home systems that could detect falls and trigger an alert.

For example, the model aims to distinguish a potential fall from other loud sounds, such as a door slamming.

Technologies Used

Python

Google Colab

Machine Learning

MFCC (Mel-Frequency Cepstral Coefficient) audio features

Logistic Regression

Ridge Classifier

Node-RED for a simple alert demonstration

Dataset

The dataset contained 950 WAV audio files, split evenly between 475 fall recordings and 475 non-fall recordings. The audio was sampled at 48 kHz.

Results

The models were evaluated using the F1 score.

Experiment

Model

F1 Score

Clean audio

Logistic Regression

0.968

Noisy audio

Ridge Classifier

0.942

The results demonstrate promising classification performance in these experiments. They do not establish real-world fall detection accuracy or guarantee reliable performance in a home environment.

Prototype

A simple Node-RED prototype used buttons and text-to-speech (TTS) to demonstrate how an alert could be triggered.

Notebooks

Clean Audio Experiment

Noisy Audio Experiment

Future Improvements

Test with more diverse real-world audio.

Evaluate false positives and false negatives.

Explore additional models and audio augmentation techniques.

Investigate integration with a smart-home alert system.
