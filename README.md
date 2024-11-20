# Melanoma_Detection_Case_Study

Case Study: Multiclass Classification Model for Melanoma Detection Using a Custom CNN in TensorFlow
Table of Contents
Overview
Approach
Key Findings
Technologies Utilized

###Overview

This study focuses on developing a custom convolutional neural network (CNN) to accurately detect melanoma. Melanoma is a dangerous form of cancer that causes 75% of skin cancer-related fatalities. Early detection is critical to reducing mortality rates. By leveraging a CNN to analyze images, the solution can aid dermatologists by minimizing manual effort and improving diagnostic efficiency.

The dataset, derived from the International Skin Imaging Collaboration (ISIC), contains 2,357 images classified into malignant and benign categories. It covers a range of dermatological conditions, including a slightly larger number of melanoma and mole samples.

The dataset includes the following categories:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

Approach
1. Understanding the Problem & Data
Objective: Build a CNN-based multiclass classifier to detect melanoma from images.
Dataset Preparation: Import and examine ISIC data for a thorough understanding.
2. Data Preprocessing
Dataset Creation: Organize the data into train, validation, and test sets.
Visualization: Generate visual insights into the dataset to understand distribution and patterns.
3. Model Development
Initial Model: Constructed and trained a baseline CNN model.
Addressing Overfitting/Underfitting: Applied data augmentation techniques to improve performance.
Second Iteration: Trained the augmented dataset with the revised CNN model.
4. Handling Class Imbalance
Examined class distributions and implemented rebalancing techniques to ensure fair representation of all categories.
Final Model: Built and trained the CNN model with balanced class data.
5. Evaluation
Assessed all models using training and validation metrics to identify the most effective iteration.
Key Findings
Overfitting and underfitting issues were effectively addressed using data augmentation and class rebalancing.
The final model (third iteration) achieved:
97% accuracy on the training dataset
82% accuracy on the validation dataset
The narrow gap between training and validation performance highlights the model's strong generalization ability.
Technologies Utilized
Deep Learning Frameworks: TensorFlow, Keras
Programming Languages: Python 
Libraries for Data Handling & Visualization: Pandas, Numpy, Matplotlib
