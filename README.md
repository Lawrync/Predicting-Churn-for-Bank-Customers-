# Predicting-Churn-for-Bank-Customers-
# Introduction
Customer churn can be a major threat to businesses that need to sustain development and competitiveness. Financial services. Often in financial services, the customer relationships are long-term and high-value, so it is key to understand the reasons why customers leave. This project would use the customer data to draw useful patterns and trends that drive the churn behavior with a view to assisting in making wiser churn strategies in SmartBank, a subsidiary of Lloyds Banking Group.

# Problem Statement
SmartBank has lost customer retention, which is especially evident among younger professionals and small business bank clients. Such a tendency may indicate that there are cracks in customer satisfaction or fitment with the service. To eliminate the problem, it is important to study the customer data and find out the main factors that lead to churn. The result will inform the creation of a predictive model to lead to timely and focused interventions.

# Data collection
The dataset considered in this analysis was retrieved on Kaggle, a trusted enterprise of open-source datasets and data science competitions. It is a simulation of customer data of a financial institution, and it is used largely for churn prediction assignments.

A single record represents the customer, and the variables are both demographic and behavioral ones; the values are captured. Finally, there is a binary labeled churn (Exited) to signify whether the customer left the service or not.

Major categories of features: Demographic Information Has Gender, Age, and Geography that make it easier to put the customer background in perspective and give a basis to categorize customer behavior.

Details of Account and Services They include Tenure as well as NumOfProducts with HasCrCard and IsActiveMember, which establishes that the presence of a customer is related to the service timeline.

Financial Data Incorporates CreditScore, Balance, and EstimatedSalary that indicate the financial status of the customer and his/her potential.
Target Variable

Exited: A binary variable with one being the churned and zero remaining retained.

The data set presents a reliable basis for determining reasons that lead to customer churn and can be used in coming up with predictive models to help enhance retention strategies.

# Stakeholders
The individuals and groups of people affected either directly or indirectly by the effects of this customer churn analysis are as follows:

Executive Team-SmartBank This group will take care of strategy formulation decisions and will employ insights on churn to come up with customer retention policies and resource deployment in terms of intervention strategies.

Data Science & Analytics Unit As a senior data scientist, Li leads this team to monitor the modeling process and will use the ready data set and the results to create and implement the predictive churn model.

Teams: Marketing, Customer Retention Such teams will be dependent on the output of the model to create and execute specific campaigns focused on the vulnerable categories of customers.
# Data Analysis
# Univariate Analysis
# What is the distribution of customer ages?
<img width="975" height="579" alt="image" src="https://github.com/user-attachments/assets/f24d0d19-8ba8-4827-b0b5-c06fdd6cda60" />
The age distribution of the customers is skewed to the right, and the majority fall between the ages of 25 and 40. The lowest age identified is 18 years, and the highest is 92 years, portraying a wide range of customer demographics. The average number is nearly 39 years, and the histogram reveals a cluster at 30- 35 years of age. This imbalanced allocation means that the bank mainly attracts the young or middle-aged clients, compared to old clients.
# How many customers have churned vs. stayed?
<img width="883" height="692" alt="image" src="https://github.com/user-attachments/assets/f537b3d8-9061-4614-91f3-fb94aca43d55" />
Out of the data, 2,038 customers have already churned ( Exited = 1) and 7,962 have remained ( Exited = 0). This implies that 20.4 percent of the customers have exited the bank and 79.6 percent have not. The behavior of this churn rate is a good place to start in modeling and the study of customer retention.
# What is the distribution of satisfaction scores?
<img width="883" height="692" alt="image" src="https://github.com/user-attachments/assets/d08c9ca2-ffa8-4247-b693-52905df8fd86" />
The data plot of the satisfaction levels are more or less distributed equally across all levels, and ther, and the middle score risest prevalent satisfaction rate is 3 and 2,042 customers occupy it, next comes the rates 2 (2,014), 4 (2,008), and 5 (2,004), the latter three rates are very close to each other. Customers' rankings were lowest at 1 with 1,932 giving the lowest ranking. This implies an approximate even spread of satisfaction around the median (the neutral point 3), and no extreme skew left or right regarding satisfaction or dissatisfaction. Most customers assigned satisfaction on a scale between 2 and 4, indicating a combination of experiences within the bank.
# How many customers use each number of bank products?
<img width="975" height="726" alt="image" src="https://github.com/user-attachments/assets/62f7062e-b5bb-4916-ae6d-57471b9eae6c" />
A majority of the customers subscribe to a single or two bank products. In particular, 5,084 customers take 1 product, whereas 4,590 take 2 products. Fewer than 0.1 percent of them buy more: 266 users use 3 products and 60 users use 4 products. This indicates that the majority of customers are utilizing less of the products and there are options that the bank can use to motivate them to use more.
# What percentage of customers have credit cards?
<img width="853" height="885" alt="image" src="https://github.com/user-attachments/assets/324fda2d-e017-442e-9673-1b65dc2918a3" />
# What is the distribution of loyalty points earned?
<img width="975" height="660" alt="image" src="https://github.com/user-attachments/assets/a94ef522-9725-48c6-9298-f2136fee548c" />
The distribution of the loyalty points to the customers, with the majority earning between 200 and 900 points. The mean of the points is nearly 606, and the minimum and maximum are 119 and 1000 points, respectively. There are no extremes, such as customers' consistency in the points earned. Many customers are close to 410 (25th percentile), 605 (median), and 801 (75th percentile). This indicates that the customers are relatively active within the loyalty program. Their loyalty points come in handy when forecasting churn among customers, given that the fewer the points, the lower the engagement will be there.
# What is the range and average of customer account balances?
<img width="883" height="692" alt="image" src="https://github.com/user-attachments/assets/fb6377ec-80f0-416a-b84f-2c7e2c5e544f" />
Range: 0.0 to 250898.09 (Range = 250898.09)
Average: 76485.889288
The minimum and maximum customer account balances are 
250,898.09, respectively, implying that the amount of money the customers deposit in their accounts varies significantly. The average balance is close to $76016.85, implying that many customers do not keep a low balance. The zero balance may represent idle accounts or clients who draw their money regularly.
# What proportion of customers have made complaints?
<img width="883" height="692" alt="image" src="https://github.com/user-attachments/assets/85ec1b6a-3f29-4185-a86e-8ed95b48c9a5" />
Among a total customer base of 10,000, 2,044 customers, which is 20.44 percent, had raised complaints, and the rest, 7,956 customers, 79.56 percent, had not registered any complaint. This distribution indicates that most customers did not express concerns, indicating general customer satisfaction. However, the magnitude of more than 2,000 complaints would indicate that there are aspects where one needs to probe more to enhance customer satisfaction and service delivery.

# What is the tenure distribution of customers?
<img width="975" height="578" alt="image" src="https://github.com/user-attachments/assets/4a109759-29f8-4ff4-943b-a4b0e71a4d15" />
There is a maximum tenure of 10 years, and a mean tenure of about 5 years, with a possible standard deviation of 2.89 in the distribution of tenure of the customers in a dataset. The figures indicate a relatively wide dispersion of the data through the tenure values of 1 to 9 years, with approximately 950 and 1050 customers. It is also interesting to note that the fewest number of customers is in the 0-year (413 customers) and 10-year (490 customers) tenure groups, which seems to denote the presence of most customers at the level of being newly onboarded or getting close to a decade of service; however, the massive majority are of mid-tenure. This allocation implies that customer retention remains relatively steady in the older years of tenure, but we will see a slight decline at the edges.













