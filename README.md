# Benchmarking Tabular Data in Banking and Finance

To evaluate model performance on common finance tasks such as banking, credit modeling, loan approval, etc., we benchmarked several tabular datasets. This section details the datasets used in our analysis, including a summary of their metadata and the resulting performance metrics.

## 1. `german-credit`
- **Description:** This dataset classifies people described by a set of attributes as good or bad credit risks
- **Source:** <a href="https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data">UCIMLR</a>
- **#Rows:** 1000
- **#Features:** 21
- **Target:** `class`
- **#Views:** 178848 (as of September 29, 2025)
- **#Citations:** 63 (as of September 29, 2025)
- **Additional Description:**  Provided by Prof. Hofmann at 10.24432/C5NC77
- **Features:**<br>
`Attribute 1`:  (qualitative)      
 Status of existing checking account
           A11 :      ... <    0 DM
           A12 : 0 <= ... <  200 DM
           A13 :      ... >= 200 DM / salary assignments for at least 1 year
           A14 : no checking account</br>
`Attribute 2`:  (numerical)
          Duration in month</br>
`Attribute 3`:  (qualitative)
          Credit history
          A30 : no credits taken/ all credits paid back duly
              A31 : all credits at this bank paid back duly
          A32 : existing credits paid back duly till now
              A33 : delay in paying off in the past
          A34 : critical account/  other credits existing (not at this bank)</br>
`Attribute 4`:  (qualitative)
          Purpose
          A40 : car (new)
          A41 : car (used)
          A42 : furniture/equipment
          A43 : radio/television
          A44 : domestic appliances
          A45 : repairs
          A46 : education
          A47 : (vacation - does not exist?)
          A48 : retraining
          A49 : business
          A410 : others</br>
`Attribute 5`:  (numerical)
          Credit amount</br>
`Attibute 6`:  (qualitative)
          Savings account/bonds
          A61 :          ... <  100 DM
          A62 :   100 <= ... <  500 DM
          A63 :   500 <= ... < 1000 DM
          A64 :          .. >= 1000 DM
              A65 :   unknown/ no savings account</br>
`Attribute 7`:  (qualitative)
          Present employment since
          A71 : unemployed
          A72 :       ... < 1 year
          A73 : 1  <= ... < 4 years  
          A74 : 4  <= ... < 7 years
          A75 :       .. >= 7 years</br>
`Attribute 8`:  (numerical)
          Installment rate in percentage of disposable income</br>
`Attribute 9`:  (qualitative)
          Personal status and sex
          A91 : male   : divorced/separated
          A92 : female : divorced/separated/married
              A93 : male   : single
          A94 : male   : married/widowed
          A95 : female : single</br>
`Attribute 10`: (qualitative)
          Other debtors / guarantors
          A101 : none
          A102 : co-applicant
          A103 : guarantor</br>
`Attribute 11`: (numerical)
          Present residence since</br>
`Attribute 12`: (qualitative)
          Property
          A121 : real estate
          A122 : if not A121 : building society savings agreement/ life insurance
              A123 : if not A121/A122 : car or other, not in attribute 6
          A124 : unknown / no property</br>
`Attribute 13`: (numerical)
          Age in years</br>
`Attribute 14`: (qualitative)
          Other installment plans 
          A141 : bank
          A142 : stores
          A143 : none</br>
`Attribute 15`: (qualitative)
          Housing
          A151 : rent
          A152 : own
          A153 : for free</br>
`Attribute 16`: (numerical)
              Number of existing credits at this bank</br>
`Attribute 17`: (qualitative)
          Job
          A171 : unemployed/ unskilled  - non-resident
          A172 : unskilled - resident
          A173 : skilled employee / official
          A174 : management/ self-employed/
             highly qualified employee/ officer</br>
`Attribute 18`: (numerical)
          Number of people being liable to provide maintenance for</br>
`Attribute 19`: (qualitative)
          Telephone
          A191 : none
          A192 : yes, registered under the customers name</br>
`Attribute 20`: (qualitative)
          foreign worker
          A201 : yes
          A202 : no</br>
`class (Target)`: (numerical)
          good or bad
          1 : Good
          2 : Bad</br>
- **Model Performance:** 
![Model Performance](./results/plot_1_german_credit.png)

