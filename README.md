This project aims to predict flight delays using a dataset of flight information from January 2019 and January 2020. Various machine learning models are employed to achieve this, including Random Forest Classifier, Gaussian Naive Bayes, Decision Tree Classifier, and K-Nearest Neighbors Classifier. The process involves several key steps:

    Data Preprocessing: The data is first loaded and inspected for missing values, which are then handled appropriately. Non-essential columns are dropped, and relevant categorical features are encoded. Special attention is given to creating meaningful time blocks for departure and arrival times, which are then label-encoded.

    Feature Engineering: Additional features such as average delay by origin and destination on specific days are generated. The ARR_DEL15 column, indicating whether a flight was delayed by more than 15 minutes, is set as the target variable.

    Data Visualization: The distributions of delayed flights for both departures and arrivals are visualized using pie charts. Bar plots are created to examine arrival delays by airline and day of the week.

    Model Training and Evaluation: The dataset is split into training and testing sets. Several classifiers are trained and evaluated using metrics such as confusion matrix, classification report, and accuracy score. The performance of each model is assessed to determine the most effective approach for predicting flight delays.

This approach provides a comprehensive method for predicting flight delays, utilizing a combination of feature engineering, visualization, and machine learning techniques. The results from different models offer insights into their effectiveness and potential application in real-world scenarios.
