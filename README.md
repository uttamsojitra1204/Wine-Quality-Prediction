# Wine-Quality-Prediction

=> This project predicts the quality of wine (good or not good) using a Random Forest Classifier. The model is trained on the Wine Quality Dataset, which includes 1,599 samples with 11 features such as acidity, sugar content, and alcohol level.

=> Workflow

1. Data Preprocessing:
- The dataset is cleaned, with no missing values.
- The target variable, quality, is binarized: 1 for good quality (>=7), 0 otherwise.

2. Model Training:
- The data is split (80% training, 20% testing), and a Random Forest Classifier is trained.
- Accuracy: Train: 100%, Test: 94.37%

3. Prediction System:
- The model predicts wine quality based on input chemical properties.

4. Dependencies
- numpy, pandas, scikit-learn, matplotlib, seaborn

5. Usage
- Run the prediction system by providing input data for wine's chemical properties, and it will classify the wine as good or not good.

=> Results
- Training Accuracy: 100%
- Test Accuracy: 94.37%
