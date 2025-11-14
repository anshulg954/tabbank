This file contains detailed description about each of the datasets to be considered for checking TabPFN performance.​

The datasets have entries less than 50K.

DISCLAIMER!!! --> The content is generated with the assistance of LLM.

---

# Customer Lifetime Management Domain​
## 1. `Telecom churn dataset​`
- **Description:** Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs.
- **Source:** <a href="https://www.kaggle.com/datasets/mnassrib/telecom-churn-datasets">Kaggle</a>
- **File:** ![telecom churn dataset.csv](.datasets/customer-lifetime-management/less-than-50K/classification/telecom churn dataset.csv)​
- **#Rows:** ~2,600
- **#Features:** 19
- **Target:** `Churn​`
- **#Views:** Not specified​
- **Additional Description:** Suitable for baseline churn modeling, feature importance analysis, and threshold‑sensitive retention policies.​
- **Features:** <br>
`State`: Two‑letter customer state code<br>
`Account length`: Number of days the account has been active.<br>
`Area code`: Customer phone area code<br>
`International plan`: Has international calling plan (Yes/No)<br>
`Voice mail plan`: Has voicemail plan (Yes/No)<br>
`Number vmail messages`: Count of voicemail messages<br>
`Total day minutes`: Daytime call minutes<br>
`Total day calls`: Daytime call count<br>
`Total day charge`: Daytime call charges<br>
`Total eve minutes`: Evening call minutes<br>
`Total eve calls`: Evening call count<br>
`Total eve charge`: Evening call charges<br>
`Total night minutes`: Night call minutes<br>
`Total night calls`: Night call count<br>
`Total night charge`: Night call charges<br>
`Total intl minutes`: International call minutes<br>
`Total intl calls`: International call count<br>
`Total intl charge`: International call charges<br>
`Customer service calls`: Number of customer service interactions<br>
`Churn`: Target indicator (TRUE/FALSE)<br>


## 2. `Telco-Customer-Churn`
- **Description:** Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs.
- **Source:** <a href="https://www.kaggle.com/datasets/blastchar/telco-customer-churn">Kaggle</a>
- **File:** ![Telco-Customer-Churn.csv](.datasets/customer-lifetime-management/less-than-50K/classification/Telco-Customer-Churn.csv)
- **#Rows:** ~7,043
- **#Features:** 21 (including target)
- **Target:** `Churn`
- **#Views:** Not specified
- **Additional Description:** Widely used telecom benchmark with monthly/total charges and a comprehensive set of service add‑ons.
- **Features:** <br>
`customerID`: Unique customer identifier.<br>
`gender`: Customer gender.<br>
`SeniorCitizen`: Senior citizen indicator.<br>
`Partner`: Whether the customer has a partner.<br>
`Dependents`: Whether the customer has dependents.<br>
`tenure`: Months the customer has stayed.<br>
`PhoneService`: Indicates phone line service.<br>
`MultipleLines`: Multiple phone lines indicator.<br>
`InternetService`: Type of internet service.<br>
`OnlineSecurity`: Online security add‑on.<br>
`OnlineBackup`: Online backup add‑on.<br>
`DeviceProtection`: Device protection add‑on.<br>
`TechSupport`: Technical support add‑on.<br>
`StreamingTV`: Streaming TV add‑on.<br>
`StreamingMovies`: Streaming movies add‑on.<br>
`Contract`: Contract term.<br>
`PaperlessBilling`: Paperless billing flag.<br>
`PaymentMethod`: Payment method category.<br>
`MonthlyCharges`: Monthly billing amount.<br>
`TotalCharges`: Total lifetime charges.<br>
`Churn`: Target churn flag.<br>


## 3. `Iranian telecom churn`
- **Description:** Customer, usage, and service details for a telecom operator in Iran to predict churn propensity.
- **Source:** <a href="https://archive.ics.uci.edu/dataset/563/iranian+churn+dataset">UCIICS</a>
- **File:** ![Iranian telecom churn.csv](.datasets/customer-lifetime-management/less-than-50K/classification/Iranian telecom churn.csv)
- **#Rows:** ~3,100
- **#Features:** 12 (including target)
- **Target:** `Churn`
- **#Views:** Not specified
- **Additional Description:** Compact feature set practical for rapid benchmarking and class‑imbalance handling.
- **Features:** <br>
`Charge Amount`: Amount charged against customer.<br>
`Call Failure`: Number of failed calls.<br>
`Complains`: Count of customer complaints.<br>
`Subscribed Length`: Current plan type.<br>
`Seconds Of Use`: Total usage in seconds.<br>
`Frequency Of use`: Number of usage.<br>
`Frequency Of SMS`: Number of SMS sent.<br>
`Distinct Called Numbers`: Unique numbers called.<br>
`Status`: Status of customer.<br>
`Age`: Age of customer.<br>
`Customer Value`: Revenue/value per user.<br>
`Age Group`: Customer age bracket.<br>
`Tariff Plan`: The tariff plan.<br>
`Churn`: Target churn status.<br>


