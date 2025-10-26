Analyzing Smoking Behavior

Project_authors: Herbert Shin, Eyoel Hailemariam, Thai Luong, Colin Smith

Overview
This project explores the use of machine learning and neural networks to classify individuals as smokers, former smokers, or non-smokers based on biological, physical, and psychological data.
The research compares two primary AI models — a Deep Feedforward Neural Network (NN) and a Random Forest (RF) — to determine which performs better at identifying smoking behavior patterns.

The work aims to contribute to AI in healthcare by demonstrating how automated behavioral detection can aid public health strategies and personalized treatment programs.

Objectives
Develop an AI-based system for early detection of smoking behavior.
Compare Neural Network and Random Forest models on predictive accuracy and generalization.
Evaluate which approach better handles real-world health data from public datasets.
Explore potential applications of AI in preventive healthcare and smoking-cessation research.

Dataset
Source: Kaggle — Smoking and Drinking Dataset with Body Signal
Provider: National Health Insurance Service, Korea
Entries: 991,346 samples

Methodology
        ->Neural Network (NN)
-Architecture: 3 Dense layers (64 → 32 → 3)
-Activations: ReLU for hidden layers, Softmax for output
-Regularization: 20% Dropout
-Optimizer: Adam (dynamic learning rate)
-Loss Function: Sparse Categorical Cross-Entropy
-Accuracy: ~70% overall on test set
-Strength: Strong at identifying non-smokers (Class 0)
-Weakness: Difficulty distinguishing between former and current smokers

        ->Random Forest (RF)
-Mechanism: Ensemble of decision trees with feature importance weighting
-Strength: Balanced performance across all three classes, less overfitting
-Weakness: Slightly slower inference as tree count increases

Tools & Libraries
-Python 3.10+
-TensorFlow / Keras
-scikit-learn
-pandas / numpy
-matplotlib / seaborn

HOW TO RUN
1/ open AI2_Final.ipynb in jupyter notebook
2/ unzip smoking_driking_dataset_Ver01.zip
3/ in jupiter notebook make sure to have requirement libs
4/ run all
