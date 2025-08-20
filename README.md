Global Terrorism Database (GTD) Analysis
📌 Project Overview

This project analyzes the Global Terrorism Database (GTD) to uncover trends, patterns, and predictive insights related to global terrorist activities. The objective is two-fold:

Exploratory Data Analysis (EDA): Understand the scale, distribution, and attributes of terrorist incidents across time, geography, and categories.

Machine Learning Models: Build classification models to predict and classify terrorism-related attributes using supervised learning algorithms.

The findings from this project are valuable for policy makers, security agencies, and researchers in understanding terrorism dynamics.

🛠️ Tech Stack

Languages & Libraries:

Python, Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn (DecisionTree, RandomForest, KNN, SGDClassifier, Pipelines, Metrics)

Dataset:

Global Terrorism Database (GTD)

File used: globalterrorismdb_0718dist.csv

🔍 Methodology
1. Data Preprocessing

Imported dataset with ~200,000+ records and 130+ attributes.

Checked duplicates and missing values.

Assessed variable completeness (retained features with ≥95% completeness).

Handled categorical & numerical attributes for downstream analysis.

2. Exploratory Data Analysis (EDA)

Distribution of terrorist incidents across years and regions.

Most affected countries and cities.

Weapon types and attack methods.

Casualty analysis and damage intensity.

3. Machine Learning Models

Decision Tree Classifier

Random Forest Classifier

K-Nearest Neighbors (KNN)

SGD Classifier (Linear models)

Pipelines for scaling + model fitting.

Evaluation metrics used:

Accuracy Score

F1 Score

ROC-AUC Curve & Report

📊 Key Insights (Example)

Terrorism incidents peaked between 2012–2015, largely concentrated in Middle Eastern and South Asian regions.

IEDs (Improvised Explosive Devices) were the most common weapon category.

Iraq, Afghanistan, and Pakistan recorded the highest incidents historically.

Ensemble models (Random Forest) achieved better predictive accuracy compared to individual classifiers.

🚀 How to Run the Project

Clone this repository:

git clone <repo_link>
cd GTD-Analysis


Install dependencies:

pip install -r requirements.txt


Run Jupyter Notebook:

jupyter notebook "GTD Analysis final.ipynb"


Ensure the dataset globalterrorismdb_0718dist.csv is placed in the working directory.

📂 Project Structure
📁 GTD-Analysis
│── GTD Analysis final.ipynb   # Main notebook
│── globalterrorismdb_0718dist.csv   # Dataset (not included in repo due to size)
│── README.md                  # Project documentation
│── requirements.txt           # Python dependencies

📌 Future Work

Build deep learning models (LSTMs) for temporal terrorism trend forecasting.

Integrate with interactive dashboards (Plotly/Dash/Streamlit).

Apply clustering techniques to identify new emerging terrorism hotspots.
