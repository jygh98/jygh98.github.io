---
layout: project
type: project
image: images/tf.png
title: Activity Recognizer
permalink: projects/har
# All dates must be YYYY-MM-DD format!
date: 2018-07-01
labels:
  - Python
  - TensorFlow
  - Deep Learning
  - Sensors
summary: Convolution Neural Network (CNN) to predict human activity using smartphone sensor data.
---

The goal of the project was to build a recognition system using deep learning that would be able to identify a predetermined set of gestures (shaking, circle, up-down, down-up) an individual is doing.  The motivation of this project was to explore the use of interaction technologies and how a recognition system is employed to model human activity to interact with an application.  A smartphone is used as the input device due to its build-in accelerometer and gyroscope sensors.  This project was done as part of my exchange program at Tokyo University of Agriculture and Technology in Summer 2018 over the course of 6 weeks.  During my stay, I had the opportunity to have Professor Tanaka as my advisor and worked closely with one of his student on this project.

<img class="ui image" src="../images/har.png">

## Responsibilities
For this project, I was responsible for building the labeled dataset that would be used to train the classifier for the recognition system.  Despite the vast amounts of [public datasets repositories for machine learning](https://github.com/awesomedata/awesome-public-datasets), we were not able to find a dataset that met our specification and decided to build a simple labeled dataset.  This was done by developing an Android data logger application to record the build-in accelerometer and gyroscope readings and be able to label recorded data by specifying a particular gesture on-screen.  Additionally, I worked on processing techniques that would reduce noise from real-time accelerometer and gyroscope data of the smartphone.  This was done through implementing a low-pass filter that was able to stabilized the input signal.  Finally to actually create the dataset, I had to coordinate with other lab members to record their gestures using the developed data logger application.

## Learning Outcome
In this project, I gained experience using Android Studio for android development and had the opportunity to work with TensorFlow to implement and train a CNN model.  By implementing this app, I learned how to work with the android interface by experimenting with widgets provided by Android studio. In addition to learning about library integration with Android Studio, I was able to learn about the activity lifecycle, Sensor manager, and basic Android features.

Source: <a href="https://github.com/ttlabtuat/sdl" target="_blank"><i class="large github icon"></i>https://github.com/ttlabtuat/sdl</a> 
