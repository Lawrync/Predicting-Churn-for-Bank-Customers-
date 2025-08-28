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
# Bivariate Analysis
# What is the relationship between age and churn?
<img width="975" height="624" alt="image" src="https://github.com/user-attachments/assets/bf644852-c32d-4178-965e-8615567e7ff6" />
Analysis indicates a close tie between customer age and churn behavior. The churned customers were also distinctly older (44.8 years) by comparison with stayers (37.4 years), yielding a difference of 7.4 years. KDE plots suggest churned customers are more focused on the 40-60 age interval, whereas non-churned customers are relatively younger (25-45). This implies that age can be a significant characteristic when considering churn, and as the customer ages, the customer is likely to churn. Such findings can help the bank work out age-related retention programs and offer more services to the middle-aged population.
# Does higher credit score reduce the likelihood of churn?
<img width="975" height="660" alt="image" src="https://github.com/user-attachments/assets/767701ed-db08-42aa-bdba-24efcafe14fc" />
The boxplot of the credit scores of customers who were churned and retained shows a slight change in the two sets of customers. The median credit score and distribution range are almost identical for churned and non-churned customers. It could imply that credit score is not a potent indicator of churn in this data. This observation implies that financial creditworthiness might not be a significant parameter that could trigger a customer to quit the bank. Instead, churn seems more of a matter of behavior or regarding service, e.g., age, satisfaction, or engagement as a loyal customer. Consequently, the retention strategies should not be credit-oriented but customer experience-oriented.
# Is there a difference in churn rate between active and inactive members?
<img width="975" height="652" alt="image" src="https://github.com/user-attachments/assets/709c1cf0-db89-4f94-b1c9-c2f5ad21485e" />
Our analysis shows that a significant gap exists between the churn rate of active and inactive customers. The churn rate of inactive members is also very high, as it is almost twofold the churn rate in active members, with inactive members churning at 26.87, whereas active ones churn at 14.27 only. This reveals that the activity level is an important predictor of churn behavior. This trend is strengthened by the visual plot, which allows us to see clearly and openly that the inactive customers are much more prone to turning their backs on the bank. According to this insight, customer engagement should not be overlooked: customers who do not show activity are considered dangerous, and they should be given priority in receiving businessspecific re-engagement interventions. Incorporation of this aspect in the churn prediction model will probably increase its accuracy and deliver some business actionable insights.
# How does the number of products relate to customer churn?
<img width="975" height="602" alt="image" src="https://github.com/user-attachments/assets/29ff82d8-0b69-4c20-b96e-967d27337c3a" />
The analysis between the quantity of products that a customer owns and the probability of churning points out an interesting U-shaped trend. This is the most desirable level of engagement, as customers with a single product display moderate churn of approximately 27%, and those with two products have the lowest risk of churning of only 8%, hence the most productive. Nonetheless, the churn rates increase at an alarming level with customers having three products (around 83%) and almost 100 percent with four products, and this shows extreme risk. This relationship indicates that once adequate product engagement is reached, the spillover effect is that excess engagement will create complexity fatigue or bind from the accumulated fees, or a sense of over-selling has been reached. In the case of businesses, the same insight is relevant in highlighting that it has to strategically cross-sell and prioritize keeping customers in the two-product sweet spot to reduce the risk of churn

# Multivariate
<img width="975" height="693" alt="image" src="https://github.com/user-attachments/assets/fdbed259-8a4b-4f8e-846a-a72aca237e6c" />
In the correlation matrix, it is possible to identify some relations that exist between customer attributes and the probability of customer attrition. Interestingly, churn positively correlates with age and presence of customer complaints with moderate strength, which means that the older customers are more likely to leave, and those who raise complaints have higher probabilities to churn. Conversely, active membership and having several products are inversely related to churn, which implies that these customers are less likely to leave. Balance is weakly and positively correlated with churn, although the influence of most other numerical terms is small. The results might be used to inform specific retention activities that draw attention to older, dissatisfied, or less-engaged customers.
# Alternative Hypothesis (H 1):
The likelihood of churn among senior citizens is much higher compared to that of young customers.
















