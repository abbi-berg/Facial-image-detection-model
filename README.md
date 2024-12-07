# Facial-image-detection-model

This code was submitted as my final project in MIT Data Science Certificate Program

## Project Summary
In this project, I developed 11 CNN models and leveraged transfer learning techniques with models such as VGG16, ResNet V2, and EfficientNet to detect 4 emotion categories in black and white images. I leveraged optimization techniques such as Barch Normalization, Dropout, and the Adam optimizer, alongside data preprocessing and feature engineering to achieve an impressive 75.79% accuracy.

## Context:
Deep learning enables the analysis of unstructured data, including image data for emotion detection. Emotion AI focuses on developing systems that can understand and respond to human emotions by analyzing facial expressions and other cues. Accurate facial emotion recognition systems could enable mental health diagnostics, improve customer service platforms, and help businesses make decisions based on customers’ perceptions of products in stores or restaurants.

## Objectives:
The objective of this project is to leverage deep learning and artificial intelligence techniques to develop a computer vision model capable of accurately detecting facial emotions. The model will perform multi-class classification on images of facial expressions, categorizing them according to the associated emotions.

## Key questions:
- What preprocessing steps are necessary to ensure the quality and consistency of the images?
- Which deep learning architectures are best suited for facial emotion recognition?
- How will the model be trained and validated?
- Can we leverage pretrained model to improve the model performance?
- Should we perform data augmentation and what effect will this have on the model performance?
- How will overfitting be prevented during training?
- How can we deploy this model for real-world application?
- What will be the limitations of the model?
- How will privacy and ethical concerns be addressed when using facial emotion recognition technology?

## Problem:
Are we able to detect emotion accurately in facial images?
The problem is that human emotion is complex and multifaceted. People have different ways of showing emotion. Can we find the generalize patterns to detect emotion across many people?

## Dataset
The data set consists of 3 folders, i.e., 'test', 'train', and 'validation'. Each of these folders has four subfolders:

‘happy’: Images of people who have happy facial expressions.
‘sad’: Images of people with sad or upset facial expressions.
‘surprise’: Images of people who have shocked or surprised facial expressions.
‘neutral’: Images of people showing no prominent emotion in their facial expression at all.
