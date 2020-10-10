# Bank_Personal_Loan_Modelling
Logistic Regression Example

# Project: Problem Statement - Personal Loan Campaign Modelling

## Thera Bank Personal Loan Campaign
 
### Data Description:
The dataset contains data on 5000 customers. The data include customer demographic information (age, income, etc.), the customer's relationship with the bank (mortgage, securities account, etc.), and the customer response to the last personal loan campaign (Personal Loan). Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign.

 
### Domain:
Banking


### Context:
This case is about a bank (Thera Bank) whose management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors). A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio with a minimal budget.

 
### Attribute Information:
<li>ID: Customer ID</li>
<li>Age: Customer's age in completed years</li>
<li>Experience: #years of professional experience</li>
<li>Income: Annual income of the customer (,000)</li>
<li>ZIP Code: Home Address ZIP</li>
<li>Family: Family size of the customer</li>
<li>CCAvg: Avg. spending on credit cards per month (,000)</li>
<li>Education: Education Level. 1: Undergrad; 2: Graduate; 3: Advanced/Professional</li>
<li>Mortgage: Value of house mortgage if any. (,000)</li>
<li>Personal Loan: Did this customer accept the personal loan offered in the last campaign?</li>
<li>Securities Account: Does the customer have a securities account with the bank?</li>
<li>CD Account: Does the customer have a certificate of deposit (CD) account with the bank?</li>
<li>Online: Does the customer use internet banking facilities?</li>
<li>Credit card: Does the customer use a credit card issued by the bank?</li>
 
 
### Learning Outcomes:
<li>Exploratory Data Analysis</li>
<li>Preparing the data to train a model</li>
<li>Training and making predictions using a classification model</li>
<li>Model evaluation</li>
 

### Objective:
The classification goal is to predict the likelihood of a liability customer buying personal loans.

 
### Steps and tasks:
<ol>
<li>Import the datasets and libraries, check datatype, statistical summary, shape, null values or incorrect imputation.</li>
<li>EDA: Study the data distribution in each attribute and target variable, share your findings </li>
<ul>
    <li>Number of unique in each column?</li>
    <li>Number of people with zero mortgage?</li>
    <li>Number of people with zero credit card spending per month?</li>
    <li>Value counts of all categorical columns.</li>
    <li>Univariate and Bivariate</li>
    <li>Get data model ready</li>
</ul>
<li>Split the data into training and test set in the ratio of 70:30 respectively</li>
<li>Use the Logistic Regression model to predict whether the customer will take a personal loan or not. Print all the metrics related to evaluating the model performance (accuracy, recall, precision, f1score, and roc_auc_score). Draw a heatmap to display confusion matrix</li> 
<li>Find out coefficients of all the attributes and show the output in a data frame with column names? For test data show all the rows where the predicted class is not equal to the observed class.</li>
<li>Give conclusion related to the Business understanding of your model?</li>
