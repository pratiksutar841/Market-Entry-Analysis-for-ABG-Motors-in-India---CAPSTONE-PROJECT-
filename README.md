🚗 Market Entry Analysis for ABG Motors – Capstone Project
📌 Project Objective

To determine whether ABG Motors, a Japanese automobile manufacturer, should enter the Indian market by leveraging data-driven decision-making. This involves building a classification model using Japanese market data to predict potential Indian customers and evaluating profitability against a sales target of 12,000 cars/year.

🧠 Problem Statement

ABG Motors is exploring expansion opportunities in India, assuming customer behavior may be similar to Japan.
You are tasked to:

Analyze sample customer data from Japan (training data) and India (prediction data).

Build a machine learning classification model to estimate purchase likelihood.

Identify the number of potential Indian customers and compare it against the 12,000-car sales benchmark.

Provide business recommendations backed by predictive analytics and visualization insights.

📂 Project Structure
📁 ABG-Market-Entry-Analysis
│── ABG_Market_Entry_Analysis.ipynb          # Jupyter Notebook with full workflow
│── cleaned_japanese.csv                     # Cleaned Japanese dataset
│── cleaned_indian_with_predictions.csv      # Indian dataset with prediction results
│── ABG_Market_Entry_Report.docx              # Detailed project report
│── /Tableau_Charts/                          # Tableau visualizations (PNG/Screenshots)
│── README.md                                 # Project documentation

🛠️ Tools & Technologies

Programming & Libraries: Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib

Data Visualization: Tableau

Environment: Google Colab, Jupyter Notebook

Version Control: Git & GitHub

📊 Methodology

Data Understanding & Cleaning

Loaded Japanese & Indian datasets

Checked for missing values, duplicates, outliers

Encoded categorical variables and scaled numerical features

Exploratory Data Analysis (EDA)

Demographic patterns of buyers vs. non-buyers

Correlation between age, income, marital status, and purchase decision

Visual comparisons of Japan vs. India

Model Building

Algorithm: Logistic Regression (due to interpretability)

Train-test split: 70% training, 30% testing

Evaluated metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

Prediction on Indian Dataset

Applied trained Japanese model to Indian customers

Counted predicted buyers and compared with 12,000 sales target

Visualization in Tableau

Age vs. Purchase Likelihood

Income Distribution of Buyers

Country-wise Sales Potential Comparison

📈 Key Results

Predicted Indian Buyers: 13,285 customers/year

Target Sales: 12,000 cars/year

Recommendation: ✅ Proceed with Market Entry

Model Performance on Japanese Data:

Accuracy: 85%

Precision: 83%

Recall: 81%

F1-score: 82%

ROC-AUC: 0.90

📌 Business Insights

Income is the strongest predictor of car purchase likelihood.

Married customers in the 30–50 age range show the highest buying intent.

Similar purchasing behavior patterns between Japan and India validate market similarity assumption.

Sales potential exceeds the break-even benchmark by 10.7%.

📷 Tableau Visualizations

Customer segmentation by age group & income

Comparative sales potential in Japan vs. India

Purchase likelihood distribution

📁 See folder: /Tableau_Charts

✅ Final Recommendation

Based on predictive modeling and market similarity, ABG Motors should enter the Indian market, targeting middle-aged, higher-income customers through tailored marketing campaigns.

🙋‍♂️ Author

Pratik Prashant Sutar
B.Tech in Computer Science & Engineering (Data Science)
GitHub: pratiksutar841
LinkedIn: https://www.linkedin.com/in/pratik-sutar-?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BHT6XOi20Q92S4xHr%2BbKKIw%3D%3D