## 2. `bank-marketing`
- **Description:**  The classification goal is to predict if the client will subscribe a term deposit (variable y).
- **Source:** <a href="https://archive.ics.uci.edu/dataset/222/bank+marketing">UCIMLR</a>
- **#Rows:** 45211
- **#Features:** 17
- **Target:** `y`
- **#Views:** 513689  (as of September 29, 2025)
- **#Downloads:**  (as of September 29, 2025)
- **#Citations:** 9
- **Additional Description:** The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution.
- **Features:** <br>
   `age` (numeric)<br>
   `job` : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student",
                                       "blue-collar","self-employed","retired","technician","services") <br>
   `marital` : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)<br>
   `education` (categorical: "unknown","secondary","primary","tertiary")<br>
   `default`: has credit in default? (binary: "yes","no")<br>
   `balance`: average yearly balance, in euros (numeric) <br>
   `housing`: has housing loan? (binary: "yes","no")<br>
   `loan`: has personal loan? (binary: "yes","no")<br>
   `contact`: contact communication type (categorical: "unknown","telephone","cellular") <br>
   `day`: last contact day of the month (numeric)<br>
   `month`: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")<br>
   `duration`: last contact duration, in seconds (numeric)<br>
   `campaign`: number of contacts performed during this campaign and for this client (numeric, includes last contact)<br>
   `pdays`: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)<br>
   `previous`: number of contacts performed before this campaign and for this client (numeric)<br>
   `poutcome`: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")<br>
   `y (Target)` - has the client subscribed a term deposit? (binary: "yes","no")<br>
- **Model Performance:** 
![Model Performance](./results/plot_2_bank_marketing.png)

## 3. `credit-approval`
- **Description:** This data concerns credit card applications; good mix of attributes
- **Source:** <a href="https://archive.ics.uci.edu/dataset/27/credit+approval">UCIMLR</a>
- **#Rows:** 690
- **#Features:** 16 
- **Target:** `A16`
- **#Views:** 108380 (as of September 29, 2025)
- **#Downloads:**  (as of September 29, 2025)
- **#Citations:** 12
- **Additional Description:** All attribute names and values have been changed to meaningless symbols to protect confidentiality of the data.
- **Features:** <br>
`A1`:	b, a.<br>
`A2`:	continuous.<br>
`A3`:	continuous.<br>
`A4`:	u, y, l, t.<br>
`A5`:	g, p, gg.<br>
`A6`:	c, d, cc, i, j, k, m, r, q, w, x, e, aa, ff.<br>
`A7`:	v, h, bb, j, n, z, dd, ff, o.<br>
`A8`:	continuous.<br>
`A9`:	t, f.<br>
`A10`:	t, f.<br>
`A11`:	continuous.<br>
`A12`:	t, f.<br>
`A13`:	g, p, s.<br>
`A14`:	continuous.<br>
`A15`:	continuous.<br>
`A16 (Target)`: +,- (class attribute)<br>
- **Model Performance:** 
![Model Performance](./results/plot_3_credit_approval.png)

## 4. `australian-credit`
- **Description:** This file concerns australian credit card applications. This database exists elsewhere in the repository (Credit Screening Database) in a slightly different form
- **Source:** <a href=""></a>
- **#Rows:** 690
- **#Features:** 15 
- **Target:** `A15`
- **#Views:** 26995 (as of September 29, 2025)
- **#Downloads:**  (as of September 29, 2025)
- **#Citations:** 4
- **Additional Description:** All attribute names and values have been changed to meaningless symbols to protect confidentiality of the data.
- **Features:** <br>
There are 6 numerical and 8 categorical attributes.  The labels have been changed for the convenience of the statistical algorithms.  For example, attribute 4 originally had 3 labels p,g,gg and these have been changed to labels 1,2,3.  <br>         
`A1`: 0,1    CATEGORICAL (formerly: a,b)<br>
`A2`: continuous.<br>
`A3`: continuous.<br>
`A4`: 1,2,3    CATEGORICAL  (formerly: p,g,gg)<br>
`A5`: 1, 2,3,4,5, 6,7,8,9,10,11,12,13,14    CATEGORICAL (formerly: ff,d,i,k,j,aa,m,c,w, e, q, r,cc, x)<br>
`A6`: 1, 2,3, 4,5,6,7,8,9    CATEGORICAL (formerly: ff,dd,j,bb,v,n,o,h,z)<br>
`A7`: continuous.<br>
`A8`: 1, 0    CATEGORICAL (formerly: t, f)<br>
`A9`: 1, 0	CATEGORICAL (formerly: t, f)<br>
`A10`:  continuous.<br>
`A11`:  1, 0	    CATEGORICAL (formerly t, f)<br>
`A12`:  1, 2, 3    CATEGORICAL (formerly: s, g, p) <br>
`A13`:  continuous.<br>
`A14`:  continuous.<br>
`A15 (Target)`:   1,2  class attribute (formerly: +,-) <br>
- **Model Performance:** 
![Model Performance](./results/plot_4_australian_credit.png)