## 4. `IBM-Employee-Attrition`
- **Description:** HR analytics dataset to predict whether an employee will exit using demographics, compensation, role, and engagement.
- **Source:** <a href="https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset">Kaggle</a>
- **File:** ![IBM-Employee-Attrition.csv](.datasets/customer-lifetime-management/less-than-50K/classification/IBM-Employee-Attrition.csv)
- **#Rows:** ~1,470
- **#Features:** 35 (including target)
- **Target:** `Attrition`
- **#Views:** Not specified
- **Additional Description:** Useful for feature importance, fairness diagnostics, and HR policy simulation.
- **Features:** <br>
`Age`: Employee age.<br>
`BusinessTravel`: Travel frequency.<br>
`DailyRate`: Daily pay rate.<br>
`Department`: Department name.<br>
`DistanceFromHome`: Commute distance.<br>
`Education`: Education level.<br>
`EducationField`: Field of study.<br>
`EmployeeCount`: Count of Employee.<br>
`EmployeeNumber`: Number of Employee.<br>
`EnvironmentSatisfaction`: Work environment satisfaction.<br>
`Gender`: Employee gender.<br>
`HourlyRate`: Hourly pay rate.<br>
`JobInvolvement`: Involvement score.<br>
`JobLevel`: Seniority level.<br>
`JobRole`: Role title.<br>
`JobSatisfaction`: Job satisfaction score.<br>
`MaritalStatus`: Marital status.<br>
`MonthlyIncome`: Monthly income.<br>
`MonthlyRate`: Monthly rate figure.<br>
`NumCompaniesWorked`: Past employers count.<br>
`Over18`: Over‑18 flag.<br>
`OverTime`: Overtime status.<br>
`PercentSalaryHike`: Raise percentage.<br>
`PerformanceRating`: Performance rating.<br>
`RelationshipSatisfaction`: Relationship satisfaction.<br>
`StandardHours`: Standard working hours.<br>
`StockOptionLevel`: Stock options tier.<br>
`TotalWorkingYears`: Total years worked.<br>
`TrainingTimesLastYear`: Training count.<br>
`WorkLifeBalance`: Work‑life rating.<br>
`YearsAtCompany`: Tenure at company.<br>
`YearsInCurrentRole`: Years in current role.<br>
`YearsSinceLastPromotion`: Years since promotion.<br>
`YearsWithCurrManager`: Years with current manager.<br>
`Attrition`: Target label.<br>


## 5. `gym_customer_churn`
- **Description:** Gym membership data with activity, payments, and contract info to predict churn.
- **Source:** <a href="https://www.kaggle.com/datasets/adrianvinueza/gym-customers-features-and-churn/data">Kaggle</a>
- **File:** ![gym_customer_churn.csv](.datasets/customer-lifetime-management/less-than-50K/classification/gym_customer_churn.csv)
- **#Rows:** ~4,000
- **#Features:** ~13 (including target)
- **Target:** `Churn`
- **#Views:** Not specified
- **Additional Description:** Covers visits, class participation, tenure, payment method, and satisfaction.
- **Features:** <br>
`Near_Location`: Whether the location of gym is in vicinity.<br>
`Gender`: Member gender.<br>
`Age`: Age in years.<br>
`Partner`: Do they bring a partner along.<br>
`Promo_friends`: If they used promotional code from friends.<br>
`Phone`: Whether phone number is available.<br>
`Contract_period`: Number of months of contract.<br>
`Group_visits`: Do the customer visit in groups.<br>
`Avg_additional_charges_total`: Additional amount charged.<br>
`Month_to_end_contract`: Months left in contract.<br>
`Lifetime`: Lifetime of customer membership in the gym.<br>
`Avg_class_frequency_total`: Average number of classes attended.<br>
`Avg_class_frequency_current_month`: Average number of classes attended this month.<br>
`Churn`: Target churn outcome.<br>


## 6. `Ecommerce_Consumer_Behavior_Analysis_Data`
- **Description:** Analyze consumer features to detect utilities such as which products to offer and to which customer category for improved targeting and retention.
- **Source:** <a href="https://www.kaggle.com/datasets/salahuddinahmedshuvo/ecommerce-consumer-behavior-analysis-data">Kaggle</a>
- **File:** ![Ecommerce_Consumer_Behavior_Analysis_Data.csv](.datasets/customer-lifetime-management/less-than-50K/classification/Ecommerce_Consumer_Behavior_Analysis_Data.csv)
- **#Rows:** 1000
- **#Features:** 26
- **Target:** Task‑dependent (e.g., CustomerSatisfaction or PurchaseIntent per analysis goal)
- **#Views:** Not specified
- **Additional Description:** Balanced mix of demographics, channel and device usage, purchase frequency and amounts, ad engagement, discounts, loyalty, and shipping preferences suitable for segmentation, uplift, and supervised modeling.
- **Features:** <br>
`CustomerID`: Unique customer identifier for joining and segmentation.<br>
`Age`: Age band for demographic profiling.<br>
`Gender`: Self‑identified gender category including non‑binary options.<br>
`Income_Level`: Income bracket indicating spending capacity.<br>
`Marital_Status`: Marital status used for lifestyle segmentation.<br>
`Education_Level`: Highest education attained.<br>
`Occupation`: Employment/occupation type for persona building.<br>
`Location`: City/region used for geo‑targeting.<br>
`Purchase_Category`: Primary category of purchased items (e.g., Electronics, Groceries).<br>
`Purchase_Amount`: Monetary value of the purchase in the record.<br>
`Frequency_of_Purchase`: Purchase cadence over a period.<br>
`Purchase_Channel`: Channel used (Online, In‑Store, Mixed).<br>
`Brand_Loyalty`: Loyalty attachment to preferred brands (e.g., Low/Medium/High).<br>
`Product_Rating`: Rating provided for purchased products.<br>
`Time_Spent_on_Product_Research(hours)`: Hours spent researching before purchase.<br>
`Social_Media_Influence`: Level of social influence on buying decision.<br>
`Discount_Sensitivity`: Sensitivity to discounts and promotions.<br>
`Return_Rate`: Frequency of product returns by the customer.<br>
`Engagement_with_Ads`: Degree of ad engagement across channels.<br>
`Device_Used_for_Shopping`: Primary shopping device (Desktop/Tablet/Smartphone).<br>
`Payment_Method`: Method used for payment (e.g., Credit Card, PayPal).<br>
`Time_of_Purchase`: Time context of the transaction (hour/period).<br>
`Discount_Used`: Whether a discount/coupon was applied.<br>
`Customer_Loyalty_Program_Member`: Loyalty program membership flag.<br>
`Purchase_Intent`: Declared intent type (e.g., Planned, Impulsive, Need‑based, Wants‑based).<br>
`Shipping_Preference`: Preferred shipping option (Standard/Express/No Preference).<br>
`Time_to_Decision`: Time taken from consideration to purchase decision.<br>
`Customer_Satisfaction`: Post‑purchase satisfaction score used as a potential target.<br>


