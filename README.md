![ecom_delivery](https://github.com/user-attachments/assets/83657d91-16a6-492c-914e-4b05e249e6a1)

# E-Commerce-Product-Delivery-Prediction
This project aims to predict whether an e-commerce product would be delivered on time or not. Alongside building the prediction model, the project also explored various factors influencing delivery performance and provided insights into customer behavior.

# Context
The company, specializing in electronic products, seeks insights from its customer database to optimize delivery performance and enhance customer satisfaction.
# Data Description
The dataset comprises 10999 observations across 12 variables, detailing customer interactions, product characteristics, and delivery outcomes. Key variables include:

- Warehouse block
  
- Mode of shipment
  
- Customer care calls
  
- Customer rating
  
- Cost of the Product
  
- Prior purchases
  
- Product importance
  
- Gender
  
- Discount Offered
  
- Weight in gms
  
- Reached on Time_Y.N (target variable)

# Key Steps
Data Preprocessing: Cleaned and prepared data, handling missing values, duplicates, and irrelevant columns.

Exploratory Data Analysis (EDA): Investigated distribution of variables, customer behavior, and logistics factors using visualizations.

Feature Engineering: Transformed categorical variables using label encoding.

Model Building: Deployed machine learning models like Random Forest, Decision Tree, Logistic Regression, and KNN to predict delivery outcomes.

Model Evaluation: Assessed models based on accuracy, confusion matrix, and classification reports.

# Key Insight
From the exploratory data analysis, it was observed that product weight and cost play a significant role in delivery outcomes. Products weighing between 2,500–3,500 grams and priced below $250 were more likely to arrive on time. Additionally, most products were shipped from Warehouse F by sea, suggesting that this warehouse might be located close to a seaport.
Customer behavior also emerged as an important factor in delivery performance. Frequent customer care calls were associated with delayed deliveries, whereas customers with a history of multiple prior purchases tended to experience more timely deliveries—likely reflecting stronger trust and loyalty toward the company.

# Models Performance
For the machine learning models, the Decision Tree Classifier achieved the highest accuracy at 69%. The Random Forest Classifier and Logistic Regression followed closely with accuracies of 68% and 67%, respectively, while the K-Nearest Neighbors (KNN) model had the lowest performance at 65%.

