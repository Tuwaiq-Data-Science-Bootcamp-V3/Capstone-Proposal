# Capstone Proposal

## Project Title:
SpeechAware

## Group Members:
- Majed Alshnifi
- Lama Alshabani
- Omar Alnasser
- Omar Alkhenani

## Objectives:
The main objective of this project is to create a robust and accurate integrated system that integrates speaker verification with the SpeechBrain library and lip reading recognition to enhance communication. By attaining these goals, we hope to create a powerful integrated system capable of properly recognizing speech by lip-reading, verifying speakers, and enabling safe authentication processes based on speaker recognition. This technology has a wide range of possible uses, including improved communication and user authentication.

## Dataset Description:

-   Lip Reading:Fifteen speakers (five men and ten women) positioned in the frustum of a MS Kinect sensor and utter ten times a set of ten words and ten phrases. Each instance of the dataset consists of a synchronized sequence of color and depth images (both of 640x480 pixels). The MIRACL-VC1 dataset contains a total number of 3000 instances.

-   VoxCeleb:The VoxCeleb dataset is a widely used and publicly available dataset for speaker recognition research. It is designed specifically for training and evaluating speaker verification systems. The dataset comprises a large collection of speech recordings from a diverse set of celebrities and public figures.

## Dataset Link:

https://www.kaggle.com/datasets/apoorvwatsky/miraclvc1

https://www.robots.ox.ac.uk/~vgg/data/voxceleb/

## Expected (Machine Learning / Deep Learning) Algorithms:
The proposed solution will involve the application of machine learning and/or deep learning algorithms. The expected algorithms to be implemented and evaluated include:
- Convolutional Neural Networks (CNN) for lip reading
- Hybrid models combining CNN and RNN for integrated speech and lip reading
- Transfer learning techniques to leverage pre-trained models
- Data preprocessing and feature engineering techniques to improve model performance
- Embedding Models: like x-vectors, ecapa-tdnn, and ECAPA+ for extracting speaker embeddings from speech signals. 
- Distance Metrics: These metrics help in making decisions based on the similarity scores.
- Data Augmentation

These algorithms will be trained and fine-tuned on the selected dataset to achieve accurate and efficient recognition and interpretation of speech and lip movements.
