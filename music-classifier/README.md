# Music Genre Classification

Machine learning model that classifies music tracks into genres using audio features extracted from audio signals.

## Project Overview

This project applies machine learning techniques to classify music tracks into different genres using numerical audio features. The model learns patterns in musical characteristics such as spectral properties, rhythm, and energy levels to distinguish between genres.

Music genre classification is useful for music recommendation systems, automatic tagging, and organizing large music libraries.

## Dataset

The dataset contains audio features extracted from music tracks. Each track is represented using numerical features derived from signal processing.

Typical features include:

- chroma_stft  
- spectral centroid  
- spectral bandwidth  
- rolloff  
- zero crossing rate  
- tempo  
- MFCC coefficients  

Target variable:

label- represents the genre of the music track.

Example genres include:

- blues  
- classical  
- country  
- disco  
- hiphop  
- jazz  
- metal  
- pop  
- reggae  
- rock  

## Tools and Libraries

- python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

## Machine Learning Workflow

### Data Exploration
- inspect dataset structure  
- check genre distribution  
- visualize feature relationships  

### Data Preprocessing
- encode genre labels  
- scale numerical features when required  
- split dataset into training and testing sets  

### Model Training
- logistic regression  
- random forest classifier  
- support vector machine  

### Model Evaluation
- accuracy score  
- confusion matrix  
- classification report  
