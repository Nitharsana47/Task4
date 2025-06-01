Breast Cancer Prediction Using Logistic Regression

This project uses Logistic Regression to predict whether a tumor is malignant (cancerous) or benign (non-cancerous) based on various medical features from the Breast Cancer Wisconsin dataset.

Project Workflow

Step 1: Load and Prepare the Data
Load the dataset using pandas
Drop unnecessary columns
Convert diagnosis column into numerical format (M=1, B=0)
Split into input features (X) and target (y)

Step 2: Train-Test Split
Split the dataset using train_test_split (80% train, 20% test)

Step 3: Feature Scaling
Use StandardScaler to normalize the feature values

Step 4: Train the Logistic Regression Model
Fit LogisticRegression to the scaled training data

Step 5: Make Predictions
Predict class labels and probabilities on the test data

Step 6: Evaluate the Model
Display the confusion matrix
Print the classification report (accuracy, precision, recall, F1-score)
Plot the ROC curve and calculate the AUC score

Step 7: Threshold Tuning (Optional)
Change the default probability threshold (example: from 0.5 to 0.3)
Show the new confusion matrix and classification report for the adjusted threshold

Visualizations
Confusion matrix heatmaps (for both threshold = 0.5 and 0.3)
ROC curve showing model performance
AUC score to measure overall classification ability

Requirements

Python libraries needed:
pandas
seaborn
matplotlib
scikit-learn


Expected Output

High model accuracy (typically above 90%)

AUC score close to 1.0 (very good classification)

Good precision and recall for detecting malignant tumors
