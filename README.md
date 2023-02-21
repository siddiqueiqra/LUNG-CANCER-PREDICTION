# LUNG-CANCER-PREDICTION
- This project is about predicting lung cancer using logistic regression.

- The dataset used for this project contains information about the age, smoking history, alcohol consumption, and living area of 59 patients, as well as their cancer status (alive or dead).

- After loading the dataset, the low-variance columns were dropped. The data was then split into independent (X) and dependent (y) variables, and then split into training and testing sets using train_test_split from sklearn.

- Logistic regression was used to fit the model to the training set, and the accuracy of the model was evaluated using the testing set. The accuracy score was found to be 1.0, indicating that the model correctly predicted all cases in the testing set. A confusion matrix was also created to visualize the true positives, true negatives, false positives, and false negatives.

- This project can be useful for medical professionals and researchers who want to predict lung cancer in patients based on various factors. The code is available in the Jupyter Notebook format and can be run using Python 3.
