# Student Graduation Classifier

In this cases, I am faced with the challenge of classifying a student's graduation period. There are several variables that will affect the student's graduation such as course credits that have been taken, GPA, and also D/E marks. Before jump to the classification code, my friend ( Juan Alberto Galih Leo, Christeigen Theodore Suhalim) and I have done exploratory data analysis and also data pre - processing to find out more details about this data.

For the classification, I started with handling imbalance data using 3 techinques, which are Random Over Sampling, Random Under Sampling and also SMOTE. Right after I found the best technique which is SMOTE, I continued to check the accuracy of 5 classifation models. There are Naive Bayes, Decision Tree, SVM, Random Forest, and Logistic Regression. To improve the performance of each model, I tried to indentify the best parameter using Hyperparameter Tuning technique. At the end, I made my own classifier based on Random Forest, Decision Tree, and SVM model to predict either the student will graduate more than 4 years or not, with accuracy above 95%. I name this classifier as Chateksada Classifier.

Special thanks to my lecturer, Ratih Ardiati Ningrum, M.S., M.Stat. and also my team for supporting me in this project