## 5. `default-credit-card`
- **Description:** This research aimed at the case of customers' default payments in Taiwan and compares the predictive accuracy of probability of default among six data mining methods.
- **Source:** <a href="https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients">UCIMLR</a>
- **#Rows:** 30000
- **#Features:** 24
- **Target:** `Y`
- **#Views:** 183542 (as of September 29, 2025)
- **#Downloads:**  (as of September 29, 2025)
- **#Citations:** 3
- **Additional Description:** This research aimed at the case of customers' default payments in Taiwan and compares the predictive accuracy of probability of default among six data mining methods. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. Because the real probability of default is unknown, this study presented the novel Sorting Smoothing Method to estimate the real probability of default. With the real probability of default as the response variable (Y), and the predictive probability of default as the independent variable (X), the simple linear regression result (Y = A + BX) shows that the forecasting model produced by artificial neural network has the highest coefficient of determination; its regression intercept (A) is close to zero, and regression coefficient (B) to one. Therefore, among the six data mining techniques, artificial neural network is the only one that can accurately estimate the real probability of default.
- **Features:** <br>
This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:<br>
`X1`: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.<br>
`X2`: Gender (1 = male; 2 = female).<br>
`X3`: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).<br>
`X4`: Marital status (1 = married; 2 = single; 3 = others).<br>
`X5`: Age (year).<br>
`X6 - X11`: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.<br>
`X12-X17`: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005. <br>
`X18-X23`: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.<br>
`Y (Target)`: default payment next month<br>
- **Model Performance:** 
![Model Performance](./results/plot_5_default_credit_card.png)

<!-- ## 6. `credit-card-approval`
- **Description:** application_record.csv contains appliers personal information, which you could use as features for predicting credit_record.csv records users' behaviors of credit card.
- **Source:** <a href="https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction/data">Kaggle </a>
- **Files:** ![application_record.csv](./datasets/application_record.csv) , ![credit_record.csv](./datasets/credit_record.csv)
- **#Rows:** 438558
- **#Features:** 21 (18 from application_record + 3 from credit_record)
- **Target:** `STATUS`
- **#Views:** 686000 (as of September 28, 2025)
- **#Downloads:** 91700 (as of September 28, 2025)
- **Additional Description:** "Credit score cards are a common risk control method in the financial industry. It uses personal information and data submitted by credit card applicants to predict the probability of future defaults and credit card borrowings. The bank is able to decide whether to issue a credit card to the applicant. Credit scores can objectively quantify the magnitude of risk. Generally speaking, credit score cards are based on historical data. Once encountering large economic fluctuations. Past models may lose their original predictive power. Logistic model is a common method for credit scoring. Because Logistic is suitable for binary classification tasks and can calculate the coefficients of each feature. In order to facilitate understanding and operation, the score card will multiply the logistic regression coefficient by a certain value (such as 100) and round it. At present, with the development of machine learning algorithms. More predictive methods such as Boosting, Random Forest, and Support Vector Machines have been introduced into credit card scoring. However, these methods often do not have good transparency. It may be difficult to provide customers and regulators with a reason for rejection or acceptance. Build a machine learning model to predict if an applicant is 'good' or 'bad' client, different from other tasks, the definition of 'good' or 'bad' is not given. You should use some techique, such as vintage analysis to construct you label. Also, unbalance data problem is a big problem in this task."
- **Features:** There're two tables could be merged by ID:<br>
---<br>
`application_record.csv`:<br>
---<br>
`ID`	Client number	<br>
`CODE_GENDER`	Gender	<br>
`FLAG_OWN_CAR`	Is there a car	<br>
`FLAG_OWN_REALTY`	Is there a property	<br>
`CNT_CHILDREN`	Number of children	<br>
`AMT_INCOME_TOTAL`	Annual income	<br>
`NAME_INCOME_TYPE`	Income category	<br>
`NAME_EDUCATION_TYPE`	Education level	<br>
`NAME_FAMILY_STATUS`	Marital status	<br>
`NAME_HOUSING_TYPE`	Way of living	<br>
`DAYS_BIRTH`	Birthday	Count backwards from current day (0), -1 means yesterday<br>
`DAYS_EMPLOYED`	Start date of employment	Count backwards from current day(0). If positive, it means the person currently unemployed.<br>
`FLAG_MOBIL`	Is there a mobile phone	<br>
`FLAG_WORK_PHONE`	Is there a work phone	<br>
`FLAG_PHONE`	Is there a phone	<br>
`FLAG_EMAIL`	Is there an email	<br>
`OCCUPATION_TYPE`	Occupation	<br>
`CNT_FAM_MEMBERS`	Family size	<br>
---<br>
`credit_record.csv`:		<br>
---<br>
`ID`	Client number	<br>
`MONTHS_BALANCE`	Record month	The month of the extracted data is the starting point, backwards, 0 is the current month, -1 is the previous month, and so on<br>
`STATUS (Target)`	Status	0: 1-29 days past due 1: 30-59 days past due 2: 60-89 days overdue 3: 90-119 days overdue 4: 120-149 days overdue 5: Overdue or bad debts, write-offs for more than 150 days C: paid off that month X: No loan for the month
- **Model Performance:** 
![Model Performance](./results/NA) -->