## 7. `Starbucks customer survey`
- **Description:** Predict behavior to retain customers using survey responses on visit frequency, preferences, spend, product choices, membership, perceived quality, price, promotions, ambiance, Wi‑Fi, service, meeting/hangout likelihood, promo channels, and continuation intent.
- **Source:** <a href="https://www.kaggle.com/datasets/mahirahmzh/starbucks-customer-retention-malaysia-survey?select=Starbuckssatisfactorysurvey.csv">Kaggle</a>
- **File:** ![Starbucks-customer-survey.csv](.datasets/customer-lifetime-management/less-than-50K/classification/Starbucks-customer-survey.csv)
- **#Rows:** 122
- **#Features:** 20
- **Target:** Task‑dependent (e.g., "Will you continue buying at Starbucks?" or satisfaction/loyalty proxy)
- **#Views:** Not specified
- **Additional Description:** Responses include demographics, visit context, distance to outlet, spend band, and multiple Likert‑scale ratings that are suitable for satisfaction modeling and churn propensity proxies.
- **Features:** <br>
`Timestamp`: Submission timestamp of the survey response.<br>
`1. Your Gender`: Respondent gender category.<br>
`2. Your Age`: Age bracket of the respondent.<br>
`3. Are you currently....?`: Current status such as student, employed, self‑employed, etc.<br>
`4. What is your annual income?`: Income band indicator.<br>
`5. How often do you visit Starbucks?`: Visit frequency measure.<br>
`6. How do you usually enjoy Starbucks?`: Mode of consumption (dine‑in, takeaway, drive‑thru).<br>
`7. How much time do you normally spend during your visit?`: Typical visit duration.<br>
`8. The nearest Starbuckss outlet to you is...?`: Distance to nearest outlet.<br>
`9. Do you have Starbucks membership card?`: Membership status flag.<br>
`10. What do you most frequently purchase at Starbucks?`: Most frequent purchase category (coffee, cold drinks, pastries, etc.).<br>
`11. On average, how much would you spend at Starbucks per visit?`: Spend band per visit.<br>
`12. How would you rate the quality of Starbucks compared to other brands Coffee Bean, Old Town White Coffee.. to be`: Relative quality rating versus competitors.<br>
`13. How would you rate the price range at Starbucks?`: Price perception rating.<br>
`14. How important are sales and promotions in your purchase decision?`: Importance of promotions in decisions.<br>
`15. How would you rate the ambiance at Starbucks? lighting, music, etc...`: Ambiance rating.<br>
`16. You rate the WiFi quality at Starbucks as..`: Wi‑Fi quality rating.<br>
`17. How would you rate the service at Starbucks? Promptness, friendliness, etc..`: Service rating.<br>
`18. How likely you will choose Starbucks for doing business meetings or hangout with friends?`: Likelihood of choosing Starbucks for meetings/hangouts.<br>
`19. How do you come to hear of promotions at Starbucks? Check all that apply.`: Promo awareness channels (website, app, social media, email, word of mouth, in‑store, billboards, etc.).<br>
`20. Will you continue buying at Starbucks?`: Continuation/retention intention, usable as a classification target.<br>


## 8. `The role of advertisement on the consumer behaviour`
- **Description:** Understand the effect of advertisement on customer behaviour using a survey covering demographics, shopping habits, preferred ad types/channels, exposure frequency, search and recall behavior, and purchase influence.
- **Source:** <a href="https://www.kaggle.com/datasets/abdelrahmanosheba/the-role-of-advertisement-on-the-consumer-behavior">Kaggle</a>
- **File:** ![The-role-of-advertisement-on-the-consumer-behaviour.csv](.datasets/customer-lifetime-management/less-than-50K/classification/The-role-of-advertisement-on-the-consumer-behaviour.csv)
- **#Rows:** 64
- **#Features:** 22
- **Target:** Task‑dependent (e.g., "Did you buy due to an advertisement?" or "Did the advert change your buying behavior?")
- **#Views:** Not specified
- **Additional Description:** Items include frequency of ad exposure, whether respondents search for ads, comparative preference for TV vs internet ads, ad paradigms dealt with, usefulness of ad information, and what elements of ads drive purchases.
- **Features:** <br>
`? What is your gender`: Respondent gender.<br>
`? Are you a shopping person`: Whether the respondent generally likes shopping.<br>
`? Rate your shopping behavior out of 5`: Self‑rated shopping enthusiasm on a 1–5 scale.<br>
`? Are you a heavy shopper`: Heavy shopper indicator.<br>
`? How many times do you go to super market a week (nearly)`: Weekly supermarket visit frequency.<br>
`What is the most entertainment ad you watched recently ?`: Most entertaining ad recently seen.<br>
`Type of ads you prefer or watch ?`: Preferred ad type (e.g., funny, emotional, cartoon).<br>
`How many adverts do you watch ads daily (nearly) ?`: Approximate number of ads seen daily.<br>
`Do you prefer internet ads or tv ads more ?`: Channel preference between internet and TV.<br>
`Have you ever search for an advert advert before ?`: Whether respondents have ever searched for an advert.<br>
`-        What is youâ€™re the most advert paradigm(method) you deal with ?`: Main advertising paradigm/method engaged with.<br>
`What do you watch more: TV advertisements or social media(internet) advertisements ?`: Dominant exposure medium.<br>
`How many times did you search for an advert ? (nearly)`: Frequency of searching for ads.<br>
`When I watch advertisements I buy or go shopping ?`: Self‑reported immediate purchase behavior after ads.<br>
`After watching advertisements, do you search for it ?`: Post‑exposure search behavior.<br>
`Have you ever bought something due to an advertisements ?`: Purchase made due to ads indicator.<br>
`Did you think that the advert can change your buying behavior ?`: Perceived influence of ads on buying behavior.<br>
`Did you find information in the adverts beneficial ?`: Utility of ad information.<br>
`Do you think that advertisements is important for businesses ?`: Perceived importance of advertising for firms.<br>
`What do you think can make you buy from an advert ? [The way introducing product]`: Influence of product presentation style.<br>
`What do you think can make you buy from an advert ? [the script]`: Influence of ad scripting/content.<br>
`What do you think can make you buy from an advert ? [the actors that work on]`: Influence of actors/cast in the advert.<br>
`What do you think can make you buy from an advert ? [the company made it]`: Influence of brand/company behind the ad.<br>


