# Machine Learning Course Repository <img src="University_of_Tehran_logo.svg.png" alt="Machine Learning" width="50">



Welcome to the Machine Learning course repository offered at the University of Tehran. This repository contains code for assignments and projects completed during the course. The course was taught by esteemed professors:

- [Dr. Babak Najar Arabi](https://scholar.google.com/citations?user=FTcata0AAAAJ&hl=en)
- [Dr. Mohammad-Reza A. Dehaqani](https://scholar.google.com/citations?user=HuMGDxIAAAAJ&hl=en)
- [Dr. Mostafa Tavassolipour](https://scholar.google.com/citations?user=oVAT1lYAAAAJ&hl=en)

## Course Description

This course focuses on various aspects of Machine Learning, covering fundamental concepts and advanced techniques. 

## Table of Contents

Please find below a brief overview of the contents of this repository:
1. `HW1/`: This directory contains code for Assignment 1, which focused on Bayes. The assignment includes code for implementing Naive Bayes without using any libraries.
2. `HW2/`: This directory contains code for Assignment 2, which focused on Regression. The assignment includes code for implementing Naive Bayes without using any libraries.
3. `HW3/`: This directory contains code for Assignment 3, which focuses on KNN (K-Nearest Neighbors), Neural Network, and Decision Tree algorithms. The assignment includes code for implementing a simple CNN (Convolutional Neural Network) for CIFAR-10 dataset and perceptron for the Iris dataset.
4. `HW4/`: This directory contains code for Assignment 4, which focuses on SVM (Support Vector Machine). The assignment includes code for implementing SVM with different hyperparameters and comparing their results. Additionally, it contains code for implementing SVR (Support Vector Regression) for a simple regression task.
5. `HW5/`: This directory contains code for Assignment 5, which focuses on feature selection methods, including LDA (Linear Discriminant Analysis), PCA (Principal Component Analysis), Sequential Forward Selection (SFS), and Recursive Feature Elimination(RFE). The assignment includes code for implementing SFS and RFE on the Wine dataset. Additionally, PCA has been implemented for the Faces dataset. In Q7, LDA has been implemented for the Fashion-MNIST dataset.
6. `Final Project/`: Here, you can find code related to the projects completed as part of the course requirements.  This particular project focuses on the classification of Dastgah in Persian music. Dastgah refers to the modal system in Persian music, which organizes melodic types (gūšas) and arranges them around a dominant mode (māya). Each dastgāh derives its name from this dominant mode, which is played during the introductory parts. Our objective in this project is to classify music based on their respective dastgahs. To accomplish this, we follow these key steps:
   * **Data Collection**: We have collected a comprehensive dataset, accessible through this [link](https://docs.google.com/spreadsheets/d/1QmJ2MomwjbD2N-9TZks4IhPzGdarQnYb9HgU-G0T3Cc/edit#gid=0).
   *   **Data Preprocessing, analysis, and visualization**: To build a robust model, 
   need to clear our dataset by deleting incorrect files. Also, we need to find features that have the most correlation with our labels and help us in the       classification and clustering tasks.
   *   **Feature extraction**: Based on the information acquired in the first part we need to extract features and prepare our dataset for the next part. We use two sets of feautres for this project, the first set are as followed:
    *   Zero Crossing Rate: The rate at which the signal changes from positive to negative or back.
    *   STFT (Short Time Fourier Transforms): The STFT represents a signal in the time-frequency domain by computing discrete Fourier transforms (DFT) over short overlapping windows
    *   Harmonics and Perceptrual: Harmonics are characteristichs that human years can't distinguish (represents the sound color). Perceptrual understanding shock wave represents the sound rhythm and emotion
    *   Tempo BMP (beats per minute): Dynamic programming beat tracker.
    *   Spectral Centroid: Indicates where the ”centre of mass” for a sound is located and is calculated as the weighted mean of the frequencies present in the sound.
    *   Spectral Rolloff: It is a measure of the shape of the signal. It represents the frequency below which a specified percentage of the total spectral energy, e.g. 85%, lies
    *   Spectral Bandwidth: Spectral Bandwidth is the spectral range of interest around the centroid, that is, the variance from the spectral centroid.
    *   Mel-Frequency Cepstral Coefficients: The Mel frequency cepstral coefficients (MFCCs) of a signal are a small set of features (usually about 10–20) which concisely describe the overall shape of a spectral envelope. It models the characteristics of the human voice.
    *   Chroma Frequencies: Chroma features are an interesting and powerful representation for music audio in which the entire spectrum is projected onto 12 bins representing the 12 distinct semitones (or chroma) of the musical octave.
   *   **Classification**: In this part, Based on the features extracted from the model and their correlation with our classes, We need to design the best model that does the task of classifying. In this project, We try models such as Multilayer Perceptron, SVM, etc.
   *   **Clustering**: Clustering music dastgah is a task of grouping music based on the similarities in their audio characteristics.

## Disclaimer

This repository is for archival and reference purposes only. The code here might not be updated or maintained. Use it at your own discretion.
