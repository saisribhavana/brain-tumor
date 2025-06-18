identify brain tumors from MRI scans with high accuracy. The model achieves 95% classification accuracy, offering a promising tool for aiding medical professionals in early diagnosis and treatment planning.

🔍 Overview
Brain tumors are life-threatening conditions that require timely and accurate diagnosis. Leveraging the power of Convolutional Neural Networks (CNNs), this project aims to:

Automate the detection of brain tumors in MRI images

Enhance diagnostic accuracy using a hybrid of two powerful CNN models

Provide a reproducible and open-source solution for medical image classification

🧪 Model Architecture
The hybrid model combines the feature extraction capabilities of:

VGG19: Known for its deep layers and simplicity

InceptionV3: Known for its efficiency and multi-scale convolutional features

The outputs of both models are concatenated and passed through dense layers for final classification.

📊 Results
Accuracy: 95%

Loss: Minimal validation loss indicating effective learning
