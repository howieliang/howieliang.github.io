# Interactive Intelligent Products

----------

DBB220 / 2019 Semester B Quartile 4 / TU Eindhoven

## Online Lectures for Rapid Prototyping Interactive Products with Machine Learning and Signal Processing.

*(Beta Version: Open to TU/e Industrial Design PhD Students and Scientific Staffs)*
Example Codes: [**Github Repository**](https://github.com/howieliang/IIP1920)

----------

**Responsible Lecturer: Dr. Rong-Hao Liang** 
*Assistant Professor, Future Everyday Group, Industrial Design, TU Eindhoven; Assistant Professor, Signal Processing Systems Group, Electrical Engineering, TU Eindhoven*
*Homepage: http://ronghaoliang.page/*

----------

**Sensors** not only enable the interactivity of products but also generate data. **Machine intelligence** leverages computational power and data to empower further the product to deal with design problems involved prediction, decision, and adaptation. This course aims to help the industrial students understand the main paradigms in sensing, data collection, signal processing, and machine learning to apply them in meaningful design solutions of **intelligent interactive products**.

![An Interactive Intelligent Product](https://paper-attachments.dropbox.com/s_2872065C7B1453917D680BF73E65026F47C98466B9BC5AC6E5A3A3247AFA79E1_1590905704193_image.png)


The course combine theories and practices. Through a series of lectures and workshops, you will learn the principle and functionality of the sensors and machine intelligence. You will develop the ability to use these signal processing methods and machine learning algorithms to deal with everyday life problems where real-world complexity, uncertainty, and changing conditions make the use of these technical solutions a necessity. Understanding the type of problems that really will benefit from the utilization of signal processing methods and machine learning algorithms and creating realistic scenarios of use is equally important.

[**Arduino**](https://www.arduino.cc/)**,** [**Processing**](https://processing.org/), and [**Weka**](https://www.cs.waikato.ac.nz/~ml/weka/) are used as the development platform. Ready available example codes are available in [**Github repository**](https://github.com/howieliang/IIP1920), so you don’t have to implement the algorithms from scratch.


![Course Overview: Topics Covered in Interactive Intelligent Products](https://paper-attachments.dropbox.com/s_2872065C7B1453917D680BF73E65026F47C98466B9BC5AC6E5A3A3247AFA79E1_1590991337954_image.png)

----------
## Teaching Assistants

Dr. Zengrong Guo, *Postdoc Researcher, Future Everyday Group, Industrial Design, TU Eindhoven*
Ruben van Dijk, *PhD candidate, Future Everyday Group, Industrial Design, TU Eindhoven*

# 1. Introduction and Problem Formulation
----------
## 1.1 Introduction
- **Overview**
- **Prerequisites**
- **Schedule**
- **Module 1: Machine Learning**
- **Module 2: Signal Processing**
- **Synergies Between The Two Modules**

## 1.2 Problem Formulation
- **Why Machine Learning?**
- **Formulate Supervised Learning problems**
- **Types of Learning**

# 2. Data Preparation and Serial Communication
----------
## 2.1 Data Preparation
- **CSV vs. ARFF**
- **Save data as ARFF files**
- **Load data as ARFF files**

## 2.2 Serial Communication
- **Timer and Uniform Sampling**
- **Send Sensor Data Stream to Processing**
- **Save Serial Data as ARFF files**
- **Bidirectional Serial Data Streaming between Arduino and Processing**

# 3. Classification and Regression
----------
## 3.1 Classification
- **Noise in Data**
- **Linear Support Vector Classification**
    - Linear Support Vector Classifier
    - Train a classifier from data
    - Confusion matrix and In-sample accuracy
    - Overfitting and out-of-sample accuracy
    - Regularization
    - k-fold Cross-Validation
    - Optimize a prediction model
    - Load a test set and get the out-of-sample accuracy
- **Real-Time Posture Classification**

## 3.2 Regression
- **Linear Regression**
    - Linear Regressor
    - Train a regressor from data
    - Loss function
    - Linear Regression in higher dimension
- **Real-Time Posture Regression**

# 4. Time-Series Signal Processing
----------
## 4.1 Time-Series Signal Processing
- **Visualizing Sensor Data Stream**
- **Segmentation and Activation Threshold**
- **Windowing and Statistic Feature**

## 4.2 ****Real-Time Motion Classification and Regression
- **Real-time motion classification**
- **Real-time motion regression**
- **Using More Features**

# 5. Evaluation and Reporting
----------
## 5.1 More Algorithms
- **More Classifiers**
    - K-Nearest Neighbors Classifier
    - Kernel Support Vector Classifier
- **More Regressors**
    - Linear Support Vector Regressor
    - Kernel Support Vector Regressor
- **Hyper-parameter Tuning**

## 5.2 Evaluation and Reporting
- **More Evaluation Metrics**
    - True Positive Rate
    - False Positive Rate and Specificity
    - Precision
    - F1 score
    - Area Under ROC
    - More than Two Classes
    - Reporting
- **Validation Methods**
    - Validate the product with users
    - Comparing different algorithms 
    - Reporting

# 6. Frequency-Domain Signal Processing
----------
## 6.1 Extraction Features in Frequency Domain
- **Time Series in Frequency Domain**
- **Sampling Theory**
- **Fast Fourier Transform**
- **Window Overlapping vs. Information Loss**
- **Segmentation, Windowing, and Filtering**

## 6.2 Recognizing Sounds and Vibrations
- **Real-time audio classification using a microphone**
- **Real-time vibration classification using an accelerometer**

# 7. Sensor Fusion and Feature Selection
----------
## 7.1 Sensor Fusion and Context Recognition
- **Human Activity Recognition Systems**
- **Synchronizing Sensor Data Streams**
- **Context Recognition using Sensor Fusion**

## 7.2 Feature Selection and Dimensionality Reduction
****- **Feature Selection**
- **Dimensionality Reduction**

# 8. Spatial-Domain Signal Processing
----------
## 8.1 Extracting Features from Images
- **Image Recognition and Computer Vision**
- **Bitmap Data Structure**
- **Statistic Features: Histograms**
- **Structural Features: Edges**
- **Simplification and Downsampling**
- **Segmentation methods**

## 8.2 Camera-based Activity Recognition
- **Haar Cascade Classifier**
- **Application: Real-time Face Detection**
- **Marker-based Object Tracking**
- **Infra-red Cameras**

# 9. Neural Networks and Wrap Up
----------
## 9.1 Neural Networks
****- **Artificial Neural Network**
- **Neuron and Activation Functions**
- **Forward and Backward Propagation**
- **Gradient Descent and Learning Rate**
- **Training an ANN**
- **Convolutional Neural Network**

## 9.2 Looking Back and Moving Forward

----------