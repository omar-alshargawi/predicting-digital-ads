Ad Click Prediction using Logistic Regression
📊 Project Overview
This project focuses on building a machine learning model to predict whether an internet user will click on a digital advertisement based on their demographic and behavioral characteristics. Using logistic regression, we analyze various features to determine their impact on ad click behavior.

🔍 Dataset Features
The dataset contains the following features:

Daily Time Spent on Site: Consumer time on site in minutes

Age: Customer age in years

Area Income: Average income of geographical area

Daily Internet Usage: Average minutes per day on internet

Ad Topic Line: Headline of the advertisement

City: City of consumer

Male: Whether consumer was male (binary)

Country: Country of consumer

Timestamp: Time when consumer clicked ad or closed window

Clicked on Ad: Target variable (0 = no click, 1 = clicked)

📈 Exploratory Data Analysis
Age Distribution
https://images/age_distribution.png
The distribution of user ages shows concentration in specific demographic groups.

Time Spent vs Age
https://images/time_vs_age.png
Relationship between daily time spent on site and user age reveals interesting behavioral patterns.

Internet Usage vs Time Spent
https://images/usage_vs_time.png
Correlation between general internet usage and site-specific engagement.

🧠 Model Performance
https://images/model_performance.png
The logistic regression model achieved 93% accuracy with strong precision and recall scores across both classes.

🛠️ Technical Implementation
Data Preprocessing: Handling missing values, feature engineering from timestamp

Feature Selection: Identifying relevant predictors for ad clicking behavior

Model Training: Logistic regression with scikit-learn

Evaluation Metrics: Precision, recall, F1-score, and accuracy

💡 Key Insights
Younger users tend to spend more time on site but don't necessarily click more ads

Time-based features extracted from timestamp improved model performance

Daily internet usage and time on site show strong correlation

The model effectively predicts ad clicks with 93% accuracy

👨‍💻 Author
[Omar Alshargawi]

LinkedIn Profile

GitHub Profile
