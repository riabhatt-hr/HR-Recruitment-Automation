HR Recruitment Analytics and Hiring Prediction
This repository demonstrates the application of predictive modeling within the recruitment lifecycle. The project aims to streamline the hiring process by identifying the most promising candidates based on multi-dimensional scoring, including technical skills and personality assessments.

Project Files
4 (1).ipynb: The main Jupyter Notebook detailing the data pipeline, model training using classification algorithms, and business impact quantification.

4 (1).csv: The recruitment dataset containing candidate profiles, including age, gender, education level, experience, and various evaluation scores.

4 (1).png / 4 (2).png: Data visualizations including feature correlation heatmaps and model performance charts.

Core Objectives
Automated Screening: Developing a classification model to predict the "Hiring Decision" based on candidate attributes.

Feature Analysis: Evaluating the weight of different factors like Interview Scores, Skill Scores, and Personality Scores in the final decision-making process.

Efficiency Gains: Calculating the potential reduction in manual HR workload through AI-assisted screening.

Model Deployment Readiness: Exporting the trained model as a serialized file for integration into HR software solutions.

Technical Implementation
Preprocessing: Encoding categorical variables such as Education Level and Recruitment Strategy.

Algorithm: Implementation of a classification model (e.g., Random Forest or Gradient Boosting) to handle non-linear relationships in recruitment data.

Performance Metrics: Analysis of precision and recall to ensure high-quality hiring recommendations.

Business Logic: An integrated impact analysis showing a projected 80% reduction in manual screening time, translating to approximately 200 hours saved per recruitment cycle.

How to Run
Prerequisites:
Install the necessary Python packages:

Bash
pip install pandas matplotlib seaborn scikit-learn joblib
Execution:
Run the 4 (1).ipynb notebook. The script will load the data, generate visualizations, train the model, and export the final version as hr_recruitment_model.pkl.

Project Impact
By implementing this model, HR departments can focus their energy on high-potential candidates identified by the "Digital Auditor," ensuring a faster and more data-driven talent acquisition process.
