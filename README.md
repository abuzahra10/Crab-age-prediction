🦀 Crab Age Prediction using Huber Regressor

This repository contains a solution for the Crab Age Prediction Challenge, where the task is to predict the age of crabs based on various physical and biological features using regression techniques. This implementation uses Huber Regressor combined with polynomial features and standardization to ensure robustness and improved generalization.

📌 Problem Statement

Predict the age of crabs from their biological measurements using machine learning. The goal is to build a regression model that minimizes prediction error, specifically Mean Absolute Error (MAE).

🧠 Approach

✅ Data Preprocessing

One-hot encoding was applied to the Sex categorical feature.

Columns were reordered to group similar features.

Visualizations:

Histograms and KDE plots to explore distributions.

Box plots to identify outliers.

Scatter plots of each predictor vs. the target (Age).

Correlation heatmap for feature relationship analysis.

✅ Feature Engineering

Standardized features using StandardScaler.

Applied polynomial transformation (degree=3) to capture non-linear relationships.

✅ Model

Used Huber Regressor, a robust linear model that is resistant to outliers.

Trained on the polynomial-transformed feature set.

Evaluated on a hold-out validation set using the following metrics:

Mean Squared Error (MSE)

R² Score

Mean Absolute Error (MAE)

📊 Evaluation

Mean Squared Error: <your_value_here>
R² Score: <your_value_here>
Mean Absolute Error: <your_value_here>

Replace <your_value_here> with actual results from your run.

🔧 Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

🚀 How to Run

Clone the repo:

git clone https://github.com/your-username/crab-age-prediction.git
cd crab-age-prediction

Install dependencies:

pip install -r requirements.txt

Place the dataset files train.csv and test.csv in the root directory.

Run the script:

python crab_age_prediction.py

📁 Files

train.csv – Labeled training data

test.csv – Unlabeled test data

crab_age_prediction.py – Main script containing data prep, modeling, and evaluation

README.md – You are here 🚀

📌 Regularization Insight

The Huber Regressor was chosen for its robustness to outliers by combining the advantages of squared and absolute loss. It also includes an internal regularization parameter (alpha) that prevents overfitting and helps the model generalize better.

📬 Contact

For feedback or suggestions, feel free to open an issue or reach out via GitHub.

