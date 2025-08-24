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
Pairplot Analysis

<img width="1338" height="1231" alt="fifth" src="https://github.com/user-attachments/assets/ce86b475-01ab-4789-8404-871e9095c9d1" />

Comprehensive visualization showing relationships between all numerical variables in the dataset.

Age Distribution

<img width="558" height="428" alt="first" src="https://github.com/user-attachments/assets/08dac065-e24d-4033-bfb1-4a1c5d19990d" />

The distribution of user ages shows concentration in specific demographic groups.

Time Spent vs Age

<img width="593" height="590" alt="third" src="https://github.com/user-attachments/assets/9a2208b4-f182-4b02-8efc-4fa76c3059d4" />

Relationship between daily time spent on site and user age reveals interesting behavioral patterns.

Internet Usage vs Time Spent

<img width="593" height="590" alt="forth" src="https://github.com/user-attachments/assets/b4448ca8-78e4-4351-bc9a-cd290fc13f34" />

Correlation between general internet usage and site-specific engagement.

🧠 Model Performance

<img width="599" height="187" alt="Screenshot 2025-08-24 062306" src="https://github.com/user-attachments/assets/dec75f1d-9059-4898-9ae0-c328f930b1c3" />

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

The pairplot revealed interesting multidimensional relationships between features

The model effectively predicts ad clicks with 93% accuracy

👨‍💻 Author

[Omar Alshargawi]
