# Titanic_problem
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

I built a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc). This is a classification problem.

I used the dataset available in Kaggle. I used python in Google Collab to analyze and visualize data and train my model. I used pandas and numpy libraries.

I tried and tested
1. Logistic Regression
2. XGBClassifier
3. Decision Tree Classification
4. K-nearest Neighbours
5. Kernel SVM
6. Naive Bayes
7. Random Forest Classification
8. Support Vector Machine (SVM)
   models. After applying K-fold cross validation, the accuracy for validation dataset, mean accuracy and standard deviation provided by Kernel SVM model gave best results:-
   
Kernel SVM :-
Accuracy = 77.65 %
After K fold cross validation-
Accuracy = 84.00 %
Standard Deviation = 3.70 %