## 9. `travels-customer-churn-prediction`
- **Description:** A travel company wants to predict if a customer will churn based on key indicators including frequent flyer status, income band, service bundle selection, social media sync, and hotel booking behavior.
- **Source:** <a href="https://www.kaggle.com/datasets/tejashvi14/tour-travels-customer-churn-prediction-data">Kaggle</a>
- **File:** ![travels-customer-churn-prediction.csv](.datasets/customer-lifetime-management/less-than-50K/classification/travels-customer-churn-prediction.csv)
- **#Rows:** 950
- **#Features:** 6
- **Target:** `Target`
- **#Views:** Not specified
- **Additional Description:** Compact, balanced schema suitable for quick benchmarking of churn classification and explainability with categorical features and binary outcomes.
- **Features:** <br>
`Age`<br>
`FrequentFlyer`<br>
`AnnualIncomeClass`<br>
`ServicesOpted`<br>
`AccountSyncedToSocialMedia`<br>
`BookedHotelOrNot`<br>
`Target`<br>


## 10. `synthetic_insurance_data`
- **Description:** Synthetic personal auto insurance records with demographics, policy, discounts, claims, lead source, digital engagement, credit/regional adjustments, and conversion outcome for full‑funnel modeling.
- **Source:** <a href="https://www.kaggle.com/datasets/samialyasin/insurance-data-personal-auto-line-of-business">Kaggle</a>
- **File:** ![synthetic_insurance_data.csv](.datasets/customer-lifetime-management/less-than-50K/classification/synthetic_insurance_data.csv)
- **#Rows:** ~10,000
- **#Features:** 27
- **Target:** `Conversion_Status`
- **#Views:** Not specified
- **Additional Description:** Columns include multiple discount levers and credit/region adjustments enabling pricing sensitivity analysis alongside source performance and time‑to‑conversion signals.
- **Features:** <br>
`Age`: Age of customer.<br>
`Is_Senior`: Senior citizen flag.<br>
`Marital_Status`: Marital status.<br>
`Married_Premium_Discount`: Premium discount for married customers.<br>
`Prior_Insurance`: Prior insurance status.<br>
`Prior_Insurance_Premium_Adjustment`: Premium adjustment based on prior insurance.<br>
`Claims_Frequency`: Frequency of claims.<br>
`Claims_Severity`: Severity of claims.<br>
`Claims_Adjustment`: Premium adjustment based on claims.<br>
`Policy_Type`: Type of policy.<br>
`Policy_Adjustment`: Adjustment based on policy type.<br>
`Premium_Amount`: Premium amount.<br>
`Safe_Driver_Discount`: Discount for safe drivers.<br>
`Multi_Policy_Discount`: Discount for multiple policies.<br>
`Bundling_Discount`: Discount for bundling policies.<br>
`Total_Discounts`: Total discounts applied.<br>
`Source_of_Lead`: Lead generation source.<br>
`Time_Since_First_Contact`: Time elapsed since first contact.<br>
`Website_Visits`: Number of website visits.<br>
`Inquiries`: Number of inquiries made.<br>
`Quotes_Requested`: Number of quotes requested.<br>
`Time_to_Conversion`: Time taken for conversion.<br>
`Credit_Score`: Credit score of customer.<br>
`Premium_Adjustment_Credit`: Premium adjustment based on credit.<br>
`Region`: Geographic region.<br>
`Premium_Adjustment_Region`: Premium adjustment based on region.<br>
`Conversion_Status`: Target conversion status.<br>


