# 🎬 Netflix Watch Hours Prediction

## Project Overview

This project focuses on predicting **Netflix Watch Hours** using various Machine Learning regression algorithms. It follows a complete end-to-end Machine Learning workflow, from data preprocessing and feature engineering to model training and performance evaluation.

The workflow includes:

- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Outlier Detection
- Feature Engineering
- Data Preprocessing using Pipeline & ColumnTransformer
- Model Training and Evaluation
- Performance Comparison of Multiple Regression Models

---

# 📂 Dataset Features

The dataset contains information related to Netflix movies and TV shows, including:

- Show ID
- Title
- Release Type
- Genre
- Language
- Country
- Release Year
- Release Day
- Duration (Minutes)
- Number of Seasons
- Total Episodes
- Budget (Million USD)
- Marketing Spend (Million USD)
- Cast Popularity Score
- Director Popularity Score
- IMDb Rating
- Critic Score
- Trailer Views (Million)
- Social Media Mentions (Thousands)
- Subscription Plan Popularity

**Target Variable**

- Watch Hours (Million)

---

# 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# ⚙️ Machine Learning Workflow

## 1. Data Preprocessing

- Missing Value Imputation
- Numerical Feature Scaling
- Categorical Feature Encoding
- Pipeline Implementation
- ColumnTransformer Implementation

---

## 2. Exploratory Data Analysis (EDA)

- Dataset Overview
- Missing Value Analysis
- Statistical Summary
- Distribution Analysis
- Boxplots for Outlier Detection
- Correlation Heatmap
- Scatter Plots
- Feature Relationship Analysis

---

## 3. Feature Engineering

New features were created to improve model performance:

- Budget to Marketing Ratio
- Overall Popularity Score
- Episodes Per Season

---

## 4. Model Building

The following Machine Learning Regression models were trained and evaluated:

- Linear Regression
- Polynomial Regression
- Ridge Regression
- Lasso Regression
- Elastic Net Regression
- K-Nearest Neighbors (KNN) Regression

---

# 📊 Model Evaluation

Models were evaluated using the following regression metrics:

- R² Score
- Adjusted R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

# 📈 Results

The performance of all regression models was compared using the evaluation metrics above, and the best-performing model was selected for predicting Netflix Watch Hours.

---

# 📁 Project Structure

```text
Netflix-WatchHours-Prediction/
│
├── Dataset/
│   └── netflix_regression_capstone_dataset.csv
│
├── Notebook/
│   └── Netflix_ML_ProjectPipeline.ipynb
│
├── README.md
```

---

# ▶️ Run the Project

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open and run:

```text
Netflix_ML_ProjectPipeline.ipynb
```

---

# 👨‍💻 Author

**Dhruv Rapariya**

**Aspiring Data Scientist | Machine Learning Enthusiast | Data Analytics Learner**


---

⭐ **If you found this project helpful, consider giving it a Star!**
