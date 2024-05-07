Salary Prediction


Introduction



Methodology:
   
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
