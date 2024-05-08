*** Salary Prediction ***


*** Introduction ***

Today's job market demands accurate salary predictions for effective decision-making.
Salary prediction is essential for HR recruitment processes: guides compensation, workforce planning, and talent acquisition strategies.
Employers and job seekers rely on predictions for competitive offers and informed career decisions.
Factors influencing salary prediction: education, experience, age, job title, industry, location, and market demand.


*** Problem Statement ***

The problem we're trying to solve is to develop accurate machine learning models that can predict salaries based on various individual attributes such as age, gender, education level, job title, and years of experience. In essence, we aim to create predictive models that can estimate a person's salary given their demographic and professional characteristics. 
Determining salary requires careful consideration and depends on various factors that can get costly. Our models can help both companies and individuals in workforce planning, make career choices, get a fair compensation, and get valuable market insights. 


**** Methodology ***
   
    Logistic regression 

    Variables:
       
       Age
       Years of Experience
       Education Level
       Job Title
       Gender
       
![image](https://github.com/ersalazarutep/Machine-Learning-Project/assets/128092824/be01c3d3-456c-463d-b5d7-146c2c75f99e)

![Uploading image.png…]()


Target Variable Definition: The code defines a binary target variable (Above Median Salary) where the value is 1 if the salary is above the median and 0 otherwise. This makes it a binary classification problem, which is suitable for logistic regression.
Model Selection: The code then instantiates a logistic regression model using LogisticRegression() from sklearn.linear_model. Logistic regression is specifically designed for binary classification tasks.
Model Training and Evaluation: The model is trained on the features (X_train) and target (y_train) using .fit() method. Finally, it makes predictions on the test set (X_test) and evaluates the model's performance using metrics like accuracy and classification report.
    
    Decision trees
    
    Random forest