## 11. `insurance-customer-lifetime-value`
- **Description:** Using this data, insurers can identify high‑value customers, predict churn, and optimize retention strategies through actionable insights.
- **Source:** <a href="https://gomask.ai/marketplace/datasets/insurance-customer-lifetime-value">GoMask marketplace</a>
- **File:** ![insurance-customer-lifetime-value.csv](.datasets/customer-lifetime-management/less-than-50K/classification/insurance-customer-lifetime-value.csv)
- **#Rows:** 200
- **#Features:** 15
- **Target:** `ischurned`
- **#Views:** Not specified
- **Additional Description:** Records combine customer demographics and full address fields with policy metadata, premiums, claims, CLV, churn risk score, last interaction and preferred contact, enabling end‑to‑end lifecycle modeling.
- **Features:** <br>
`customerid`: Customer identifier.<br>
`firstname`: Customer's first name.<br>
`lastname`: Customer's last name.<br>
`dateofbirth`: Customer's date of birth.<br>
`gender`: Customer's gender.<br>
`email`: Customer's email address.<br>
`phonenumber`: Customer's phone number.<br>
`addressstreet`: Street address.<br>
`addresscity`: City of residence.<br>
`addressstate`: State of residence.<br>
`addresspostalcode`: Postal code.<br>
`addresscountry`: Country of residence.<br>
`policyid`: Policy identifier.<br>
`policytype`: Type of insurance policy.<br>
`policystartdate`: Policy start date.<br>
`policyenddate`: Policy end date.<br>
`annualpremium`: Annual premium amount.<br>
`totalclaims`: Number of claims filed.<br>
`totalclaimamount`: Total amount claimed.<br>
`customerlifetimevalue`: Customer lifetime value.<br>
`churnriskscore`: Risk score for churn.<br>
`lastinteractiondate`: Date of last interaction.<br>
`preferredcontactmethod`: Preferred method of contact.<br>
`ischurned`: Churn status indicator.<br>


## 12. `financial-customer-lifetime-value`
- **Description:** Similar to insurance customer lifetime value but for financial services; supports identifying high‑value customers, predicting churn, and optimizing retention and cross‑sell strategies.
- **Source:** <a href="https://gomask.ai/marketplace/datasets/financial-customer-lifetime-value">GoMask marketplace</a>
- **File:** ![financial-customer-lifetime-value.csv](.datasets/customer-lifetime-management/less-than-50K/classification/financial-customer-lifetime-value.csv)
- **#Rows:** 200
- **#Features:** 15
- **Target:** `ischurned`
- **#Views:** Not specified
- **Additional Description:** Combines customer profile, product type, granular transaction history with timestamps and amounts, retention duration, churn date flags, lifetime value, multi‑currency support, and churn status, enabling both classification and survival‑style analysis.
- **Features:** <br>
`customerid`: Customer identifier.<br>
`customername`: Customer's full name.<br>
`customeremail`: Customer's email address.<br>
`customerphone`: Customer's phone number.<br>
`customerjoindate`: Date customer joined.<br>
`productid`: Product identifier.<br>
`producttype`: Type of financial product.<br>
`transactionid`: Transaction identifier.<br>
`transactiondate`: Date of transaction.<br>
`transactionamount`: Amount of transaction.<br>
`transactiontype`: Type of transaction.<br>
`retentionperiodmonths`: Months customer was retained.<br>
`churndate`: Date customer churned.<br>
`lifetimevalue`: Customer lifetime value.<br>
`currency`: Transaction currency code.<br>
`ischurned`: Churn status indicator.<br>


## 13. `Customer Personality Analysis`
- **Description:** Household demographics, category spending, and campaign responses to segment and predict purchase behavior.
- **Source:** <a href="https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis">Kaggle</a>
- **File:** ![customer personality analysis.csv](.datasets/customer-lifetime-management/less-than-50K/classification/customer personality analysis.csv)
- **#Rows:** ~2,000
- **#Features:** 29 (including target)
- **Target:** `Response`
- **#Views:** Not specified
- **Additional Description:** Includes recency, spend by category, and campaign acceptances for uplift and segmentation tasks.
- **Features:** <br>
`ID`: Customer identifier.<br>
`Year_Birth`: Year of birth.<br>
`Education`: Education level.<br>
`Marital_Status`: Marital status.<br>
`Income`: Annual household income.<br>
`Kidhome`: Number of kids at home.<br>
`Teenhome`: Number of teens at home.<br>
`Dt_Customer`: Enrollment date.<br>
`Recency`: Days since last purchase.<br>
`MntWines`: Spend on wine.<br>
`MntFruits`: Spend on fruits.<br>
`MntMeatProducts`: Spend on meat.<br>
`MntFishProducts`: Spend on fish.<br>
`MntSweetProducts`: Spend on sweets.<br>
`MntGoldProds`: Spend on gold products.<br>
`NumDealsPurchases`: Purchases with deals.<br>
`NumWebPurchases`: Online purchase count.<br>
`NumCatalogPurchases`: Catalog purchase count.<br>
`NumStorePurchases`: In‑store purchase count.<br>
`NumWebVisitsMonth`: Web visits per month.<br>
`AcceptedCmp3`: Campaign 3 acceptance.<br>
`AcceptedCmp4`: Campaign 4 acceptance.<br>
`AcceptedCmp5`: Campaign 5 acceptance.<br>
`AcceptedCmp1`: Campaign 1 acceptance.<br>
`AcceptedCmp2`: Campaign 2 acceptance.<br>
`Complain`: Complaint indicator.<br>
`Z_CostContact`: Cost control variable.<br>
`Z_Revenue`: Revenue control variable.<br>
`Response`: Target response to last campaign.<br>


