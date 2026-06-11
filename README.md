# FUTURE_ML_02
Update README.md
🎫 Customer Support Ticket Classification & Priority Prediction 

📌 Project Overview
This project is an NLP-based Machine Learning system that automatically analyzes customer support tickets and predicts:
•	Ticket Category
o	Billing
o	Technical Issue
o	Account
o	General Query
•	Priority Level
o	High
o	Medium
o	Low
The goal is to help organizations automate ticket triaging, reduce response times, improve customer satisfaction, and streamline support operations.
________________________________________
🚀 Features
✅ Automatic ticket categorization
✅ Automatic priority prediction
✅ Text preprocessing and feature extraction using TF-IDF
✅ Machine Learning classification models
✅ Model performance evaluation
✅ Interactive prediction for new support tickets
✅ Model saving and loading using Joblib
________________________________________
🛠️ Technologies Used
•	Python
•	Pandas
•	NumPy
•	Scikit-learn
•	Matplotlib
•	Joblib
•	Jupyter Notebook
________________________________________
📂 Dataset
The dataset contains customer support tickets with the following fields:
Column	Description
ticket_text	Customer support request
category	Ticket category
priority	Priority level
Example:
ticket_text	category	priority
Charged twice for subscription	Billing	High
Unable to login to account	Account	Medium
Application crashes on startup	Technical Issue	High
________________________________________
🔄 Project Workflow
1. Data Collection
Support ticket data is collected and stored in CSV format.
2. Data Preprocessing
•	Missing value handling
•	Text cleaning
•	Lowercasing
•	Stop-word removal
3. Feature Engineering
TF-IDF Vectorization is used to convert textual ticket descriptions into numerical feature vectors.
4. Model Training
Two separate Machine Learning models are trained:
Category Classification Model
Predicts:
•	Billing
•	Technical Issue
•	Account
•	General Query
Priority Classification Model
Predicts:
•	High
•	Medium
•	Low
5. Model Evaluation
Models are evaluated using:
•	Accuracy
•	Precision
•	Recall
•	F1 Score
•	Confusion Matrix
6. Prediction
The system predicts category and priority for unseen support tickets.
________________________________________
📊 Exploratory Data Analysis
The following visualizations were created:
•	Category Distribution
•	Priority Distribution
•	Confusion Matrix
•	Model Performance Metrics
________________________________________
📈 Results
Category Classification
Metric	Score
Accuracy	XX%
Priority Prediction
Metric	Score
Accuracy	XX%
Replace the above values with your actual results after training.
________________________________________
🧠 Machine Learning Models
The following algorithms were explored:
•	Logistic Regression
•	Linear Support Vector Classifier (Optional)
•	Random Forest Classifier (Optional)
The best-performing model was selected based on evaluation metrics.
________________________________________
📁 Project Structure
Customer-Support-Ticket-Classification/

│
├── tickets.csv
├── Customer_Support_Ticket_Classification.ipynb
├── category_model.pkl
├── priority_model.pkl
├── vectorizer.pkl
├── README.md
│
└── outputs/
    ├── category_distribution.png
    ├── priority_distribution.png
    └── confusion_matrix.png
________________________________________
▶️ How to Run
Clone This Repository
Install Dependencies
pip install pandas numpy scikit-learn matplotlib joblib
Open Jupyter Notebook
jupyter notebook
Run all cells in:
Customer_Support_Ticket_Classification.ipynb
________________________________________
📝 Example Prediction
Input Ticket
My payment was deducted twice and I need an urgent refund.
Output
Category: Billing
Priority: High
________________________________________
🎯 Future Improvements
•	Deep Learning using LSTM/BERT
•	Streamlit Web Application
•	Real-time Ticket Processing
•	Multi-label Classification
•	Cloud Deployment
________________________________________
📚 Learning Outcomes
Through this project, I learned:
•	Natural Language Processing (NLP)
•	Text Vectorization using TF-IDF
•	Machine Learning Classification
•	Model Evaluation Techniques
•	Data Visualization
•	End-to-End ML Project Development
________________________________________
👨‍💻 Author
Madiraju Himaja Sripriya
Machine Learning Intern Project – Future Interns 2026

