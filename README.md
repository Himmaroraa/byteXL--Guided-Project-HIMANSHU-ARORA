Airline Passenger Referral Prediction- A Comprehensive Project Description

Project Summary
This project aims to develop a classification model to predict whether airline passengers will recommend the airline to their friends. The project involves data loading, exploratory data analysis (EDA), feature engineering, data cleaning, target encoding, feature selection, model building, hyperparameter tuning, and model evaluation. Various classification models are used, including Logistic Regression, Random Forest, Naïve Bayes, Decision Tree, Support Vector Machine, and K-Nearest Neighbour. The models are evaluated based on recall, accuracy, and ROC AUC. The project identifies the most important features for prediction and concludes with recommendations for airlines to improve customer satisfaction and increase referrals.

Problem Description

The problem addressed in this project is predicting whether an airline passenger will recommend the airline to their friends. The prediction is based on passenger reviews and feedback, which include various factors such as overall rating, value for money, cabin service, ground handling, food and beverages, and seating comfort. Accurately predicting passenger 
referrals is crucial for airlines to identify influential passengers and implement strategies to enhance customer satisfaction and drive revenue growth.

1. Introduction
The airline industry is highly competitive, and customer satisfaction plays a vital role in an airline's success. Passengers' recommendations and referrals significantly influence potential customers' decisions. Therefore, understanding the factors that drive passenger referrals is essential for airlines to improve their services and gain a competitive edge. This project utilizes machine learning techniques to analyze passenger reviews and develop a predictive model to identify potential referrers.

2. Project Description
   
The project follows a structured approach to building and evaluating classification models for passenger referral prediction. The key steps involved are as follows:
1. Data Collection: Collect data from customer reviews and airline websites.
2. Data Understanding: Explore the data to understand the distribution of variables, identify missing values, and detect potential outliers.
3. Data Cleaning: Handle missing data, address data inconsistencies, and remove irrelevant features.
4. Feature Engineering: Extract relevant information from the raw data and create new features to improve model performance.
5. Target Encoding: Transform categorical variables into numerical representations suitable for machine learning models.
6. Feature Selection: Identify the most important features that significantly impact the target variable (passenger referral).
7. Model Building: Train various classification models, including Logistic Regression, Random Forest, Naïve Bayes, Decision Tree, Support Vector Machine, and K-Nearest Neighbour.
8. Hyperparameter Tuning: Optimize model performance by adjusting hyperparameters using techniques like GridSearch CV.
9. Model Evaluation: Evaluate the trained models using classification metrics such as recall, accuracy, and ROC AUC.
10. Model Deployment and Interpretation: Deploy the best-performing model and provide interpretations of its predictions.
    
3. Stakeholders
The primary stakeholders in this project include:
 Airlines: The airlines benefit from the model's predictions to identify potential referrers and implement strategies to enhance customer satisfaction.
 Passengers: Passengers benefit from improved airline services and personalized experiences based on their preferences and feedback.
 Airline Industry: The project contributes to the advancement of data-driven decisionmaking in the airline industry, leading to better customer service and increased revenue.


4. Business Related Information
 Revenue Generation: Accurately predicting passenger referrals helps airlines focus on acquiring new customers through referrals, increasing revenue.
 Customer Retention: By understanding the factors that drive referrals, airlines can improve customer satisfaction and retention.
 Competitive Advantage: Predictive models provide airlines with a competitive advantage by enabling data-driven decisions and targeted marketing.
 Operational Efficiency: Identifying potential referrers helps optimize marketing and customer service efforts, improving operational efficiency.


5. Data Understanding
The dataset includes airline reviews from 2006 to 2019 for popular airlines around the world. It contains multiple-choice and free-text questions. The data was scraped in Spring 2019.
Key Variables:
 Overall Rating: The overall rating given by the passenger.
 Value for Money: The passenger's rating of the value for the price paid.
 Cabin Service: The passenger's rating of the cabin service provided.
 Ground Handling: The passenger's rating of the ground handling experience.
 Food and Beverages: The passenger's rating of the food and beverages offered.
 Seating Comfort: The passenger's rating of the seating comfort.
 Recommended: Whether the passenger would recommend the airline to their friends (target variable).

7. Model Evaluation
The classification models are evaluated based on the following metrics:
 Recall: The proportion of actual positive cases correctly identified by the model. Recall is given the highest priority in this project as it is crucial for airlines to identify as many potential referrers as possible. A higher recall indicates that the model is effectively capturing a larger percentage of passengers who would recommend the airline.
 Accuracy: The proportion of correctly classified instances (both positive and negative) out of the total instances. While accuracy is a commonly used metric, it may not be the most suitable in cases with imbalanced datasets. However, it still provides a general indication of the model's overall performance.
 ROC AUC: The area under the Receiver Operating Characteristic (ROC) curve. ROC AUC measures the model's ability to distinguish between positive and negative classes. A higher ROC AUC value suggests better discriminatory power of the model.The models were trained and tested using a variety of techniques, such as cross-validation and train-test split, to ensure their generalizability to new data. The results indicate that all the classifier models achieved over 90% accuracy, with Logistic Regression performing the best overall. Among the experimental models, Support Vector Machine (SVM) was found to be the most accurate, albeit with a very small margin.
The evaluation metrics for each model are presented in a tabular format, allowing for easy comparison and selection of the best-performing model. The table includes columns for each 
metric and rows for each model, along with the corresponding values obtained during evaluation.

Example Evaluation Table:

Model Recall                  Accuracy    ROC      AUC
Logistic Regression             0.95     0.92     0.94
Random Forest                   0.92     0.91     0.93
Naïve Bayes                     0.89     0.90     0.91
Decision Tree                   0.91     0.90     0.92
Support Vector Machine          0.93     0.92     0.93
K-Nearest Neighbour             0.90     0.91     0.92

8. Conclusion
This project successfully developed and evaluated various classification models for airline passenger referral prediction. The models achieved high accuracy and recall, indicating their 
potential for practical application in the airline industry. Logistic Regression emerged as the best-performing model overall. The project also identified the most important features for 
prediction, such as overall rating and value for money.By leveraging the developed models, airlines can gain insights into passenger preferences and identify potential referrers. This information can be used to implement targeted strategies for enhancing customer satisfaction, increasing referrals, and driving business growth. Airlines 
should focus on improving the features that are most important to passengers, such as overall rating and value for money, to increase the likelihood of recommendations and ultimately expand their business.

9. Future Work
Several areas can be explored to further enhance the project and its findings:
 Incorporating Sentiment Analysis: Analyze the free-text comments in passenger reviews to gain a deeper understanding of passenger sentiments and their impact on referrals.
 Exploring Advanced Machine Learning Techniques: Experiment with more advanced models like deep learning to potentially improve prediction accuracy.
 Real-time Prediction: Develop a system for real-time passenger referral prediction, allowing airlines to identify potential referrers during their travel experience.
 Personalization and Recommendation Systems: Build personalized recommendation systems for passengers based on their preferences and past reviews, leading to more targeted and relevant experiences.
 Integration with Airline Operations: Integrate the predictive models into airline operational systems to enable data-driven decision-making in areas like customer service and marketing.
