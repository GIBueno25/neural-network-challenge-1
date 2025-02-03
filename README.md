# **Student Loan Repayment**

## **Overview*git confir --global --edit*

With knowledge of machine learning and neural networks, this project requires students to identify which features to use from a dataset to create a model that will predict the likelihood that an applicant will repay their student loans. The following steps were used:

**Data Preparation:** <br>
    *   Reading Data: The student-loans.csv file is imported into a Pandas DataFrame, and key columns are identified for features and target variables. <br>
    *   Preprocessing: The data is cleaned and prepared, focusing on defining the target variable (credit_ranking) and setting up features. <br>
**Feature Engineering & Scaling:** <br>
    *   The features (X) and target (y) datasets are created. <br>
    *   Data is split into training and testing sets. <br>
    *   StandardScaler from Scikit-learn is used to normalize feature values. <br>
**Model Development:** <br>
    *   A Deep Neural Network (DNN) is built using TensorFlow's Keras API. <br>
    *   The model architecture includes multiple layers with specified neurons tailored for the dataset. <br>
    *   Compilation and Training: The model is compiled using the binary_crossentropy loss function and optimized with the adam optimizer. Accuracy is used as the evaluation metric. <br>
**Model Evaluation:** <br>
    *   The trained model is evaluated on the test set to determine loss and accuracy. <br>
    *   Results are analyzed to assess the model's performance in predicting student loan risks. <br>
**Model Persistence:** <br>
    *   The trained model is saved in .keras format (student_loans.keras) for future use. <br>
    *   The notebook demonstrates how to reload the saved model and make predictions on new data. <br>
**Prediction and Reporting:** <br>
    *   Predictions are generated using the test dataset.
    *   A classification report is displayed to evaluate the model's predictive accuracy and performance metrics like precision, recall, and F1-score. <br>
        
## **Summary** <br>
    This notebook serves as a comprehensive guide for applying deep learning techniques to financial risk prediction, providing a solid foundation for more advanced machine learning workflows. Let me know if you need further details or explanations.

    This roject also provied recommendations for developomg a recopmmendation system to recommend student loan options for students.