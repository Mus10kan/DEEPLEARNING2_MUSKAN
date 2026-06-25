Image Caption Generator using Deep Learning (CNN + LSTM)
This project builds an automatic image captioning system using deep learning techniques. It generates meaningful textual
descriptions for images by combining computer vision and natural language processing.

Dataset
The model is trained on the Flickr8k dataset, which contains around 8,000 images, each with multiple human-written captions.

Approach
The system follows an encoder-decoder architecture:
CNN (ResNet50) is used to extract image features
LSTM is used to generate captions word by word
Additionally, MobileNetV2 is used for feature extraction and representation learning.

Key Features
End-to-end image captioning system
CNN-based image feature extraction
LSTM-based sequence generation
Pretrained model usage (ResNet50, MobileNetV2)
Works on unseen images

Results
The model generates relevant captions describing objects and actions in images with reasonable accuracy after training.

Example:
A dog is running through a field of grass

Tools & Technologies
Python, TensorFlow, Keras, NumPy, Pandas, ResNet50, MobileNetV2, LSTM

Conclusion
This project demonstrates how deep learning can connect image understanding with natural language generation to automatically describe visual content.

Python, TensorFlow, Keras, NumPy, Pandas, ResNet50, MobileNetV2, LSTMConclusion

This project demonstrates how deep learning can connect image understanding with natural language generation to automatically describe visual content.
