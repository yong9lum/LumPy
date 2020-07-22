# Turning Data into Insights

### [Project 5 - Machine Learning from Disaster](https://github.com/yong9lum/Titanic_Project)

The legendary Titanic machine learning competition on Kaggle is one of the best challenges for someone who is just picking up on predictive programming to practise his skills. In this challenge, I tried to predict whether or not a person on the Titanic back in 1912 was likely to survive the crash, based on the given variables in the dataset, along with new engineered features. I used six machine learning techniques (Logistic Regression, Support Vector Machines, Multilayer Perceptron, Random Forest, Gradient Boosting, XGBoost) to create base models.

As part of my own learning, I further ensembled these six models using VotingClassifier in an attempt to produce a model with greater accuracy. I made seven submissions, one for every model I tested. The results are as shows:

1. Logistic Regression: 75.8%
2. Support Vector Machine: 76.6%
3. Multilayer Perceptron: 74.2%
4. Random Forest: 76.8%
5. Gradient Boosting: 76.6%
6. XGBoost: 76.3%
7. Voting Classifier Ensemble: 77.5%

Through this, the ensemble model showed that it can improve predictions from the average, and more feature engineering can possibly be done to try to improve the accuracies for all models.


### [Project 4 - Crime Prevention with Data](https://github.com/yong9lum/SanFrancisco_Crime_Project)

With a crime rate of 64 per one thousand residents, San Francisco has one of the highest crime rates in America compared to other communities of various sizes — from the smallest towns to the very largest cities. One's chance of becoming a victim of either violent or property crime in San Francisco is 1-in-16, & within California alone, more than 99% of the communities have a lower crime rate. A victim of crime may experience different kinds of effects, including physical effects like injuries, psychological effects like anger & Post-Traumatic Stress Disorder (PTSD), & economic effects like paying for medical expenses & time-off from work. The implications of crime go beyond individuals and affect communities as a whole. In San Francisco, property & low-level crimes are aggravating the destruction of the retail market. With rampant theft & lack of security, landmark Mission District stores are closing, while mom-&-pop businesses find it hard to survive when wracked by constant thefts. The high crime rates & lack of security has also resulted in San Francisco being labelled as a non-viable market, discouraging new businesses from setting up due to fear. Against high crime rates, every individual, family, community, and organization is a victim.

I used San Francisco's historical crime dataset to run data analytics visualisations using Tableau & machine learning models like XGBoost, CART & Logistic Regression to get a better overview of the crime situation, & come up with predictive & preventive solutions for those problems. The most important outcomes I want to achieve in this project are improving manpower allocation & scheduling, using police patrols as preventive measures & giving priority to crimes that are more 'solvable', as well as bringing focus to juvenile crimes (be it perpetrators or victims).


### [Project 3 - Using Data Analytics in E-commerce](https://github.com/yong9lum/E-commerce_Project)

A hypothetical e-commerce company 'X' serves as a third-party retailer, bridging online shoppers with sellers. It also has its own production line of goods, & has a physical brick & mortar store in Singapore selling some of their own products. It is vital for 'X' to be ahead of customers’ buying patterns & current trends, due to strong competition from other e-commerce companies with similarly competitive pricing & strong marketing.

I leveraged on the data to recommend a loyalty program, to tier customers so that they can be rewarded gradually for spending more. I also created a forecasting model that the supply chain department can better manage the available inventory space & ensure that a future increase/decrease in demand can be accounted for. Lastly, I programmed a command line user interface that will allow easy summary pull outs of past data & generate future demands, serving as a user interface that all employees can access.


### [Project 2 - A Solution for IBM's HR Headache](https://github.com/yong9lum/IBM_Project)

A HR department receives thousands of resumes on a daily basis & evaluates them manually to shortlist candidates for a first-round interview. This is done by assessing if candidates have the right skills & experience, as well as the key qualities & traits required for a position. These various processes are currently very labor-intensive & hence, there is room to improve the effectiveness of current processes given the high turnover for certain roles such as sales. Also, it is difficult to accurately predict the potential fit and future conduct of the candidate. HR is thus seeking for ways to better support its HR team to make the recruitment process more effective with improved accuracy in the matching process.

I used text mining techniques to create a solution that will help the HR department pick which applicants to invite for an interview, & did a comparison between logistic regression & CART to predict which prospective employees should or should not be hired based on the likelihood of attrition within four years. These machine learning techniques seek to automate the hiring processes while also providing value to IBM's hiring department through the use of analytics.


### [Project 1 - An Airbnb Application](https://github.com/yong9lum/Airbnb_Project)

This is the very first data science project that I attempted with some basic Python programming knowledge, as part of a submission for Hackwagon Academy's DS101 course.

In this project, I used questions to guide my exploration on of the dataset to pick up on any trends or insights on the different neighborhoods, the pricing, as well as the satisfaction levels based on reviews.

I also created a input-based application for customers to visualise possible listings on a map depending on how they want to filter price, overall satisfaction (number of stars), & neighborhood. Prospective hosts can also use the application to give them a gauge on the price to set per night for their listing, which will be calculated by taking the average prices of the other listings within the same neighborhood.
