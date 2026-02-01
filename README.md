Diabetes Prediction System

This project implements an end-to-end machine learning pipeline for diabetes prediction using clinical and demographic health data. The system focuses on data preprocessing, model comparison, and deployment to deliver a practical and interpretable predictive solution.

The workflow starts with data cleaning and preprocessing, where medically invalid zero values in key features (such as Glucose, Blood Pressure, Insulin, BMI, and Skin Thickness) are handled using median-based imputation. Feature scaling is applied using Min-Max normalization to ensure stable and fair model training.

Multiple machine learning models are trained and evaluated, including Logistic Regression, Random Forest, Support Vector Machine (SVM), and a Deep Learning Neural Network built with TensorFlow/Keras. Model performance is compared using test accuracy, highlighting the strengths of both classical ML algorithms and neural networks for tabular healthcare data.

The best-performing classical model (Logistic Regression) is serialized and deployed using pickle, enabling real-time predictions based on user-provided medical inputs. The system allows users to enter health indicators through a simple interface and receive an immediate diabetes risk prediction.

This project demonstrates practical skills in:

Healthcare data preprocessing and feature engineering

Supervised learning and model comparison

Neural network design for binary classification

Model deployment and inference using Python

Overall, the project showcases the application of machine learning techniques to solve a real-world healthcare prediction problem with a focus on reliability, interpretability, and deployment readiness.