## 6. `loan-modelling`
- **Description:** The data include customer demographic information (age, income, etc.), the customer's relationship with the bank (mortgage, securities account, etc.), and the customer response to the last personal loan campaign (Personal Loan). Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign.
- **Source:** <a href="https://www.kaggle.com/datasets/teertha/personal-loan-modeling">Kaggle</a>
- **File:**  ![Bank_Personal_Loan_Modelling.csv](./datasets/Bank_Personal_Loan_Modelling.csv)
- **#Rows:** 5000
- **#Features:** 14
- **Target:** `Personal_Loan`
- **#Views:** 61300 (as of September 29, 2025)
- **#Downloads:** 9739 (as of September 29, 2025)
- **Additional Description:** "This case is about a bank (Thera Bank) whose management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors). A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns with better target marketing to increase the success ratio with minimal budget."
- **Features:** <br>
`ID`: Customer ID <br>
`Age`: Customer’s age in completed years<br>
`Experience`: #years of professional experience<br>
`Income`: Annual income of the customer (in thousand dollars)<br>
`ZIP Code`: Home Address ZIP code.<br>
`Family`: the Family size of the customer<br>
`CCAvg`: Average spending on credit cards per month (in thousand dollars)<br>
`Education`: Education Level. 1: Undergrad; 2: Graduate;3: Advanced/Professional<br>
`Mortgage`: Value of house mortgage if any. (in thousand dollars)<br>
`Securities_Account`: Does the customer have securities account with the bank?<br>
`CD_Account`: Does the customer have a certificate of deposit (CD) account with the bank?<br>
`Online`: Do customers use internet banking facilities?<br>
`CreditCard`: Does the customer use a credit card issued by any other Bank (excluding All life Bank)?<br>
`Personal_Loan (Target)`: Did this customer accept the personal loan offered in the last campaign?<br>
- **Model Performance:** 
![Model Performance](./results/plot_6_loan_modelling.png)

## 7. `credit-risk`
- **Description:** This dataset contains columns simulating credit bureau data
- **Source:** <a href="https://www.kaggle.com/datasets/laotse/credit-risk-dataset/">Kaggle</a>
- **File:**  ![credit_risk_dataset.csv](./datasets/credit_risk_dataset.csv)
- **#Rows:** 32581
- **#Features:** 12
- **Target:** `loan_status`
- **#Views:** 271000 (as of September 29, 2025)
- **#Downloads:** 46100  (as of September 29, 2025)
- **Additional Description:**
- **Features:** <br>
`person_age`: Age of the individual applying for the loan.<br>
`person_income`: Annual income of the individual.<br>
`person_home_ownership`: Type of home ownership of the individual.<br>
    |- rent: The individual is currently renting a property.<br>
    |- mortgage: The individual has a mortgage on the property they own.<br>
    |- own: The individual owns their home outright.<br>
    |- other: Other categories of home ownership that may be specific to the dataset.<br>