## 14. `R_acquisitionRetention`
- **Description:** Acquisition–Retention data from Chapter 5 of Kumar and Petersen (2012), designed for modeling acquisition probability, retention duration, CLV, and marketing spend effects including squared terms for nonlinear response.
- **Source:** <a href="https://cran.r-project.org/web/packages/SMCRM/SMCRM.pdf">CRAN: SMCRM package</a> (see page 2, “acquisitionRetention”)
- **File:** ![R_acquisitionRetention.csv](.datasets/customer-lifetime-management/less-than-50K/classification/R_acquisitionRetention.csv)
- **#Rows:** 500 (book dataset spec)
- **#Features:** 15
- **Target:** acquisition
- **#Views:** Not applicable
- **Additional Description:** Variables include marketing acquisition/retention expenses and their squares, purchase frequency and its square, cross‑buy, share‑of‑wallet, and firmographics (industry, revenue, employees) for end-to-end CLV and retention modeling.
- **Features:** <br>
`customer`: customer number (from 1 to 500).<br>
`acquisition`: 1 if the prospect was acquired, 0 otherwise.<br>
`duration`: number of days the customer was a customer of the firm, 0 if acquisition == 0.<br>
`profit`: customer lifetime value (CLV) of a given customer, -(Acq_Exp) if the customer is not acquired.<br>
`acq_exp`: total dollars spent on trying to acquire this prospect.<br>
`ret_exp`: total dollars spent on trying to retain this customer.<br>
`acq_exp_sq`: square of the total dollars spent on trying to acquire this prospect.<br>
`ret_exp_sq`: square of the total dollars spent on trying to retain this customer.<br>
`freq`: number of purchases the customer made during that customer’s lifetime with the firm, 0 if acquisition == 0.<br>
`freq_sq`: square of the number of purchases the customer made during that customer’s lifetime.<br>
`crossbuy`: number of product categories the customer purchased from during that customer’s lifetime, 0 if acquisition = 0.<br>
`sow`: Share-of-Wallet; percentage of purchases the customer makes from the given firm given the total amount of purchases across all firms in that category.<br>
`industry`: 1 if the customer is in the B2B industry, 0 otherwise.<br>
`revenue`: annual sales revenue of the prospect’s firm (in millions of dollar).<br>
`employees`: number of employees in the prospect’s firm.<br>


## 15. `R_customerAcquisition`
- **Description:** Customer Acquisition data from Chapter 3 capturing whether a prospect was acquired, early purchase value, predicted CLV, exposure window with right‑censoring, acquisition and retention marketing spend (with squared terms), firmographics, cross‑buy, and purchase frequency.
- **Source:** <a href="https://cran.r-project.org/web/packages/SMCRM/SMCRM.pdf">CRAN: SMCRM package</a> (see page 3 “customerAcquisition”)
- **File:** ![R_customerAcquisition.csv](.datasets/customer-lifetime-management/less-than-50K/classification/R_customerAcquisition.csv)
- **#Rows:** 500
- **#Features:** 17
- **Target:** `acquisition`
- **#Views:** Not applicable
- **Additional Description:** Duration is right‑censored at 730 days; squared spend/frequency terms enable nonlinear response modeling; variables align with the SMCRM textbook datasets for reproducible CRM analytics.
- **Features:** <br>
`customer`: customer number (from 1 to 500).<br>
`acquisition`: 1 if the prospect was acquired, 0 otherwise.<br>
`first_purchase`: dollar value of the first purchase (0 if the customer was not acquired).<br>
`clv`: the predicted customer lifetime value score; it is 0 if the prospect was not acquired or has already churned from the firm.<br>
`duration`: time in days that the acquired prospect has been or was a customer, right‑censored at 730 days.<br>
`censor`: 1 if the customer was still a customer at the end of the observation window, 0 otherwise.<br>
`acq_expense`: dollars spent on marketing efforts to try and acquire that prospect.<br>
`acq_expense_sq`: square of dollars spent on marketing efforts to try and acquire that prospect.<br>
`industry`: 1 if the customer is in the B2B industry, 0 otherwise.<br>
`revenue`: annual sales revenue of the prospect’s firm (in millions of dollar).<br>
`employees`: number of employees in the prospect’s firm.<br>
`ret_expense`: dollars spent on marketing efforts to try and retain that customer.<br>
`ret_expense_sq`: square of dollars spent on marketing efforts to try and retain that customer.<br>
`crossbuy`: the number of categories the customer has purchased.<br>
`frequency`: the number of times the customer purchased during the observation window.<br>
`frequency_sq`: the square of the number of times the customer purchased during the observation window.<br>


## 16. `R_customerChurn`
- **Description:** Customer Churn data from Chapter 6 designed to model time‑to‑churn with right‑censoring, incorporating average monthly retention spend, lifetime purchase breadth and frequency, and firmographics.
- **Source:** <a href="https://cran.r-project.org/web/packages/SMCRM/SMCRM.pdf">CRAN: SMCRM package</a> (see page 4 “customerChurn”)
- **File:** ![R_customerChurn.csv](.datasets/customer-lifetime-management/less-than-50K/classification/R_customerChurn.csv)
- **#Rows:** 500
- **#Features:** 11
- **Target:** `censor`
- **#Views:** Not applicable
- **Additional Description:** Variables align with the SMCRM textbook; `duration` is right‑censored at 730 days, and squared terms enable nonlinear effects of spend and frequency.
- **Features:** <br>
`customer`: customer number (from 1 to 500).<br>
`duration`: time in days that the acquired prospect has been or was a customer, right‑censored at 730 days.<br>
`censor`: 1 if the customer was still a customer at the end of the observation window, 0 otherwise.<br>
`avg_ret_exp`: average number of dollars spent on marketing efforts to try and retain that customer per month.<br>
`avg_ret_exp_sq`: square of the average number of dollars spent on marketing efforts to try and retain that customer per month.<br>
`total_crossbuy`: total number of categories the customer has purchased during the customer’s lifetime.<br>
`total_freq`: total number of purchase occasions the customer had with the firm in the customer’s lifetime.<br>
`total_freq_sq`: square of the total number of purchase occasions the customer had with the firm in the customer’s lifetime.<br>
`industry`: 1 if the customer is in the B2B industry, 0 otherwise.<br>
`revenue`: annual sales revenue of the prospect’s firm (in millions of dollar).<br>
`employees`: number of employees in the prospect’s firm.<br>


