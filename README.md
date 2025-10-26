# Analyzing Smoking Behavior

Project_authors: Herbert Shin, Eyoel Hailemariam, Thai Luong, Colin Smith

## Overview
This project explores the use of machine learning and neural networks to classify individuals as smokers, former smokers, or non-smokers based on biological, physical, and psychological data.<br />
The research compares two primary AI models — a Deep Feedforward Neural Network (NN) and a Random Forest (RF) — to determine which performs better at identifying smoking behavior patterns.<br /><br />

The work aims to contribute to AI in healthcare by demonstrating how automated behavioral detection can aid public health strategies and personalized treatment programs.<br />

## Objectives
Develop an AI-based system for early detection of smoking behavior.__
Compare Neural Network and Random Forest models on predictive accuracy and generalization.__
Evaluate which approach better handles real-world health data from public datasets.__
Explore potential applications of AI in preventive healthcare and smoking-cessation research.__

## Dataset
Source: Kaggle — Smoking and Drinking Dataset with Body Signal__
Provider: National Health Insurance Service, Korea__
Entries: 991,346 samples____

## Methodology
### Neural Network (NN)
-Architecture: 3 Dense layers (64 → 32 → 3)__
-Activations: ReLU for hidden layers, Softmax for output__
-Regularization: 20% Dropout__
-Optimizer: Adam (dynamic learning rate)__
-Loss Function: Sparse Categorical Cross-Entropy__
-Accuracy: ~70% overall on test set__
-Strength: Strong at identifying non-smokers (Class 0)__
-Weakness: Difficulty distinguishing between former and current smokers__

### Random Forest (RF)
-Mechanism: Ensemble of decision trees with feature importance weighting__
-Strength: Balanced performance across all three classes, less overfitting__
-Weakness: Slightly slower inference as tree count increases__

### Tools & Libraries
-Python 3.10+__
-TensorFlow / Keras__
-scikit-learn__
-pandas / numpy__
-matplotlib / seaborn____

## HOW TO RUN
1/ open AI2_Final.ipynb in jupyter notebook__
2/ unzip smoking_driking_dataset_Ver01.zip__
3/ in jupiter notebook make sure to have requirement libs__
4/ run all__
