# Image Caption Generator
This project implements an AI system that generates contextually relevant captions for images using deep learning techniques. It uses an **encoder-decoder architecture** with InceptionV3 for image feature extraction and an LSTM-based decoder for caption generation. The system is trained on a custom image-caption dataset and evaluated using BLEU scores.

## Features
- Preprocesses and normalizes images for model input.  
- Encodes images with **InceptionV3** pretrained on ImageNet.  
- Tokenizes and encodes captions for training.  
- Implements an **encoder-decoder LSTM model** for caption generation.  
- Generates captions for new images.  
- Evaluates performance using **BLEU scores**.  
- Visualizes generated captions alongside images.  
- Supports batch processing for memory-efficient training.  

## Workflow
1. **Data Preparation** – Load and preprocess images and captions.  
2. **Tokenization** – Convert captions to sequences and encode them.  
3. **Feature Extraction** – Use InceptionV3 to extract image features.  
4. **Model Training** – Train the encoder-decoder LSTM model using data generators.  
5. **Evaluation** – Generate captions and compute BLEU scores.  
6. **Visualization** – Display images with predicted captions.  

## Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib, PIL  
- Scikit-learn  
- NLTK (BLEU score evaluation)  
- Google Colab  
