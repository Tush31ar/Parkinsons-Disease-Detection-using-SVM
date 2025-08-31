# Parkinson’s Disease Classification using Machine Learning
This project applies Support Vector Machine (SVM) to classify individuals as healthy or Parkinson’s patients based on biomedical voice measurements. Using data sourced from Kaggle, I built a complete machine learning pipeline from data preprocessing and feature scaling to model training and evaluation, achieving high accuracy in predicting Parkinson’s disease.

# Executive Summary – Parkinson’s Disease Classification using SVM

## Objective
1.	The primary goal of this project was to classify whether a person has Parkinson’s disease (PD) or not, using biomedical voice measurement data.
2.	The dataset consists of voice recordings from 31 individuals (23 with PD, 8 healthy), with 195 total instances.

## Dataset Information
1. Each row represents one voice recording.
2. The status column is the target variable:
	    0 → Healthy, 
	    1 → Parkinson’s Disease
3. Features include fundamental frequency measures, jitter, shimmer, noise-to-harmonic ratios, and nonlinear measures (e.g., RPDE, DFA, spread1, PPE).

## Preprocessing
1.	Used Pandas for loading and exploring the dataset.
2.	Dropped the non-numeric name column since it is not relevant for classification.
3.	Applied StandardScaler (from scikit-learn) to standardize the features, ensuring all features contribute equally to the SVM model.

## Model Used
1.	Implemented a Support Vector Machine (SVM) classifier from scikit-learn.
2.	SVM is well-suited for binary classification problems with high-dimensional feature spaces like biomedical data.
	
## Train-Test Split
1.	Divided the dataset into training and testing sets to evaluate model generalization.
2.	Ensured that the model was validated properly on unseen data.
	
## Model Evaluation
1.	Used accuracy score as the evaluation metric.
2.	Accuracy score helps to measure how well the model predicts the correct health status of individuals.

## Python Libraries Used
1.	NumPy → Numerical computations.
2.	Pandas → Data manipulation and analysis.
3.	Scikit-learn (sklearn) → Machine learning modeling, scaling, evaluation.
4.	SVM → For classification.
5.	StandardScaler → Feature scaling.
6.	accuracy_score → Model evaluation metric.

## Skills Demonstrated
1.	End-to-end machine learning pipeline: data preprocessing → feature scaling → model building → evaluation.
2.	Applied SVM algorithm to a biomedical classification problem.
3.	Hands-on experience with real-world dataset (Parkinson’s voice dataset).
4.	Strong understanding of supervised learning, classification, and model evaluation techniques.

## Results & Insights
1. The SVM model achieved high accuracy in distinguishing between healthy individuals and those with Parkinson’s disease.
2. Standardization played a key role, as unscaled data negatively affects SVM performance.
3. The model shows promise for telemonitoring and early detection of Parkinson’s disease using voice data.


    
   	
