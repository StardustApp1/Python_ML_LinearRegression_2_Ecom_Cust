# Python_ML_LinearRegression_2_Ecom_Cust
Exploratory Data Analysis for Ecommerce Customer

Ecommerce Customers
The Ecommerce Customers dataset contains details about customer interactions with an online business, including their website and app usage, session lengths, membership durations, and yearly spending habits. The goal of the analysis was to understand the key factors influencing customer spending and develop a predictive model.

Initially, Exploratory Data Analysis (EDA) revealed strong correlations between certain variables. Notably, customers who spent more time using the mobile app were found to have higher yearly spending, while time spent on the website showed a weaker correlation. Additionally, Length of Membership appeared to be the most significant predictor of customer spending, indicating that loyal customers tend to spend more over time.

To quantify these relationships, a Linear Regression Model was built using features such as Average Session Length, Time on App, Time on Website, and Length of Membership. The model successfully predicted Yearly Amount Spent with high accuracy, as evident from the R² score and residual analysis. The regression coefficients confirmed that Time on App and Length of Membership were the most influential factors, reinforcing the importance of a well-optimized mobile experience and long-term customer retention strategies.

The insights derived suggest that businesses should invest more in app development and customer loyalty programs to drive higher revenue. The presence of normally distributed residuals further validates the model’s reliability in predicting customer spending behavior.
