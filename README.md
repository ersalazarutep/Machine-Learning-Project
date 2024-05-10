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
       


![image](https://github.com/ersalazarutep/Machine-Learning-Project/assets/128092824/107660ef-c4a2-4a16-aaab-85f669a4a5de)


![image](https://github.com/ersalazarutep/Machine-Learning-Project/assets/128092824/8f64d2ea-a8da-4404-8cd5-797635cf05c3)

Logistic Regression: A linear model commonly used for binary classification tasks but can also be adapted for regression tasks. 
    
    Linear regression


![image](https://github.com/ersalazarutep/Machine-Learning-Project/assets/128092824/7eedd4a5-4d7a-478a-88bd-4adeed1ae634)


Linear Regression: A simple and interpretable linear model that assumes a linear relationship between input features and target variable. 

    Decision trees

![image](https://github.com/ersalazarutep/Machine-Learning-Project/assets/128092824/3f71fba8-f111-45fd-977a-1ab5711b1bc8)


Decision Trees: Non-parametric models that partition the feature space into hierarchical structures to make predictions. 
    
    Random forest

![image](https://github.com/ersalazarutep/Machine-Learning-Project/assets/128092824/34d13052-91a2-4f78-84a2-1addb6c7303f)

Random Forest: An ensemble learning technique that aggregates multiple decision trees to improve predictive accuracy and robustness. 

    Random forest

![image](https://github.com/ersalazarutep/Machine-Learning-Project/assets/128092824/52be581d-2a1d-4407-81f0-754018f75c9e)

Support Vector Machine (SVM): A powerful supervised learning algorithm capable of handling high-dimensional data and capturing non-linear relationships through kernel functions. 


      Conclusion


The Random Forest model typically outperforms the SVM, with lower error scores (MSE and MAE) and a higher R² value, indicating it is more accurate and reliable for predicting salaries. The SVM might perform less optimally due to its sensitivity to how it is set up and the specific settings used. 

 
In our analysis, we found that the most important features in predicting salary were level of experience and age. This observation aligns with intuitive expectations, as age and years of experience often go hand in hand. Typically, individuals with more years of experience tend to be older, and thus, these features are closely correlated. Consequently, it's reasonable to observe that both age and level of experience play pivotal roles in determining salary levels, with experience being the primary driver followed closely by age.

