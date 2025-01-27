# House-Price-Predicition
Lagos House Price Prediction Using Machine Learning

This project focused on predicting house prices in Lagos using machine learning techniques. The process began with data collection, sourcing the Lagos housing dataset from Kaggle.
![rent](https://github.com/user-attachments/assets/af28bf37-8426-4c56-b821-2c4acbd8508d)

Once the data was obtained, it underwent preprocessing to ensure its readiness for analysis. During this stage, the data was cleaned by addressing outliers, handling duplicate entries, and managing null fields.

Following preprocessing, exploratory data analysis (EDA) was conducted to gain deeper insights into the dataset. This phase revealed key information, such as the highest and lowest house rents in Lagos and their distribution patterns, providing a clearer understanding of the underlying trends.

![neigh](https://github.com/user-attachments/assets/1fed6cb0-98b1-489b-8608-8769b67eab46)
![neigh count](https://github.com/user-attachments/assets/7326cc7e-1d9c-4084-82ed-22188bd8d6a9)
![pie](https://github.com/user-attachments/assets/97eef7a4-c63f-44a2-973e-f6e504373d37)

After the analysis, the data was split into training and testing sets to prepare it for prediction. Several machine learning models were considered for this task, including:

Linear Regression
LightGBM
Decision Trees
Random Forest
Gradient Boosting
The performance of each model was evaluated, and the results were as follows:

Comparison of the training model

![comparison](https://github.com/user-attachments/assets/14061712-0418-4f0f-a34b-8b320b691335)

Linear Regression: 73.31
Random Forest: 71.62
Gradient Boosting: 68.76
Decision Tree: 67.82
LightGBM: 65.17

Compariosn of the testing model

![comparion for testing](https://github.com/user-attachments/assets/2a64709c-6ff7-49d2-8e23-1ea64155580c)

Linear Regression emerged as the best-performing model with a score of 73.31, making it the optimal choice for predicting house prices in Lagos.









