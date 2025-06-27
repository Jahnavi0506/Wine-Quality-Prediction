Wine Quality Prediction
This project predicts whether red wine is of good or bad quality using machine learning (Random Forest Classifier). The model is trained on physicochemical properties of wine to classify wine quality as either good (1) or bad (0).

📁 Dataset
The dataset used is the Red Wine Quality dataset, containing 1599 samples and 12 columns.

📌 Target Column: quality
Label Binarized:

0 → Bad Quality (quality < 7)

1 → Good Quality (quality ≥ 7)

📊 Features
fixed acidity

volatile acidity

citric acid

residual sugar

chlorides

free sulfur dioxide

total sulfur dioxide

density

pH

sulphates

alcohol

🧪 Libraries Used
numpy
pandas
matplotlib
seaborn
scikit-learn

🧠 Model Training
Model: RandomForestClassifier

Train-test split: 80% training / 20% testing

Accuracy: ~91.9%

📈 Visualizations
Distribution of wine quality

Feature vs quality (bar plots)

Heatmap of feature correlation
