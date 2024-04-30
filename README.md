# Breast cancer prediction using machine learning

Data Collection: The dataset contains various features extracted from breast cancer patients, such as tumor size, shape, texture, etc. along with their corresponding diagnosis (malignant or benign).
Data Preprocessing: Before training the model, the data is preprocessed to ensure it's in a suitable format. This includes handling missing values, encoding categorical variables, and standardizing numerical features.
Model Training: The Logistic Regression model is trained on the preprocessed data. Logistic Regression is a common choice for binary classification problems like this one.
Model Evaluation: The trained model is evaluated using metrics such as accuracy, precision, recall, and F1-score on a separate test dataset. These metrics give an indication of how well the model is performing at distinguishing between malignant and benign tumors.
Model Deployment: Once the model is trained and evaluated, it can be deployed for real-world use. In this case, it's saved using pickle for future use. Medical professionals can then use this model to make predictions on new data.
Utility in Predicting Breast Cancer: By inputting relevant features of a breast tumor into the trained model, it can predict whether the tumor is likely to be malignant or benign. This prediction can aid healthcare professionals in making decisions about further diagnostic tests, treatment planning, and patient care.
