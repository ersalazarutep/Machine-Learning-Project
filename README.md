                                                                                       *** Salary Prediction ***


*** Introduction ***

Today's job market demands accurate salary predictions for effective decision-making.
Salary prediction is essential for HR recruitment processes: guides compensation, workforce planning, and talent acquisition strategies.
Employers and job seekers rely on predictions for competitive offers and informed career decisions.
Factors influencing salary prediction: education, experience, age, job title, industry, location, and market demand.


*** Problem Statement ***


The problem we're trying to solve is to develop accurate machine learning models that can predict salaries based on various individual attributes such as age, gender, education level, job title, and years of experience. In essence, we aim to create predictive models that can estimate a person's salary given their demographic and professional characteristics. 
Determining salary requires careful consideration and depends on various factors that can get costly. Our models can help both companies and individuals in workforce planning, make career choices, get a fair compensation, and get valuable market insights. 

*** Why should we care to solve this ***

Human Resources Optimization: 

Help the organization in optimizing human resources allocation and budgeting.
Better planning of compensation packages, recruitment strategies, and employee retention efforts.

Fair Compensation:

Organizations can strive for fair and equitable compensation practices.
Identifying any biases or disparities in salary distribution based on demographics can help address issues of pay inequity.

Career Planning and Negotiation: 

For individuals, having insights into the expected salary range for specific roles and demographics can inform career decisions and negotiations. 
Empowers employees to advocate for fair compensation 


Why is ML needed?

Complex Relationships: Machine learning models accurately capture the complex factors that determine salaries.

Scalability: These models can efficiently handle large datasets, essential for robust predictions across different job markets.

Flexibility: Machine learning provides the versatility to choose and customize different algorithms based on the data and goals.



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