## 17. `R_customerRetentionDemographics`
- **Description:** Demographics data for customer retention from Chapter 4, capturing customer gender, marital status, income band, first purchase value, loyalty membership, share-of-wallet, and discounted CLV for segmentation and retention modeling.
- **Source:** <a href="https://cran.r-project.org/web/packages/SMCRM/SMCRM.pdf">CRAN: SMCRM package</a> (see page 5 “customerRetentionDemographics”)
- **File:** ![R_customerRetentionDemographics.csv](.datasets/customer-lifetime-management/less-than-50K/classification/R_customerRetentionDemographics.csv)
- **#Rows:** 500
- **#Features:** 8
- **Target:** `loyalty`
- **#Views:** Not applicable
- **Additional Description:** Income is a ranked band; loyalty is a binary program flag; sow measures the firm’s purchase share across all‑category spend, enabling uplift and retention segmentation with basic demographics.
- **Features:** <br>
`customer`: customer number (from 1 to 500).<br>
`gender`: 1 if the customer is male, 0 if the customer is female.<br>
`married`: 1 if the customer is married, 0 if the customer is not married.<br>
`income`: 1 if income < 30,000; 2 if 30,001 < income < 45,000; 3 if 45,001 < income < 60,000; 4 if 60,001 < income < 75,000; 5 if 75,001 < income < 90,000; 6 if income > 90,001.<br>
`first_purchase`: value of the first purchase made by the customer in quarter 1.<br>
`loyalty`: 1 if the customer is a member of the loyalty program, 0 if not.<br>
`sow`: share‑of‑wallet; the percentage of purchases the customer makes from the given firm given the total amount of purchases across all firms in that category.<br>
`clv`: discounted value of all expected future profits, or customer lifetime value.<br>


## 18. `R_customerRetentionTransactions`
- **Description:** Transactions data for customer retention from Chapter 4, providing a quarterly panel with purchases, order values, cross‑category breadth, and retention marketing spend to analyze purchase dynamics and retention effects over time.
- **Source:** <a href="https://cran.r-project.org/web/packages/SMCRM/SMCRM.pdf">CRAN: SMCRM package</a> (see pages 5–6 "customerRetentionTransactions")
- **File:** ![R_customerRetentionTransactions.csv](.datasets/customer-lifetime-management/less-than-50K/classification/R_customerRetentionTransactions.csv)
- **#Rows:** 500 customers × up to 12 quarters (panel)
- **#Features:** 7
- **Target:** `purchase`
- **#Views:** Not applicable
- **Additional Description:** Each row is a customer–quarter; order values and cross‑category counts support RFM‑style features, while retention spend and its square allow modeling diminishing returns of marketing.
- **Features:** <br>
`customer`: customer number (from 1 to 500).<br>
`quarter`: quarter (from 1 to 12) where the transactions occurred.<br>
`purchase`: 1 when the customer purchased in the given quarter and 0 if no purchase occurred in that quarter.<br>
`order_quantity`: dollar value of the purchases in the given quarter.<br>
`crossby`: number of different categories purchased in a given quarter.<br>
`ret_expense`: dollars spent on marketing efforts to try and retain that customer in the given quarter.<br>
`ret_expense_sq`: square of dollars spent on marketing efforts to try and retain that customer in the given quarter.<br>


## 19. `R_customerWinBack`
- **Description:** Customer win‑back data from Chapter 7 capturing reacquisition outcomes, first and second lifecycle durations and value, offer magnitude, lapse since loss, price change between lifecycles, and basic demographics to model win‑back propensity and post‑return value.
- **Source:** <a href="https://cran.r-project.org/web/packages/SMCRM/SMCRM.pdf">CRAN: SMCRM package</a> (see page 7 "customerWinBack")
- **File:** ![R_customerWinBack.csv](.datasets/customer-lifetime-management/less-than-50K/classification/R_customerWinBack.csv)
- **#Rows:** 500
- **#Features:** 10
- **Target:** `reacquire`
- **#Views:** Not applicable
- **Additional Description:** Enables modeling how offer size, elapsed time since churn, and price changes affect the probability of win‑back and the second‑lifecycle CLV; suitable for treatment optimization and uplift analysis.
- **Features:** <br>
`customer`: customer number (from 1 to 500).<br>
`reacquire`: 1 if the customer is reacquired, 0 if not.<br>
`duration_2`: time in days of the customer's second lifecycle with the company, 0 if not reacquired.<br>
`slcv`: CLV of the customer in the second lifecycle.<br>
`duration_1`: time in days of the customer's first lifecycle with the company.<br>
`offer`: value of the offer provided to the customer for reacquisition.<br>
`duration_lapse`: time in days since the customer was lost to when the offer to reacquire was given.<br>
`price_change`: increase or decrease in subscription price between the first and second lifecycle, 0 if not reacquired.<br>
`gender`: 1 if male, 0 if female.<br>
`age`: age in years of the customer at the time of the attempt to reacquire.<br>

