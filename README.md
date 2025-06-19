# Air-Signature-Using-Smartwatch-Motion-Sensors

## Project Overview

This project introduces a biometric authentication system that identifies handwritten signatures performed in the air using smartwatch motion sensors. The system collects motion data, such as acceleration and rotation, from a smartwatch to recognize unique signature patterns without requiring any physical surface.

## Objective

The goal of this project is to build a portable and contactless authentication system that can accurately differentiate between genuine and forged signatures using smartwatch sensor data.

## Models Used

Several deep learning models were trained and evaluated using the collected dataset:
- BLSTM (Bidirectional Long Short-Term Memory)
- CNN (Convolutional Neural Network)
- Hybrid CNN-BLSTM
- ResNet

The CNN model achieved the best performance with an accuracy of 99.86%.

## Dataset

- Data collected from 24 participants using Apple Watch SE (44mm)
- Each participant provided 7 genuine and 7 forged signatures
- Data recorded in CSV files containing accelerometer, rotation, and device attitude information
- Each file was labeled as genuine or forged and used to form signature pairs

## Preprocessing

Before training, the raw data was processed using several techniques:
- Rotation correction
- Signal differentiation
- Normalization
- Pairing (genuine-genuine and genuine-forged)

## Experiments

Four experiments were conducted to test the models and compare their performance. The evaluation focused on accuracy, resistance to forgery, and real-time usability.

## Contributions

- Developed a custom Arabic-language air signature dataset
- Proposed a contactless, real-time authentication system using smartwatches
- Compared multiple deep learning models for effectiveness and robustness
- Focused on Arabic signatures, which are rarely studied in this field

## Tools and Technologies

- Python
- TensorFlow and Keras
- NumPy and Matplotlib
- Apple Watch SE
- CSV data format

## Applications

The system can be used in:
- Banking and financial services
- Healthcare systems
- Digital identity verification
- Secure login for mobile and wearable devices

## Authors
- Lama Faham AlOtibie
- Maymona Turki Alotaibi  
- Atheer Abdullah AlAsiri  
- Rimas Saad AlBahli  
  

Supervised by Dr. Rasha Mohammad AlEidan  
King Saud University – College of Computer and Information Sciences
