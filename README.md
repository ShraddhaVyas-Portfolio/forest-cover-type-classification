Forest Cover Type Classification using TensorFlow
Overview
This project uses deep learning to predict forest cover type based on cartographic variables from the US Forest Service and US Geological Survey.

The objective was to build and evaluate a multi-class classification model using TensorFlow and Keras.

Dataset
The dataset contains 581,012 observations and 54 input features, including:

Elevation
Aspect
Slope
Distance to Hydrology
Distance to Roads
Distance to Fire Points
Wilderness Areas
Soil Types
Target Variable:

Forest Cover Type (7 Classes)
Technologies Used
Python
TensorFlow
Keras
Pandas
NumPy
Scikit-Learn
Matplotlib
Methodology
Data Exploration
Train-Test Split
Feature Scaling
Neural Network Development
Model Evaluation
Hyperparameter Tuning
Neural Network Architecture
Dense (128, ReLU)
Dense (64, ReLU)
Dense (32, ReLU)
Dense (8, Softmax)
Results
Test Accuracy: 78.93%

Key Learnings
Deep Learning Classification
TensorFlow and Keras Workflows
Multi-Class Classification
Data Preprocessing
Feature Scaling
Hyperparameter Tuning
Conclusion
The model successfully predicted forest cover types from environmental and cartographic variables and achieved strong classification performance.