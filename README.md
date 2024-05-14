# CS298 - Comparing Balancing Techniques For Malware Classification

## Description
This code will experiment to find the best data balancing technique for
malware classification when training with an imbalanced dataset. This project will leverage
opcode proportions in binary files as training features for the classifiers. The code will try 
undersampling and oversampling the training data and consider metrics such as: precision, 
recall, f1-score, and accuracy. Four (4) machine learning models will be used as malware 
classifiers for the experiments. Random Forest (RF), Support Vector Machines (SVM), KNeighbors, 
and Multi-layer Perceptron (MLP) models will be trained with the VirusShare dataset which consists 
of binary files transformed into assembly opcodes. The best balancing technique for classifying malware
families by category and name will be selected.


## Technologies Used

- Python
- Google Colab/Python Notebook


## Setup

To run this project, follow these steps:
1. Download files and run on Google Colab or Python Notebook
2. Datasets can be found in the 'Dataset' folder
