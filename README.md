# credit-card-fraud-detection
Credit card fraud detection and cost-based transaction review analysis using Python and Machine Learning

**Project Overview**

The project, completed by Team Lions for MSDS 530 - Fundamentals of Data Science at the University of the Cumberlands, explores how data science and machine learning can help identify potentially fraudulent credit card transactions and prioritize transactions for manual review. 

The project analyze synthetic 2026 credit card transactions data, examines fraud patterns, evaluates predictive modeling approaches, and compares the potential financial impact of different transactions review strategies. 

**Project Objectives** 
- Explore transactions characteristics and patterns associated with fraudulent activity.
- Analyze fraud trends across transactions hours, weekends, and months.
- Apply machine learning techniques to support fraud detection and transactions prioritizations.
- Evaluate model performance using appropriate metrics for an imbalanced classification problem.
- Compare a data-driven transactions review policy with a country-risk based rule.
- Estimate potential cost savings under specified review cost and fraud prevention assumptions.
- Identify limitations and considerations for real-world implementations.

 **Methodology** 
 The Project follows a data-driven analytical workflow:
 1. Data Preparation: Load and Prepare the transaction dataset for analysis.
 2. Exploratory data analysis: Examine transaction patterns and fraud related characteristics.
 3. Feature analysis: Investigate transaction attributes that may help distinguish fraudulent activity.
 4. Model Evaluation: Assess predictive performance using classification metrics, including precision recall analysis.
 5. Review policy comparison: Compare a model-risk approach with a country-risk rule.
 6. Cost-based evaluation: Estimate the financial impact of reviewing selected transactions under defined assumptions.
 7. Limitations and recommendations: Discuss the implications of the findings and the need for further validations.

**Key Findings**

The revised analysis estimates the following net savings under the project's assumptions

**Transaction review strategy** : Data-driven review policy, Country-risk rule 
**Estimated net savings**: $25,174, $11,056

These are estimates from synthetic data, not verified savings from a real financial institutions. The calculations assume a cost of 5$ per review and an 80% fraud-loss prevention rate. Actual results would depend on real-world transaction patterns, fraud prevalence, review costs, model performance, and operational effectiveness. 
**Tools and Technologies**
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Machine Learning and exploratory data analysis

**Installation** 
Install Python and the required libraries:
pip install pandas numpy scikit-learn matplotlib

**How to Run**
Ensure that the required dataset, credi_card_fraud_detection_2026.csv, is available in your working directory.

**Run the analysis script:**
python Team_Lions_Fraud_Analysis_Feedback_Revised.py credit_card_fraud_detecton_2026.csv
The script generates figures in a figures/directory and saves results to results.json. The full bootstrap analysis may take several minutes to complete.

You can also open fraud_review_full_analysis_Feedback_Revised.ipynb in jupyter Notebook to explore the analysis interactively. 

Dataset Note: The script and notebook require the CSV dataset is included in the repository and that its license and sharing permissions allow public distribution before publishing it.

**Limitations**
- The dataset is synthetic and may not represent actual credit card transaction behavior.
- Financial estimates depend on assumptions about review costs and fraud-loss prevention.
- Results from synthetic data do not establish performance on real-world banking transactions.
- Time-based patterns are descriptive and should not automatically be interpreted as casual relationships or evidence of seasonality.
- Real-world deployment would require additional validation, monitoring, privacy, safeguards, and operational testing.

**Conclusion**
This project demonstrates how exploratory data analysis, machine learning, and cost-based evaluation can support more informed credit card transaction review decisions. The findings illustrate the potential value of data-driven review prioritization while emphasizing that assumptions and model performance must be validated before applying the approach in a real financial environment.


**Academic Information**
**Team**: Lions
**Institution**: University of the Cumberlands
**Course**: MSDS 530 - Fundamentals of Data Science
**Project**: Credit Card Fraud Detection and Cost-Based Transaction Review Analysis

