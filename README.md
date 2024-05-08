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


**** Dataset ****

 Attributes: 
* Age: Age of the individual in year

* Gender: Gender of the individual 

* Education Level: Highest level of education attained by the individual (High School, Bachelor’s, Master’s, and PhD) 

* Job Title: Title of the individual current position

* Year of Experience: Number of years of work experience the individual has

* Salary (dependent variable): Annual salary of the individual in dollars 

* 6704 rows, each row represents one individual's information, 6 columns 



![image](https://github.com/ersalazarutep/Machine-Learning-Project/assets/128092824/afabf6bf-ec33-4ff7-a4da-cd5de0fc0209)


-- Data Cleaning --

Dropped null values

Omitted titles with less than 20 counts 

Combined repeating education levels

Label encoding

Scaled numerical features

Got rid of outliers


**** Methodology ****
   
    Logistic regression 
       

![image](https://github.com/ersalazarutep/Machine-Learning-Project/assets/128092824/5dd6313e-e224-4c3a-9eb0-9c02351f2c88)

![image](https://github.com/ersalazarutep/Machine-Learning-Project/assets/128092824/8f64d2ea-a8da-4404-8cd5-797635cf05c3)

![image](https://github.com/ersalazarutep/Machine-Learning-Project/assets/128092824/fb2853bf-d0d4-47bc-922c-c563c8b76baa)

Target Variable Definition: The code defines a binary target variable (Above Median Salary) where the value is 1 if the salary is above the median and 0 otherwise. This makes it a binary classification problem, which is suitable for logistic regression.
Model Selection: The code then instantiates a logistic regression model using LogisticRegression() from sklearn.linear_model. Logistic regression is specifically designed for binary classification tasks.
Model Training and Evaluation: The model is trained on the features (X_train) and target (y_train) using .fit() method. Finally, it makes predictions on the test set (X_test) and evaluates the model's performance using metrics like accuracy and classification report.
    
    Linear regression


![image](https://github.com/ersalazarutep/Machine-Learning-Project/assets/128092824/7eedd4a5-4d7a-478a-88bd-4adeed1ae634)


![image](https://github.com/ersalazarutep/Machine-Learning-Project/assets/128092824/0f250274-b369-4ae8-b0e4-2b006a45e62d)

    
    Decision trees
    
    Random forest
