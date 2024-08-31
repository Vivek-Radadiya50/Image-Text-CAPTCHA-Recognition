# Image Text CAPTCHA Recognition

## 1. About the Dataset
This project involves extracting text from web CAPTCHAs using Optical Character Recognition (OCR) techniques. The dataset comprises images of CAPTCHAs, which are designed to test a user's ability to recognize distorted text. The goal is to analyze and improve CAPTCHA security by recognizing and extracting text from these images.

## 2. Objective
The primary objectives of this project are to:
- Extract text from web CAPTCHAs using OCR.
- Analyze vulnerabilities in CAPTCHA designs.
- Propose improvements to enhance CAPTCHA security and robustness.

## 3. Approach
The project employs two different machine learning approaches for CAPTCHA text recognition:
- **Convolutional Neural Network (CNN) with Fully Connected Layers:**
  - Implemented a CNN model with convolutional and max-pooling layers.
  - Utilized a 5-step output vector to predict individual characters from CAPTCHAs.
- **CNN + Bi-LSTM Model:**
  - Applied a combination of CNN and Bidirectional Long Short-Term Memory (Bi-LSTM) networks.
  - Used Connectionist Temporal Classification (CTC) loss for sequence prediction.
  - Incorporated dropout and batch normalization layers for regularization.
  - Added ResNet layers to improve feature extraction and performance.

## 4. Results & Key Features
- **Accuracy:** Achieved over 95% accuracy in recognizing text from a single type of CAPTCHA.
- **Model Generalization:** Currently working on Generative Adversarial Networks (GANs) to generalize the model for various types of CAPTCHAs, enhancing its versatility and robustness.

## 5. License
This project is licensed under the MIT License. For detailed licensing information, refer to the [LICENSE](LICENSE) file in this repository.

## 6. Contact
For any questions or feedback regarding this project, please contact:
- ** Vivek Radadiya**