`person_emp_length`: Employment length of the individual in years.<br>
`loan_intent`: The intent behind the loan application.<br>
`loan_grade`: The grade assigned to the loan based on the creditworthiness of the borrower.<br>
    |- A: The borrower has a high creditworthiness, indicating low risk.<br>
    |- B: The borrower is relatively low-risk, but not as creditworthy as Grade A.<br>
    |- C: The borrower's creditworthiness is moderate.<br>
    |- D: The borrower is considered to have higher risk compared to previous grades.<br>
    |- E: The borrower's creditworthiness is lower, indicating a higher risk.<br>
    |- F: The borrower poses a significant credit risk.<br>
    |- G: The borrower's creditworthiness is the lowest, signifying the highest risk.<br>
`loan_amnt`: The loan amount requested by the individual.<br>
`loan_int_rate`: The interest rate associated with the loan.<br>
`loan_percent_income`: The percentage of income represented by the loan amount.<br>
`cb_person_default_on_file`: Historical default of the individual as per credit bureau records.<br>
    |- Y: The individual has a history of defaults on their credit file.<br>
    |- N: The individual does not have any history of defaults.<br>
`cb_preson_cred_hist_length`: The length of credit history for the individual.<br>
`loan_status (Target)`: Loan status, where 0 indicates non-default and 1 indicates default.<br>
    - 0: Non-default - The borrower successfully repaid the loan as agreed, and there was no default.
    - 1: Default - The borrower failed to repay the loan according to the agreed-upon terms and defaulted on the loan.<br>
- **Model Performance:** 
![Model Performance](./results/plot_7_credit_risk.png)

<!-- ## 9. `credit-score`
- **Description:**  Given a person’s credit-related information, build a machine learning model that can classify the credit score
- **Source:** <a href="https://www.kaggle.com/datasets/parisrohan/credit-score-classification">Kaggle</a>
- **File:**  ![credit_score.csv](./datasets/credit_score.csv)
- **#Rows:** 100000
- **#Features:** 28
- **Target:** `credit_score`
- **#Views:** 290000 (as of September 29, 2025)
- **#Downloads:** 50200 (as of September 29, 2025)
- **Additional Description:** You are working as a data scientist in a global finance company. Over the years, the company has collected basic bank details and gathered a lot of credit-related information. The management wants to build an intelligent system to segregate the people into credit score brackets to reduce the manual efforts. This dataset provides a comprehensive view of customer profiles, encompassing demographic details, financial histories, and payment patterns that play a crucial role in evaluating credit risk. The goal is to clean and analyze this data to identify key features suitable for training Machine Learning and Deep Learning Algorithms.
- **Features:** <br>
`id`	Unique identifier for each record.<br>
`customer_id`	Unique identifier for each customer.<br>
`month`	Month of the transaction or record.<br>
`name`	Customer’s name.<br>
`age`	The customer’s age.<br>
`ssn`	Customer’s social security number.<br>
`occupation`	The customer’s occupation.<br>
`annual_income`	The customer’s annual income.<br>
`monthly_inhand_salary`	The customer’s monthly take-home salary.<br>
`num_bank_accounts`	Total number of bank accounts owned by the customer.<br>
`num_credit_card`	Total number of credit cards held by the customer.<br>
`interest_rate`	The interest rate applied to loans or credits.<br>
`num_of_loan`	Number of loans the customer has taken.<br>
`type_of_loan`	Categories of loans obtained by the customer.<br>
`delay_from_due_date`	The delay in payment relative to the due date.<br>
`num_of_delayed_payment`	Total instances of late payments made by the customer.<br>
`changed_credit_limit`	Adjustments made to the customer’s credit limit.<br>
`num_credit_inquiries`	Number of inquiries made regarding the customer's credit.<br>
`credit_mix`	The variety of credit types the customer uses (e.g., loans, credit cards).<br>
`outstanding_debt`	Total amount of debt the customer currently owes.<br>
`credit_utilization_ratio`	Proportion of credit used compared to the total credit limit.<br>
`credit_history_age`	Duration of the customer’s credit history.<br>
`payment_of_min_amount`	Indicates if the customer pays the minimum required amount each month.<br>
`total_emi_per_month`	Total Equated Monthly Installment (EMI) paid by the customer.<br>
`amount_invested_monthly`	Monthly investment amount made by the customer.<br>
`payment_behaviour`	Customer’s payment habits and tendencies.<br>
`monthly_balance`	The remaining balance in the customer’s account at the end of each month.<br>
`credit_score (Target)`	The customer’s credit score (target variable: "Good," "Poor," "Standard").<br>
- **Model Performance:** 
![Model Performance](./results/NA) -->

