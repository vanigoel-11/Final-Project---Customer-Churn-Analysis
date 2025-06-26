# Final-Project---Customer-Churn-Analysis
📌 Objective
Predict customer churn and derive actionable strategies to retain users in a highly competitive telecom environment.

🛠️ Tools & Technologies
Python (Scikit-learn, XGBoost, SHAP)
SQL for data aggregation
Google Colab for development and experimentation
Matplotlib / Seaborn for visualization

📊 Dataset Overview
The dataset includes customer demographics, service usage, billing information, and churn labels. Key features:
Tenure
Monthly Charges
Contract Type
Customer Support Interactions

🧠 Modeling Approach
Binary classification problem
Models used: Decision Tree, Random Forest, XGBoost
SMOTE used to address class imbalance
Evaluated with accuracy, confusion matrix, and classification report

🔍 Model Explainability
SHAP was used to interpret model predictions. Key churn drivers identified:
Contract Type (especially month-to-month)
Tenure
Monthly Charges
Customer Support Interactions

👥 Customer Segmentation
At Risk: High churn probability
Loyal: Long tenure, low churn risk
Dormant: Low usage or engagement
Segmentation supports focused retention strategies.

✅ Final Recommendations
Engage at-risk users with personalized retention offers
Implement loyalty rewards for long-term customers
Address frequent complaint categories to reduce dissatisfaction
Reactivate dormant users via targeted campaigns
Monitor key churn indicators and retrain models as needed

📁 Deliverables
Google Colab Notebook (CustomerChurnProject.ipynb)
PowerPoint Report (visual insights & model summary)
Summary & Recommendations Document

🚀 How to Run (on Google Colab)
Upload the notebook to Google Colab
Mount Google Drive if using external files
Run all cells in sequence
Install any required packages using !pip install commands
