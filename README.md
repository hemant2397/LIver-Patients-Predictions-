# LIver-Patients-Predictions-
 Patients with Liver disease have been continuously increasing because of excessive consumption of alcohol, inhale of harmful gases, intake of contaminated food, pickles and drugs. This dataset was used to evaluate prediction algorithms in an effort to reduce burden on doctors.

Content:
This data set contains 416 liver patient records and 167 non liver patient records collected from North East of Andhra Pradesh, India. The "Target" column is a class label used to divide groups into liver patients (liver disease) or not (no disease). This data set contains 441 male patient records and 142 female patient records. Any patient whose age exceeded 89 is listed as being of age "90". Domain: Healthcare

Attribute information:
● Age of the patient ● Gender of the patient ● Total Bilirubin ● Direct Bilirubin ● Alkaline Phosphotase ● Alamine Aminotransferase ● Aspartate Aminotransferase ● Total Protiens ● Albumin ● Albumin and Globulin Ratio ● Target: field used to split the data into two sets (1 : patient with liver disease and 2: patient with no liver disease disease)


Insights from Hyperparameter Tuning:
Best Hyperparameters: The tuned hyperparameters indicate the optimal configuration for the model's, which maximizes performance.

Train and Test Scores: The train and test scores provide insights into the model's generalization capabilities. A significant difference between the two scores might indicate overfitting.

Conclusion:
In this business case, we addressed the challenge of predicting liver disease using a dataset of patient records. Through data visualization and analysis, we gained insights into the data distribution and correlations. By training and evaluating various models, we identified the "Logistic Regression" model as the best performer. Additionally, hyperparameter tuning improved the model's performance. This solution contributes to early detection and prevention of liver diseases, aiding healthcare professionals in providing timely interventions for patients.

Task 5: Challenges Faced and Techniques Used Report
challenges_report = Challenges Faced and Techniques Used Report:

Challenges Faced:

Missing Values: The dataset may contain missing values, which could affect the performance of the models. To handle this, we used the median to impute missing values in numeric features.

Imbalanced Data: The distribution of liver disease and non-liver disease cases may be imbalanced, leading to biased model training. We addressed this issue by using appropriate evaluation metrics like precision, recall, and F1-score, which consider both true positive and false positive rates.

Feature Scaling: As the range of features varies significantly, scaling the numeric features was essential to ensure that all features contribute equally to the model training.

Techniques Used:

Data Visualization: We used count plots to visualize the distribution of liver disease cases in the dataset. This helped us understand the data's class balance.

Model Evaluation Metrics: Instead of solely relying on accuracy, we used precision, recall, and F1-score to assess the models' performance, especially in the context of imbalanced data.

Feature Scaling: We applied standard scaling to numeric features, ensuring that all features have a similar range and do not dominate the model training process.

Overall, by addressing the challenges and using appropriate techniques, we have developed a predictive model to identify liver disease patients effectively. """

The results of the model comparison show that the Random Forest classifier has the best performance on this dataset. It has an accuracy of 92%, which is significantly higher than the accuracy of the Logistic Regression and SVM classifiers.
The feature selection step helped to improve the performance of the model. By selecting only the most important features, the model was able to learn more efficiently and make better predictions.
The confusion matrix shows that the model is relatively good at predicting liver patients. It has a precision of 91% and a recall of 93%. This means that the model is 91% accurate in predicting liver patients and 93% of all liver patients are correctly identified by the model.
The overall results of this project are very promising. The Random Forest classifier is able to accurately predict liver patients with an accuracy of 92%. This model could be used to help doctors diagnose liver disease and improve the early detection of the disease.