## 20. `BankChurners`
- **Description:** Credit card customers with demographics, product and account tenure, spend/transaction behavior, utilization, and attrition outcome for churn prediction.
- **Source:** <a href="https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers">Kaggle</a>
- **File:** ![BankChurners.csv](.datasets/customer-lifetime-management/less-than-50K/classification/BankChurners.csv)
- **#Rows:** ~10,000
- **#Features:** 21 (plus target)
- **Target:** `Attrition_Flag`
- **#Views:** Not specified
- **Additional Description:** Common benchmark for financial churn; includes change features (Q4/Q1 deltas), relationship breadth, and utilization for feature importance and score calibration.
- **Features:** <br>
`CLIENTNUM`: Unique identifier for the cardholder.<br>
`Attrition_Flag`: Target indicating attrition status.<br>
`Customer_Age`: Customer age in years.<br>
`Gender`: Gender of the customer.<br>
`Dependent_count`: Number of dependents.<br>
`Education_Level`: Highest education attained.<br>
`Marital_Status`: Marital status of the customer.<br>
`Income_Category`: Household income bracket.<br>
`Card_Category`: Credit card tier/category.<br>
`Months_on_book`: Tenure in months with the bank.<br>
`Total_Relationship_Count`: Products held with the bank.<br>
`Months_Inactive_12_mon`: Inactive months in last 12 months.<br>
`Contacts_Count_12_mon`: Contacts in last 12 months.<br>
`Credit_Limit`: Credit limit on the card.<br>
`Total_Revolving_Bal`: Revolving balance amount.<br>
`Avg_Open_To_Buy`: Average available credit.<br>
`Total_Amt_Chng_Q4_Q1`: Spend amount change Q4 to Q1 ratio.<br>
`Total_Trans_Amt`: Total transaction amount (12M).<br>
`Total_Trans_Ct`: Total transaction count (12M).<br>
`Total_Ct_Chng_Q4_Q1`: Transaction count change Q4 to Q1 ratio.<br>
`Avg_Utilization_Ratio`: Average utilization ratio.<br>


## 21. `Churn Modelling`
- **Description:** Retail bank customer dataset with demographics, geography, account metrics, and activity indicators to predict whether a customer exits the bank.
- **Source:** <a href="https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling">Kaggle</a>
- **File:** ![Churn Modelling.csv](.datasets/customer-lifetime-management/less-than-50K/classification/Churn Modelling.csv)
- **#Rows:** 10,000
- **#Features:** 14 (including target)
- **Target:** `Exited`
- **#Views:** Not specified
- **Additional Description:** Popular supervised learning dataset enabling feature engineering around credit score, product holdings, and engagement for churn risk scoring.
- **Features:** <br>
`RowNumber`: Row index/order of records.<br>
`CustomerId`: Unique bank customer identifier.<br>
`Surname`: Customer surname for reference.<br>
`CreditScore`: Creditworthiness score.<br>
`Geography`: Country/region of the customer.<br>
`Gender`: Gender of the customer.<br>
`Age`: Age in years.<br>
`Tenure`: Years with the bank.<br>
`Balance`: Current account balance.<br>
`NumOfProducts`: Number of bank products held.<br>
`HasCrCard`: Indicator if customer holds a credit card.<br>
`IsActiveMember`: Active membership flag.<br>
`EstimatedSalary`: Estimated annual salary.<br>
`Exited`: Target exit flag.<br>


## 22. `Customer Acquisition data`
- **Description:** Takes into account both the revenue generated by each customer and the costs associated with acquiring and serving that customer to analyze acquisition efficiency.
- **Source:** <a href="https://www.kaggle.com/datasets/amirmotefaker/customer-acquisition-data">Kaggle</a>
- **File:** ![customer_acquisition_data.csv](.datasets/customer-lifetime-management/less-than-50K/regression/customer_acquisition_data.csv)
- **#Rows:** ~800 (reference spec); actual file shows hundreds of entries with consistent schema.
- **#Features:** 5
- **Target:** Task‑dependent (e.g., classify high‑ROI customers or predict revenue from channel/cost).
- **#Views:** Not specified
- **Additional Description:** Useful for computing CAC, conversion lift by channel, and revenue‑to‑cost ratios for acquisition strategy optimization.
- **Features:** <br>
`customerid`: Unique identifier for each acquired customer used to join or aggregate performance metrics.<br>
`channel`: Acquisition source such as referral, paid advertising, social media, or email marketing to compare ROI across channels.<br>
`cost`: Spend attributed to acquiring the specific customer, enabling CAC and payback calculations.<br>
`conversionrate`: Observed conversion probability or rate associated with the customer’s acquisition path for uplift analyses.<br>
`revenue`: Revenue realized from the customer, used to compute ROI, LTV proxies, and profitability signals.<br>


## 23. `analyzing customer spending habits`
- **Description:** This Sales Data dataset offers a unique insight into the spending habits of customers from various countries across the globe. With detailed information on customer age, gender, product category, quantity, unit cost and price, as well as revenue generated through sales of products listed in this dataset, you can explore and discover patterns in consumer behavior.
- **Source:** <a href="https://www.kaggle.com/datasets/thedevastator/analyzing-customer-spending-habits-to-improve-sa">Kaggle</a>
- **File:** ![analyzing customer spending habits.csv](.datasets/customer-lifetime-management/less-than-50K/regression/analyzing customer spending habits.csv)
- **#Rows:** ~17400
- **#Features:** 12 (excluding index)
- **Target:** Revenue
- **#Views:** Not specified
- **Additional Description:** Also with this dataset you can gain valuable insights about the changes in consumer demand for specific products over time.
- **Features:** <br>
`index`: Numbering for each row<br>
`Date`: Date of transaction<br>
`Year`: Year of transaction<br>
`Month`: Month of transaction<br>
`Customer Age`: Age of customer<br>
`Customer Gender`: Gender of customer<br>
`Country`: Country of origin of the customer<br>
`State`: Particular state from the country<br>
`Product Category`: Category of the product<br>
`Sub Category`: Sub category of the product under the main category<br>
`Quantity`: Quantity of product purchased<br>
`Unit Cost`: Unit cost of that product<br>
`Unit Price`: Unit price of that product<br>
`Cost`: Actual cost of the product<br>
`Column1`: No specific description<br>
`Revenue`: Revenue realised from the customer on the purchase of the product<br>