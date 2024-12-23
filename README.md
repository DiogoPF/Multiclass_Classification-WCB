The New York Workers’ Compensation Board (WCB) oversees various workers’ benefits programs but relies on a manual, labor-intensive process for handling claims. This lack of automation leads to delays, increased workload, and a higher risk of errors. This project aims to address these challenges by developing a machine learning model to automate the classification of claims by injury type. Using a labeled dataset of claims from 2020 to 2022, which is inherently imbalanced due to certain types of cases being much more frequent than others, we employed a systematic approach to build, evaluate, and optimize predictive models. 
We start by testing 5 models (Neural Networks, Decision Trees, K-Nearest Neighbors, Logistic Regression, and Naïve Bayes) to establish a performance. In an effort to maximize performance, we tested different types of ensemble models (Bagging, Boosting and Stacking). After selecting the model with the best performance, we tested different preprocessing techniques. 
Our best-performing estimator is a Neural Network that achieved 0.41 ± 0.01 in training and 0.4 ± 0.01 in validation. It can predict very well two classes, non-compensation and temporary. But the others suffer from misclassification. 
We attribute the model's limitations to the lack of meaningful features that effectively distinguish between classes. There were no performance improvements by adding more features to the model, by using various ensemble techniques, by oversampling minority classes or by using a One versus All framework. 
These findings underscore the critical need for advanced feature engineering to enhance model performance. Future efforts should focus on extracting domain-specific features and exploring alternative data representations to better capture the nuances of claims data. By addressing these challenges, the WCB can significantly improve claim processing efficiency and decision accuracy.
