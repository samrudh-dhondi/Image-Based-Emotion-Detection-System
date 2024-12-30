
# Image-Based-Emotion-Detection-System

An emotion prediction system involves using techniques such as machine learning, specifically convolutional neural networks (CNNs), to recognize and classify emotions depicted in visual content. This process train models on labeled datasets containing images associated with specific emotions (e.g., happiness, sadness, anger). Once trained, these models can analyze new images and accurately predict the emotions they convey.

### Methodology

- Dataset Loading and Preprocessing: Load facial images categorized by emotions. Preprocess images (resizing to a consistent size, label encoding).

- Model Definition and Training: Define a CNN model with convolutional and pooling layers for feature extraction, followed by fully connected layers for classification. Train the model using the preprocessed dataset.

- Model Evaluation: Evaluate the model using metrics like accuracy and loss on training and testing datasets.

- Model Saving: Save the trained model for future predictions, eliminating the need for retraining.

- Output Display: Input an image, and the pre-trained model predicts the dominant emotion. Display the image with the predicted emotion overlaid in real-time.


## Features

- Accurate Emotion Recognition: Utilizes CNNs for learning hierarchical features from facial images.
- Real-time Prediction: Provides fast and reliable emotion predictions with a user-friendly display.
- Reusable Model: Trained model can be used directly for predictions without retraining.

## Evaluation

![graph](https://github.com/user-attachments/assets/5f4566c2-8b1f-4a76-b37f-63218248457e)

## Demo

- Upload a facial image.
- Get the predicted emotion displayed in real-time.

![output 1](https://github.com/user-attachments/assets/2811807a-f2cc-410f-8301-8cacca19fc55)



