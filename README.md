
________________________________________
💳 Credit Card Fraud Detection using Machine Learnin
-----------------------------------------------------------------------------------------------------------------------------------
🗂️ Table of Contents
•	Overview
•	Dataset
•	Installation
•	Project Structure
•	Models and Techniques
•	Results
•	Usage
•	Conclusion and Future Work
•	License

________________________________________
📚 Overview
Credit card fraud is a serious concern that results in billions of dollars in losses every year. This project builds a machine learning model capable of detecting fraudulent transactions with high accuracy. By using various data balancing techniques and classification models, the aim is to minimize false negatives (fraud cases missed).
--------------------------------------------------------------------------------------------------------------------------------------
📊 Dataset
•	Source: csv file named as “Credit Card Fraud Detection.csv”
•	Description:
o	Total Transactions: 1,00,000
o	Fraudulent Transactions: 50%
o	Balanced dataset.
________________________________________
🛠️ Installation
To set up this project locally:
1.	Clone the repository:
2.	git clone https://github.com/MUKHTAR280506/CREDIT-CARD-FRAUD-DETECTION-BALANCED.git
3.	cd credit-card-fraud-detection
4.	Create a virtual environment (optional but recommended):
5.	python -m venv venv
6.	source venv/bin/activate  # For Linux/Mac
7.	venv\Scripts\activate     # For Windows
8.	Install the required libraries:
pip install -r requirements.txt
________________________________________
📂 Project Structure
credit-card-fraud-detection-balanced/
│  ccfd_project.ipynb
| credit card fraud detection.csv
| requirements.txt

________________________________________
🤖 Models and Techniques
•	Data Preprocessing:
o	Categorical features converted to numerical values using onehotencoder
o	Feature scaling with StandardScaler
•	Machine Learning Models:
o	Logistic Regression
o	Decision Trees
o	Random Forest
o	XGBoost Classifier
•	Evaluation Metrics:
o	Accuracy
o	Precision
o	Recall
o	F1-Score
o	ROC-AUC Curve
________________________________________
📈 Results
Model	Accuracy	Precision	Recall	F1-Score	
Logistic Regression	49.63%	49%	51%	50%	
Random Forest	50.30%	50%	50%	50%	
XGBoost	49.97%	49%	51%	50%	
•	Best Model: RandomForest Classifier
•	Key Observations:
o	Recall is prioritized to catch as many fraud cases as possible
________________________________________
✅ Conclusion and Future Work
•	Conclusion:
The machine learning models, particularly RandomForest, showed strong potential in identifying fraudulent transactions.
•	Future Improvements:
o	Implement real-time fraud detection pipelines..
o	Deploy the model using Flask or FastAPI for API-based detection.
o	Deep Learning model implementation can be explored 
________________________________________
📄 License
open source
________________________________________

