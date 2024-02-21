# CSE-404-Project

## Overview

This Git repository serves as a comprehensive starter kit for facial recognition projects. Whether you are just starting with facial recognition or looking for pretrained models to enhance your existing projects, this repository has you covered.

## Contents

### 1. Beginning Code for Facial Recognition

This folder contains the foundational code to kickstart your facial recognition project.

initial_train+test_ideas.ipynb- unrefined facial recognition code very rough draft. Need to work on refining. It has a basic layout which shows how to train an test image data within it. Will use this to build a more refined model. 

### 2. Pretrained Facial Recognition Models

In this folder, you'll find pretrained facial recognition models ready for testing. These models are trained on the Well Known Faces dataset in various ways, providing a solid foundation for accurate and efficient facial recognition in your applications. Most of these models are pretty well trained but are not good enough to reach the high areas of accuracy, specifically 85% up for facial recongition on images outside the dataset. 

### 3. Validation Face Images

Contains images of the classes (people) within the Facial Recognition but these images are not within the dataset itself. These are outside validation images to test the model on different image styles/quality and test each models respective robustness. We can modify these images when testing if the models we have are more accurate on certain factors. For example, for a model that is trained on all the images converted to blues it would be crucial to modify the validation image to blue before using the model to predict the class on that image.
