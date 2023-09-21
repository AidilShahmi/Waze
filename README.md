# Waze

Overview

This project aimed at increasing overall growth by preventing monthly user churn on the Waze app. For the purposes of this project, churn quantifies the number of users who have uninstalled the Waze app or stopped using the app. This project also includes developing a two-sample hypothesis test to analyze and determine whether there is a statistically significant difference between mean number of rides and device type – Android vs. iPhone.


Data Understanding

This dataset contains 82% retained users and 18% churned users. The dataset contains 12 unique variables with types including objects, floats, and integers; the label column is missing 700 values with no indication that the omissions are non-random. The median user who churned drove 608 kilometers each day they drove last month, which is almost 250% the per-drive-day distance of retained users. Regardless of user churn, the users represented in this data drive a lot! It is probably safe to assume that this data does not represent typical drivers at large. 

Modelling and Evaluation

The more times users used the app, the less likely they were to churn. While 40% of the users who didn't use the app at all last month churned, nobody who used the app 30 days churned. Distance driven per driving day had a positive correlation with user churn. The farther a user drove on each driving day, the more likely they were to churn. Number of driving days had a negative correlation with churn. Users who drove more days of the last month were less likely to churn. The t-test results concluded there is not a statistically significant difference in mean number of rides between iPhone users and Android users. 

Conclusion

The ML models developed for Milestone 6 demonstrate a critical need for additional data in order to more accurately predict user churn. This modeling effort confirms that the current data is insufficient to consistently predict churn. Since engineered features are a proven valuable tool for improving the performance of ML models, the Waze team recommends a second iteration of the User Churn Project.









