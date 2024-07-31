# TOR Network Usage Detection with Deep Learning

## Overview
The usage of the TOR network poses significant risks as it can facilitate anonymous communication for malicious activities. Detecting TOR network traffic is crucial for enhancing cybersecurity measures.

## Dataset
The dataset used in this project is the ISCXT TOR 2016 dataset.

## Preprocessing
Several preprocessing steps were taken to prepare the data for training:
- Removal of source and destination IP columns.
- Removal of rows containing NaN and infinite values.
- Removal of columns where the majority of values are zeros.
- Encoding the label column: 0 for the negative class (non-TOR) and 1 for the positive class (TOR).

## Handling Class Imbalance
The TOR and non-TOR classes are imbalanced, which can cause issues in classification. To address this, the classes were balanced to ensure better model performance.

## Models
Two deep learning architectures were used for this project:
- Convolutional Neural Network (CNN)
- Deep Neural Network (DNN)

## Cross-Validation
Cross-validation was applied with the CNN architecture to enhance performance.

## Note
This project aims to detect TOR network usage using deep learning techniques. The implementation includes detailed preprocessing steps and model training procedures to achieve reliable detection.


