# Application of Machine Learning for Tsunami Prediction

## Team Information

- **Team Member 1:** Rakshit Upadhyay  
  **ID:** WQ24-Z2CGEFbNfS0B1Lf

- **Team Member 2:** Mariam Baher Elmaghraby  
  **ID:** WQ24-a0JkSQECeSwldfO

- **Team Member 3:** Arina Kleizer  
  **ID:** WQ24-ABiY30kL7jvzL7T

## 1. What is your project about? What problem are you trying to solve?

Our project is focused on developing a machine learning model to predict tsunamis based on seismic data. The goal is to enhance existing tsunami early warning systems by creating a model that can accurately predict the likelihood of a tsunami following an earthquake. This is crucial for minimizing damage and preventing loss of life, as timely warnings can save thousands of lives.

## 2. What were the different objectives of your project and how did you achieve them?

The main objectives of our project included:

- **Feature Selection and Engineering:** We focused on selecting and engineering features that could be strong indicators of tsunamis, such as earthquake magnitude, geographic location (latitude and longitude), and the interaction of these features. We also added additional features, such as the square of the magnitude and the interaction between latitude and longitude, to improve the predictive power of the models.

- **Exploration of Various Machine Learning Models:** We experimented with several models, including Logistic Regression, Random Forest, and Support Vector Machine (SVM). We evaluated the performance of each model based on metrics like accuracy, recall, and precision.

- **Building an Ensemble Model:** After comparing the performance of different models, we decided to use an ensemble model that combines the strengths of all approaches. This allowed us to improve overall accuracy and reliability of the predictions.

- **Model Optimization:** We also optimized the ensemble model’s hyperparameters to achieve the best balance between recall (catching potential tsunamis) and precision (avoiding false alarms), which is especially important for an early warning system.

- **Integrating the Model into a Real-Time Seismic Monitoring System:** To ensure that the system can process incoming seismic data, make predictions rapidly, and issue warnings with minimal delay.

## 3. Did you achieve your desired results? What were your success metrics? How did your project make an impact on the current field of research?

The project was successful: our ensemble model achieved an accuracy of approximately **78.89%**, and the precision for predicting tsunamis was about **83%**. These results demonstrate that our model is reliable enough to be used in early warning systems.

Our success metrics for the project included:

- **Accuracy:** The ratio of correct predictions to the total number of predictions. This metric shows how often our model correctly identifies the presence or absence of a tsunami.
  
- **Precision:** The proportion of true positive predictions among all positive predictions. High precision is particularly important to avoid false alarms.

- **Recall:** The ability of the model to capture all positive cases (in this case, tsunamis). High recall is crucial for minimizing missed tsunami predictions.

Our project has the potential to significantly impact the current field of tsunami prediction by providing more accurate and timely warnings, which could substantially reduce the damage from these natural disasters.

## 4. What are some future steps you would recommend to extend your project? What limitations are you facing today that are stopping you from achieving your future recommendations?

To further extend the project, we recommend the following steps:

- **Categorical Variable Processing:** Transforming categorical data, such as tsunami cause codes, into numerical formats using encoding methods could improve the predictive capability of the model.

- **Cross-Validation:** Incorporating cross-validation into the model evaluation process to increase the reliability of results and minimize the impact of random fluctuations in the data.

- **Hyperparameter Optimization:** Using grid search or randomized search methods for further optimization of model hyperparameters, which could lead to improved accuracy and recall.

- **Class Balancing:** Applying class balancing techniques such as oversampling or undersampling to improve prediction accuracy in the presence of imbalanced data.

- **Result Visualization:** Adding result visualization tools, such as ROC curves and Precision-Recall curves, to better understand model performance and assess risks.

Currently, our main limitation is the limited amount of data and potential class imbalance (e.g., a significant prevalence of non-tsunami events over tsunami events). These limitations may affect the accuracy and reliability of predictions. To overcome these limitations, we could consider expanding the dataset, using data augmentation methods, or incorporating additional data sources.


