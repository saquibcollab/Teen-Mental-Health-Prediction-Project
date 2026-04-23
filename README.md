# Teen-Mental-Health-Prediction-Project
This project provides an end-to-end analysis and predictive modeling of teen mental health based on the provided dataset. The objective is to identify key factors contributing to depression and build a model to predict potential mental health risks.
Key Insights from EDA
Social Media Impact: A positive correlation exists between high social media usage and increased anxiety/stress levels.

Sleep Quality: Lower sleep hours are significantly associated with higher depression markers.

Academic Pressure: Lower academic performance often correlates with higher stress levels.

🤖 Model Performance
We implemented a Random Forest Classifier with balanced class weights to address the data imbalance.

Accuracy: ~98.7%

Top Predictors: Stress Level, Anxiety Level, Addiction Level, and Academic Performance.

🛠️ Tech Stack
Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

📂 File Structure
Teen_Mental_Health_Dataset.csv: Raw data.

analysis_code.py: Full project script (EDA + Modeling).

README.md: Project documentation.

feature_importance.png: Visualizing key drivers of the model.

Disclaimer: This project is for educational purposes and should not be used as a clinical diagnostic tool.
"""

Write to file
with open('README.md', 'w') as f:
f.write(readme_content)

print("README.md has been created successfully.")

Your GitHub **README.md** file has been generated. This file provides a professional overview of the project, details the dataset, and summarizes the machine learning findings.

[file-tag: code-generated-file-0-1776955055502123014]

### Recommended Repository Structure
To make your GitHub repository look complete, I suggest organizing your files as follows:

1.  **`README.md`**: The file provided above.
2.  **`main.py`**: Contains the full end-to-end code (Data Loading, EDA, and Modeling).
3.  **`Teen_Mental_Health_Dataset.csv`**: Your raw data file.
4.  **`plots/`**: A folder containing the saved visualizations (Correlation Heatmap, Feature Importance, etc.).
5.  **`.gitignore`**: A file to prevent uploading temporary files (like `__pycache__` or `.DS_Store`).

### How to use the generated README:
* Download the file above.
* Upload it to the root directory of your GitHub repository.
* Update the `git clone` URL in the "Installation" section with your actual re
