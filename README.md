Comprehensive Analysis of Stroke Risk Factors

📌 Project Overview

This project is a Comprehensive Analysis of Stroke Risk Factors, aimed at identifying and evaluating the key variables affecting stroke risk. Using data-driven methodologies, this project incorporates exploratory data analysis, visualization, and machine learning models to extract meaningful insights and predict stroke probability with high accuracy.

📊 Key Features

-In-depth exploratory data analysis (EDA) with visualizations 📈
-Data preprocessing (handling missing values, feature engineering, normalization) 🛠
-Advanced Machine Learning models (Logistic Regression, Decision Trees, Random Forest, SVM, XGBoost) 🤖
-Model evaluation & performance metrics (AUC-ROC, precision-recall, feature importance) 📊
-Comprehensive report and presentation summarizing findings 📜
📂 Project Structure

Comprehensive-Analysis-of-Stroke-Risk-Factors/
```
├── Comprehensive_Analysis_of_Stroke_Risk_Factors/
│   ├── MervePakcan_code.ipynb      # Jupyter Notebook with full analysis
│   ├── MervePakcan_data.csv        # Dataset used in the project
│   ├── MervePakcan_presentation.pdf # Project presentation slides
│   ├── MervePakcan_report.pdf      # Final project report
│   └── README.md                   # This documentation file
```
🚀 Getting Started

🔧 Prerequisites

Ensure your system meets the following requirements:

Python 3.9+ (Recommended for compatibility and performance)
Jupyter Notebook (For running the analysis)
Required Python libraries: pandas, numpy, matplotlib, seaborn, sklearn
📥 Installation

Clone this repository:

git clone https://github.com/mervepakcan/Comprehensive-Analysis-of-Stroke-Risk-Factors.git
Navigate to the project directory:

cd Comprehensive-Analysis-of-Stroke-Risk-Factors
Install dependencies:

pip install -r requirements.txt
Note: If requirements.txt is missing, you can manually install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn
🏃‍♀️ Usage

Run the Jupyter Notebook to execute the analysis:

jupyter notebook MervePakcan_code.ipynb
This will open the Jupyter Notebook interface where you can execute cells step by step.

🔍 Exploratory Data Analysis (EDA)

Exploratory Data Analysis is a crucial step in understanding the dataset and uncovering patterns before applying machine learning models. In this project, we have applied various EDA techniques, including:

Feature Distribution Analysis: Histograms and box plots were used to visualize the spread of continuous variables and detect outliers.
Correlation Heatmaps: A heatmap was generated to analyze the relationships between different variables and identify potential dependencies.
Missing Data Handling: Strategies such as mean/median imputation and categorical encoding were used to handle missing values.
Outlier Detection: We employed statistical techniques such as the IQR method and Z-score analysis to detect anomalies in the dataset.
Feature Engineering: New features were derived based on domain knowledge to improve model performance.
🤖 Machine Learning Models & Evaluation

After preprocessing the data, multiple machine learning models were implemented to predict stroke risk. The following models were used:

Logistic Regression: A simple yet effective baseline model for stroke prediction, used to evaluate the significance of each feature.
Decision Trees: A model that helps identify the most important factors contributing to stroke risk by constructing interpretable decision rules.
Random Forest: An ensemble method that improves prediction accuracy by combining multiple decision trees and reducing overfitting.
Support Vector Machines (SVM): Tested for classification performance in high-dimensional spaces.
XGBoost: A powerful gradient boosting technique to enhance model accuracy and generalization.
🏆 Model Performance Metrics

AUC-ROC Curve: Used to measure the model’s ability to distinguish between stroke-positive and stroke-negative cases.
Precision-Recall Analysis: Evaluated to balance the trade-off between false positives and false negatives.
Confusion Matrix: A breakdown of model predictions to assess classification accuracy and error distribution.
Feature Importance Analysis: Understanding which features contribute the most to model predictions.
🤝 Contributing

Want to contribute? Follow these steps:

Fork the repository
Create a new feature branch:
git checkout -b feature-new-analysis
Commit and push your changes:
git commit -m "Added new analysis on feature importance"
git push origin feature-new-analysis
Submit a Pull Request (PR) for review 🚀
📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

🎉 Acknowledgments

Special thanks to:

Open-source datasets & researchers 📊
Machine learning community & contributors 👏
Feedback from domain experts & reviewers 🤝
✨ If you find this project useful, don't forget to give it a star ⭐ on GitHub! ✨