<!-- ## 10. `credit-fraud`
- **Description:** 
- **Source:** <a href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data">Kaggle</a>
- **File:**  ![creditcardfraud.csv](./datasets/creditcardfraud.csv)
- **#Rows:** 284,807
- **#Features:** 31
- **Target:** `Class`
- **#Views:**  12100000 (as of September 29, 2025)
- **#Downloads:** 990000 (as of September 29, 2025)
- **Additional Description:** "It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection. More details on current and past projects on related topics are available on https://www.researchgate.net/project/Fraud-detection-5 and the page of the DefeatFraud project"
- **Features:** <br>
`Time`	`V1`	`V2`	`V3`	`V4`	`V5`	`V6`	`V7`	`V8`	`V9`	`V10`	`V11`	`V12`	`V13`	`V14`	`V15`	`V16`	`V17`	`V18`	`V19`	`V20`	`V21`	`V22`	`V23`	`V24`	`V25`	`V26`	`V27`	`V28`	`Amount`	`Class (Target)`
- **Model Performance:** 
![Model Performance](./results/NA) -->

## 8. `hmeq`
- **Description:** The Home Equity dataset (HMEQ) contains baseline and loan performance information for 5,960 recent home equity loans. The target (BAD) is a binary variable indicating whether an applicant eventually defaulted or was seriously delinquent. This adverse outcome occurred in 1,189 cases (20%). For each applicant, 12 input variables were recorded.
- **Source:** <a href="https://www.kaggle.com/datasets/ajay1735/hmeq-data/">Kaggle</a>
- **File:**  ![hmeq.csv](./datasets/hmeq.csv)
- **#Rows:** 5960
- **#Features:** 13
- **Target:** `BAD`
- **#Views:**  77300 (as of September 29, 2025)
- **#Downloads:** 9017 (as of September 29, 2025)
- **Additional Description:** 
The consumer credit department of a bank wants to automate the decisionmaking process for approval of home equity lines of credit. To do this, they will follow the recommendations of the Equal Credit Opportunity Act to create an empirically derived and statistically sound credit scoring model. The model will be based on data collected from recent applicants granted credit through the current process of loan underwriting. The model will be built from predictive modeling tools, but the created model must be sufficiently interpretable to provide a reason for any adverse actions (rejections).
- **Features:** <br>
`LOAN` Amount of the loan request<br>
`MORTDUE` Amount due on existing mortgage<br>
`VALUE` Value of current property<br>
`REASON` DebtCon = debt consolidation HomeImp = home improvement<br>
`JOB` Six occupational categories<br>
`YOJ` Years at present job<br>
`DEROG` Number of major derogatory reports<br>
`DELINQ` Number of delinquent credit lines<br>
`CLAGE` Age of oldest trade line in months<br>
`NINQ` Number of recent credit lines<br>
`CLNO` Number of credit lines<br>
`DEBTINC` Debt-to-income ratio<br>
`BAD (Target)` 1 = client defaulted on loan 0 = loan repaid<br>
- **Model Performance:** 
![Model Performance](./results/plot_8_hmeq.png)

## 9. `loan-approval`
- **Description:** Loan Approval Dataset used for Prediction Model 
- **Source:** <a href="https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset">Kaggle</a>
- **File:**  ![loan_approval_dataset.csv](./datasets/loan_approval_dataset.csv)
- **#Rows:** 4269
- **#Features:** 13
- **Target:** `loan_status`
- **#Views:**  143000 (as of September 29, 2025)
- **#Downloads:** 33800 (as of September 29, 2025)
- **Additional Description:**  The loan approval dataset is a collection of financial records and associated information used to determine the eligibility of individuals or organizations for obtaining loans from a lending institution. It includes various factors such as cibil score, income, employment status, loan term, loan amount, assets value, and loan status. This dataset is commonly used in machine learning and data analysis to develop models and algorithms that predict the likelihood of loan approval based on the given features.
- **Features:** <br>
`loan_id` : ID<br>
`no_of_dependents`: Number of Dependents of the Applicant<br>
`education`: Education of the Applicant (Graduate/Not Graduate)<br>
`self_employed`: Employment Status of the Applicant<br>
`income_annum`: Annual Income of the Applicant<br>
`loan_amount`: Loan Amount<br>
`loan_term`: Loan Term in Years<br>
`cibil_score`: Credit Score<br>
`residential_assets_value`: Amount of Residential Assests <br>
`commercial_assets_value`: Amount of Commercial Assests <br>
`luxury_assets_value`: Amount of Luxury Items Assests <br>
`bank_asset_value`: Amount of Bank Assests <br>
`loan_status (Target)`: Loan Approval Status (Approved/Rejected)<br>
- **Model Performance:** 
![Model Performance](./results/plot_9_loan_approval.png)

