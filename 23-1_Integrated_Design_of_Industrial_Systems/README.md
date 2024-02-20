# Imperfect Fruit Utilization System for Farming Profit Enhancement

## Project Timeline
**March 2023 - June 2023**

## Introduction
In an innovative effort to boost farm incomes, this project aimed at leveraging imperfect fruits, which are often undervalued and discarded, thereby creating a more sustainable and profitable avenue for farmers. The initiative involved developing a system to identify and categorize these fruits, potentially opening up new markets and reducing food waste.

## Data Collection and Preparation
One of the initial hurdles was the absence of a suitable dataset for training our model. To tackle this:

- **True Dataset Creation**: We embarked on a direct approach by purchasing imperfect fruits and creating a comprehensive dataset from scratch.
- **False Dataset Acquisition**: For comparison and model training purposes, standard fruit datasets were sourced from platforms like Kaggle.

## Training Challenges and Solutions

### Overfitting Issue
The project encountered significant challenges with model overfitting, primarily due to the small size of our custom dataset. Our approach involved fine-tuning a pre-trained ResNet18 model, expecting to leverage its learned features for our unique classification task.

### Strategies Implemented
- **Data Augmentation**: Despite employing various data augmentation techniques to enrich the dataset and introduce variability, overfitting persisted, indicating the limitations of augmentation in compensating for a small dataset size.
- **Model Parameter Freezing**: Adjusting the freeze level of the pre-trained model's parameters was also explored as a strategy to mitigate overfitting. However, this did not result in a meaningful improvement in model performance.

## Conclusion and Future Directions
This project underscored the critical need for ample and diverse datasets in training machine learning models, especially for specialized tasks like classifying imperfect fruits. It also highlighted the challenges of utilizing pre-trained models in a fine-tuning context with limited data.

Moving forward, the project aims to:
- Expand the dataset significantly to provide a richer foundation for training.
- Explore more sophisticated data augmentation and transfer learning strategies.
- Investigate alternative models and training techniques that might be more resilient to overfitting with small datasets.

By addressing these challenges, we hope to refine our system further, enhancing its accuracy and reliability, and ultimately contributing to a more sustainable and profitable farming ecosystem by valorizing imperfect produce.
