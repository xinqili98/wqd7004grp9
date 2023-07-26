WQD7004 Group 9 - Airline Passenger Satisfaction

1 Introduction <br />
Airline satisfaction is a crucial aspect in the aviation industry as it directly impacts the loyalty and customer retention. Airline satisfaction data collected from Kaggle is used to conduct various exploratory data analysis for better understanding of passenger preferences in airline services. Several classification Machine Learning algorithms are applied to predict their passengers satisfaction. With the insights and conclusions from this analysis, we seek to improve the airline services and increase passenger satisfaction.

The dataset can be found here: Airline Passenger Satisfaction Dataset

2 Objectives
To determine the main airline services that affects the passenger satisfaction.
To understand the correlation between the services provided by Airline.
To evaluate the performance among different classification models and predict the best model in terms of accuracy.

3 Methodology
3.1 Data Understanding
It is critical for understanding data that is available for mining and avoiding unexpected problems during data preparation. In this phase, the steps involved are collecting data, describing and exploring data and lastly to verify the data quality. Further details are elaborated in each step.

The dataset contains 24 distinct features and 103,904 entries, including information on various aspects of the flight experience, such as in-flight Wi-Fi service, online booking ease, gate location, food and drink, seat comfort, in-flight entertainment, on-board service, legroom, baggage handling, check-in service, cleanliness, passenger demographics such as gender, age, and travel type, as well as the information on departure and arrival delay times.

3.2 Data Cleaning
Having clean data will ultimately increase overall productivity and allow for the highest quality information in your decision-making. 92 and 310 missing values were detected in continuous data, which are the attributes of Departure.Delay.in.Minutes and Arrival.Delay.in.Minutes respectively and are cleaned by replacing with 0 value. Incorrect, misspell and structural error values are detected in nominal values such as Gender, Customer.Type, Type.of.Travel and Class attributes. Incorrect values are found in the ordinal type of attributes which are fixed using imputation method. All noisy data are cleaned, formatted and renamed accordingly. Irrelevant attributes are dropped to get the final clean data.

3.3 Exploratory Data Analysis (EDA)
In this section, we will walk through an overall view of the airline satisfaction dataset by customer demographics and service ratings.

3.4 Classification
Classification is the process of predicting the target label based on features in the dataset. In this project, we will build classification model using different algorithms to predict the satisfaction of customers (either satisfied or neutral/dissatisfied) based on available features such as customer demographics, flight details, service ratings etc. The algorithms used are:
Logistic Regression
Decision Tree
K-Nearest Neighbour (KNN)

4 Results
From the outcome, Decision Tree has outperformed the rest by attaining 95% accuracy score, as compared to Logistic Regression and KNN models with 88% and 91% score respectively.
Therefore, the airline company should opt for Decision Tree model to perform predictive analysis on determining their passenger satisfaction for further use.

5 Conclusion
In overall, it is suggested that Airlines should give more attention to the four services which are “In-flight Wi-Fi service,” “Ease of Online Booking,” “Departure Arrival time convenient,” and “Gate location” as they are identified to be major sources of dissatisfaction among business travelers.

For Personal Travel, the majority of the ratings for these services fall between “1” and “3” which indicates that these services are not performing as well as they could. By taking initiative to improve these services, the ratings could be increased, indicating a significant increase in passenger satisfaction and loyalty.
