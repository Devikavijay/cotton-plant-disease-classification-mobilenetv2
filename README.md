# Cotton Plant Disease Classification using MobileNetV2
### Project Overview

This project focuses on building a deep learning model to classify diseases in cotton plant leaves using image data. The goal is to help in early detection of plant diseases, which can improve crop quality and reduce losses in agriculture.

Instead of training a model from scratch, I used a transfer learning approach with a pretrained MobileNetV2 model to achieve better performance with less data and training time.

### Objective
To classify cotton leaf images into different disease categories
To apply transfer learning for efficient model training
To understand real-world application of deep learning in agriculture

### Diseases & Dataset Details

The model is trained on the following classes:

Aphids — 400 images
Army Worm — 400 images
Bacterial Blight — 400 images
Healthy — 390 images
Powdery Mildew — 400 images
Target Spot — 390 images

This dataset provides a fairly balanced distribution across classes, helping the model learn effectively.

### Dataset - download here:
https://drive.google.com/drive/folders/1f8J6IdbnmtCH1-5aDV5W9YwlWFIyOKmH?usp=sharing

### Tools & Technologies Used
Python
TensorFlow / Keras
MobileNetV2 (Pretrained Model)
NumPy & Matplotlib
Jupyter Notebook

### Techniques Applied
Transfer Learning using MobileNetV2
Image Resizing for consistent input
Feature Extraction using pretrained weights
Adding Custom Dense Layers for classification
Model Training and Evaluation

### Model Workflow
Load and preprocess image dataset
Resize images to required input size
Load pretrained MobileNetV2 model
Add custom classification layers
Train the model on dataset
Evaluate performance on test data

### Key Learnings
Gained hands-on experience with transfer learning
Understood how pretrained models improve performance
Learned how to build and fine-tune CNN-based models
Explored practical applications of deep learning in agriculture

### Conclusion

This project shows how deep learning can be used for plant disease classification with minimal preprocessing. Using MobileNetV2 made the model efficient and suitable for real-world applications.

### Future Improvements
Add more diverse dataset for better accuracy
Apply data augmentation
Deploy as a web or mobile application
Extend to real-time disease detection
