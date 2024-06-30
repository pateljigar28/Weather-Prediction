🌦️ Weather Prediction using Machine Learning

📄 Description:

This project leverages machine learning algorithms to predict weather conditions based on historical weather data from Seattle. The goal is to forecast various weather types using features such as precipitation, temperature, and wind.

✨ Features:

🔄 Data Preprocessing: Includes handling missing values, encoding categorical labels, normalizing data, and selecting relevant features.

🧠 Model Training: Employs the XGBoost classifier to build a predictive model based on the processed dataset.

🔍 Hyperparameter Tuning: Utilizes GridSearchCV to optimize the model's hyperparameters for better performance.

📊 Model Evaluation: Provides detailed accuracy scores and classification reports to evaluate the effectiveness of the trained model.



🛠️ Technologies:
This project is built using the following technologies:

🐍 Python: The primary programming language used for development.

📊 Pandas: A library for data manipulation and analysis.

🔢 NumPy: A library for numerical computations.

🔬 Scikit-learn: A machine learning library used for preprocessing, model training, and evaluation.

🚀 XGBoost: A powerful and efficient implementation of the gradient boosting algorithm.







📝 Steps and Explanation:

📥 Load the Dataset: The dataset is loaded into a DataFrame to begin the preprocessing steps.

🔠 Label Encoding: Categorical labels, specifically the weather types, are converted to numerical values for the model.

📏 Normalization: Numerical features such as precipitation, temperature, and wind are normalized to bring them to a common scale.

✂️ Feature Selection: Irrelevant features like the date are removed, and the dataset is split into features (X) and target (y).

🔀 Train-Test Split: The dataset is divided into training and testing sets to evaluate the model's performance on unseen data.

🏋️ Model Training: The XGBoost classifier is trained on the training set to learn patterns and make predictions.

🧾 Model Evaluation: The trained model is evaluated using the test set, providing accuracy scores and classification reports to measure its performance.

⚙️ Hyperparameter Tuning: GridSearchCV is employed to explore different hyperparameter combinations and find the best settings for the model.
