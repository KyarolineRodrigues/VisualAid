# VisualAid
Image Captioning for Visually Impaired Users

VisualAid is an AI-powered system designed to assist visually impaired individuals by automatically generating descriptive captions for images. The system uses deep learning techniques to understand image content and convert it into meaningful text, which can also be converted to speech.
The project combines computer vision and natural language processing to provide an accessible solution that helps users understand visual information.
Project Objective

The main objective of VisualAid is to:
Automatically generate captions for images
Help visually impaired individuals understand visual content
Convert generated captions into audio feedback
Demonstrate the application of deep learning in accessibility solutions

Technologies Used
Python
TensorFlow / Keras
CNN (InceptionV3)
LSTM (Long Short-Term Memory)
Flask (for web application)
Google Colab (model training)
gTTS / pyttsx3 (Text-to-Speech)

Dataset
The model is trained using the Flickr8k dataset, which contains:
8,000 images
5 captions for each image
The dataset is commonly used for image captioning tasks.
Dataset link:
https://www.kaggle.com/datasets/adityajn105/flickr8k

Output
The system generates:
Text caption describing the image
Audio output of the caption using Text-to-Speech