## 10. `loan-repay`
- **Description:** Use the lending data from 2007-2010 to classify and predict whether or not the borrower paid back their loan in full
- **Source:** <a href="https://www.kaggle.com/datasets/itssuru/loan-data">Kaggle</a>
- **File:**  ![loan_data.csv](./datasets/loan_data.csv)
- **#Rows:** 9578
- **#Features:** 14
- **Target:** `not fully paid.`
- **#Views:**  86200 (as of September 29, 2025)
- **#Downloads:**  14900 (as of September 29, 2025)
- **Additional Description:** Publicly available data from LendingClub.com. Lending Club connects people who need money (borrowers) with people who have money (investors). Hopefully, as an investor you would want to invest in people who showed a profile of having a high probability of paying you back.
- **Features:** <br>
`credit.policy`: This binary feature reflects whether the borrower meets LendingClub.com's credit underwriting criteria (1) or not (0). This indicator is crucial as it signifies the outcome of the initial creditworthiness assessment based on the lender's policy.<br>
`purpose`: A categorical variable that represents the loan's purpose, including categories like 'credit_card', 'debt_consolidation', 'educational', 'major_purchase', 'small_business', and 'all_other'. The purpose of the loan is vital as it influences the loan's risk profile and the likelihood of repayment.<br>
`int.rate`: The loan's interest rate represented as a proportion (e.g., 0.11 for 11%). Interest rates are pivotal as they reflect the lender's risk assessment—higher rates often correlate with perceived higher borrower risk.<br>
`installment`: The monthly installment amount the borrower must pay if the loan is funded. Installments are significant as their size can impact the borrower's repayment capacity, especially relative to their income and other debts.<br>
`log.annual.inc`: The natural logarithm of the borrower's self-reported annual income. Employing the logarithm reduces income distribution skewness, facilitating better modeling.<br>
`dti`: The debt-to-income ratio, computed as debt divided by annual income. A higher DTI suggests that a large income portion is allocated to debt servicing, potentially affecting loan repayment.<br>
`fico`: The FICO credit score, a critical measure of creditworthiness influencing loan approval and terms.<br>
`days.with.cr.line`: The number of days the borrower has had a credit line, where longer histories might imply more financial reliability.<br>
`revol.bal`: The borrower's unpaid balance at the credit cycle end, with higher balances possibly indicating financial strain.<br>
`revol.util`: The rate at which the borrower utilizes their revolving credit line. Higher rates can signify elevated credit risk.<br>
`inq.last.6mths`: The count of credit inquiries in the last six months, where more inquiries can suggest increased credit-seeking behavior and potential risk.<br>
`delinq.2yrs`: Instances of being 30+ days late on payments in the past two years, reflecting on the borrower's reliability.
`pub.rec`: The count of derogatory public records like bankruptcy filings or tax liens, which can significantly impact creditworthiness.<br>
`not.fully.paid (Target)`: The binary target variable indicating whether the loan was not fully repaid (1) or was (0). Our predictive modeling efforts focus on this outcome.
- **Model Performance:** 
![Model Performance](./results/plot_10_loan_repay.png)

## 14. `dummy`
- **Description:** 
- **Source:** <a href=""></a>
- **#Rows:** 
- **#Features:** 
- **Target:** ``
- **#Views:**  (as of Month x, 2025)
- **#Downloads:**  (as of Month x, 2025)
- **#Citations:**
- **Additional Description:**
- **Features:** <br>


---

**Contact:** For questions or contributions, reach out to me @ anshulg2743@gmail.com.
