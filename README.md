# Trigger Word Detection 

## Abstract

This project is about applying deep learning in speech recognition. Trigger word detection(also known as keyword detection, or wakeword detection) is the technology working behind for the devices like Amazon Alexa.

## Introduction

In this project, we will generate training data based on three types of audio clips, one is positive cases(audio clips that contain trigger word), another one is negative cases, and the last one is the audio clips containing background voice. Then we will use the python package called `pydub` to insert some positive and negative audio clips into background audio clips without overlapping with each other.

The below image is the model architecture.

![](images/model.png)