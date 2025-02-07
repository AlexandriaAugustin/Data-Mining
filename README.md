# Data-Mining
Summary of Workflow 

1. Data Preparation 
The dataset was examined for structure and quality, with categorical variables such as 
City_Type and Education_Level converted to numeric formats to support modeling. 
Missing values were addressed, and numerical predictors were scaled where necessary to 
ensure compatibility with distance-based algorithms like k-NN. The data was partitioned 
into training and testing sets to evaluate model performance effectively.


2. Model Development 
k-Nearest Neighbors (k-NN): A k-NN model was developed to predict Product_Purchase 
using Age, Income, Spending_Score, and City_Type_Numeric. The model achieved 
modest accuracy (58.67%), indicating limitations due to unscaled features and class 
imbalance.

Linear Regression: A regression model was built to predict Income using Age, 
Spending_Score, and City_Type. The model demonstrated a strong fit (R-squared = 
89.66%) but had a Root Mean Squared Error (RMSE) of $5280.79, suggesting variability 
in predictions. 

Classification Tree: A decision tree was constructed to classify Product_Purchase using 
all predictors, achieving an 80% accuracy rate. The tree highlighted the importance of 
Income, Spending_Score, and Age in predicting purchase behavior. 


3. Key Findings 
Income and Spending Patterns: Income and Spending_Score emerged as critical 
predictors of purchasing behavior, indicating that customers with higher spending 
tendencies and incomes are more likely to make purchases. 
Age Relevance: Older individuals tended to have higher incomes, as reflected in the linear 
regression model. 
Model Limitations: Both the k-NN model and the classification tree struggled with class 
imbalance, leading to some misclassifications.

 
4. Actionable Insights and Recommendations 
Target High-Income and High-Spending Segments: Focus marketing efforts on 
individuals with higher incomes and spending scores, as they are more likely to purchase 
products. 
Refine Data for Better Modeling: Address class imbalance through oversampling or 
adjusting class weights in models to improve sensitivity to minority classes. 
Explore Additional Features: Incorporate other predictors like spending categories or 
customer demographics for enhanced model performance. 
Validate on New Data: Test the models on unseen data to confirm their generalizability 
and identify opportunities for improvement.

By leveraging these insights, businesses can optimize strategies to enhance customer 
targeting and product offerings, ultimately improving revenue and engagement. 
