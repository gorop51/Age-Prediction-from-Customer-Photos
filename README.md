# 👤 Age Prediction from Customer Photos

## 📌 Project Overview

Developed a computer vision model for the "Khleb-Sol" supermarket chain to estimate customer age from photos captured at checkout. The solution enables personalized marketing and ensures compliance with alcohol sales regulations by accurately identifying customer age groups.

## 🎯 Objective

Build a deep learning model that:
- Predicts approximate age from customer photos with minimal error
- Supports business goals through age-based product recommendations
- Helps prevent underage alcohol sales through reliable age verification
- Achieves sufficient accuracy for practical business applications

## 📊 Dataset Description

- **7,591 labeled photos** of customers with corresponding real ages
- Age range: 1 to 100 years
- Age distribution: 
  - Mean age: 31.2 years
  - Standard deviation: 17.1 years
  - Slightly right-skewed distribution (skewness = 0.73)
- Images resized to 224×224 pixels for model input

## 🔍 Methodology

### Data Preparation
- Implemented image normalization (rescale=1/255)
- Used ImageDataGenerator for efficient data loading
- Applied proper train/validation splitting

### Model Development
- Built convolutional neural network architecture
- Leveraged transfer learning approaches for image recognition
- Optimized model to handle the natural age distribution skew
- Focused on minimizing mean absolute error (MAE) as primary metric

### Business Integration
- Designed model output for practical business applications
- Ensured predictions align with meaningful age groupings
- Balanced accuracy requirements with computational efficiency

## 📈 Results

The developed model:
- Achieves accurate age estimation across diverse age ranges
- Effectively identifies age groups for targeted marketing
- Provides reliable verification for alcohol sales compliance
- Enables personalized shopping experiences based on customer demographics

This solution empowers "Khleb-Sol" to enhance customer experience through age-appropriate product recommendations while ensuring regulatory compliance, ultimately driving sales and improving customer satisfaction through data-driven personalization.
