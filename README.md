# Analyzing Smoking Behavior

Project_authors: Herbert Shin, Eyoel Hailemariam, Thai Luong, Colin Smith

## Overview
This project explores the use of machine learning and neural networks to classify individuals as smokers, former smokers, or non-smokers based on biological, physical, and psychological data.<br />
The research compares two primary AI models — a Deep Feedforward Neural Network (NN) and a Random Forest (RF) — to determine which performs better at identifying smoking behavior patterns.<br /><br />

The work aims to contribute to AI in healthcare by demonstrating how automated behavioral detection can aid public health strategies and personalized treatment programs.<br />

## Objectives
Develop an AI-based system for early detection of smoking behavior.<br />
Compare Neural Network and Random Forest models on predictive accuracy and generalization.<br />
Evaluate which approach better handles real-world health data from public datasets.<br />
Explore potential applications of AI in preventive healthcare and smoking-cessation research.<br />

## Dataset
Source: Kaggle — Smoking and Drinking Dataset with Body Signal<br />
Provider: National Health Insurance Service, Korea<br />
Entries: 991,346 samples<br /><br />

## Methodology
### Neural Network (NN)
-Architecture: 3 Dense layers (64 → 32 → 3)<br />
-Activations: ReLU for hidden layers, Softmax for output<br />
-Regularization: 20% Dropout<br />
-Optimizer: Adam (dynamic learning rate)<br />
-Loss Function: Sparse Categorical Cross-Entropy<br />
-Accuracy: ~70% overall on test set<br />
-Strength: Strong at identifying non-smokers (Class 0)<br />
-Weakness: Difficulty distinguishing between former and current smokers<br />

### Random Forest (RF)
-Mechanism: Ensemble of decision trees with feature importance weighting<br />
-Strength: Balanced performance across all three classes, less overfitting<br />
-Weakness: Slightly slower inference as tree count increases<br />

### Tools & Libraries
-Python 3.10+<br />
-TensorFlow / Keras<br />
-scikit-learn<br />
-pandas / numpy<br />
-matplotlib / seaborn<br /><br />

## HOW TO RUN
1/ open AI2_Final.ipynb in jupyter notebook<br />
2/ unzip smoking_driking_dataset_Ver01.zip<br />
3/ in jupiter notebook make sure to have requirement libs<br />
4/ run all<br />
