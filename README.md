# Cancer_Prediction
Predict breast cancer diagnosis (benign or malignant) using Logistic Regression on features like radius, texture, and area. This project uses the Breast Cancer Wisconsin dataset with visual insights and model evaluation to show how simple ML can support early cancer detection.
🧬 Breast Cancer Prediction using Logistic Regression
📝 Project Description:
This project uses Logistic Regression to predict whether a breast tumor is benign (B) or malignant (M) based on various diagnostic features extracted from medical imaging. The goal is to provide a simple yet effective machine learning model for early cancer detection.

The dataset contains measurements of cell nucleus properties, such as radius, texture, perimeter, area, smoothness, and more — captured in both average and "worst" form.

🧠 Tech Stack:
Python

Scikit-learn – for Logistic Regression modeling

Pandas & NumPy – for data handling

Seaborn & Matplotlib – for data visualization

📊 Key Features Used:
radius_mean, texture_mean, area_mean, smoothness_mean

concavity_mean, compactness_mean, concave points_mean

radius_worst, area_worst, concavity_worst, etc.

🏷️ Target Variable:
diagnosis:

M – Malignant

B – Benign

🔁 Workflow:
Load and explore the dataset.

Drop the id column and encode the diagnosis column.

Perform exploratory data analysis (EDA).

Train a Logistic Regression model.

Evaluate model using accuracy, confusion matrix, and ROC curve.

Visualize important features and model performance.

🎯 Outcome:
The Logistic Regression model effectively classifies tumors as benign or malignant using diagnostic features. It provides a simple, interpretable, and reliable method for cancer prediction with high accuracy.

📈 Visual Insights:
Malignant tumors show significantly higher values for certain features.

The ROC curve shows strong performance for binary classification.

Logistic Regression is interpretable and performs well on this medical dataset.
