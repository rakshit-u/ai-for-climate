# Application of Machine Learning for Tsunami Prediction
Team Information

- **Team Member 1:** Rakshit Upadhyay  
  **ID:** WQ24-Z2CGEFbNfS0B1Lf

- **Team Member 2:** Mariam Baher Elmaghraby  
  **ID:** WQ24-a0JkSQECeSwldfO

- **Team Member 3:** Arina Kleizer  
  **ID:** WQ24-ABiY30kL7jvzL7T
## Project Overview

This project focuses on developing a machine learning model to predict tsunamis based on seismic data. The primary goal is to enhance existing tsunami early warning systems by creating a model that can accurately predict the likelihood of a tsunami following an earthquake. This is crucial for minimizing damage and preventing loss of life, as timely warnings can save thousands of lives.

## Objectives and Approach

### Feature Selection and Engineering

- We focused on selecting and engineering features that could serve as strong indicators of tsunamis, such as:
  - Earthquake magnitude
  - Geographic location (latitude and longitude)
  - Interaction between these features
- Additional features were created to enhance predictive power:
  - **Magnitude Squared**: The square of the earthquake magnitude.
  - **Latitude-Longitude Interaction**: The product of latitude and longitude.

### Exploration of Machine Learning Models

- We experimented with several machine learning models, including:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
- Performance was evaluated using metrics like **accuracy**, **recall**, and **precision**.

### Building an Ensemble Model

- After comparing model performance, we decided to use an ensemble model that combines the strengths of different approaches.
- The ensemble model was optimized to achieve the best balance between **recall** (capturing potential tsunamis) and **precision** (avoiding false alarms).

## Results

- **Accuracy**: Our ensemble model achieved an accuracy of approximately **78.89%**.
- **Precision**: The model demonstrated a precision of about **83%** for predicting tsunamis, indicating its reliability for early warnings.

These results suggest that our model is reliable enough to be integrated into tsunami early warning systems, potentially making a significant impact on the field.

## Future Work and Recommendations

### Categorical Variable Processing

- Transform categorical data (e.g., tsunami cause codes) into numerical formats using encoding methods to improve model performance.

### Cross-Validation

- Implement cross-validation to enhance the reliability of model evaluation and minimize random fluctuations in the data.

### Hyperparameter Optimization

- Utilize grid search or randomized search methods for further optimization of model hyperparameters to potentially increase accuracy and recall.

### Class Balancing

- Apply techniques like oversampling or undersampling to address any class imbalance, which could improve prediction accuracy.

### Result Visualization

- Incorporate visual tools such as ROC curves and Precision-Recall curves to better understand model performance and assess risks.

## Limitations

Currently, the main limitations include:

- **Limited Data**: The dataset is relatively small, which may impact model performance.
- **Class Imbalance**: A potential imbalance in the target variable (e.g., more non-tsunami events than tsunami events) could affect prediction accuracy.

To overcome these limitations, future work could focus on expanding the dataset, using data augmentation techniques, or integrating additional data sources.

