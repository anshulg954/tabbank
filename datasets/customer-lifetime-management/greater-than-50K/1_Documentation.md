This file contains detailed description about each of the datasets to be considered for checking TabPFN performance.​

The datasets have entries greater than 50K.

DISCLAIMER!!! --> The content is generated with the assistance of LLM.

---

# Customer Lifetime Management Domain​
## 1. `customer_churn_dataset`
- **Description:** LCustomer churn refers to the phenomenon where customers discontinue their relationship or subscription with a company or service provider. In the context of the Churn dataset, the churn label indicates whether a customer has churned or not.
- **Source:** <a href="https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset?select=customer_churn_dataset-training-master.csv">Kaggle</a>
- **File:** ![customer_churn_dataset.csv](.datasets/customer-lifetime-management/greater-than-50K/classification/customer_churn_dataset.csv)
- **#Rows:** ~505,000
- **#Features:** ~11 (including target)
- **Target:** `Churn`
- **#Views:** Not specified
- **Additional Description:** Ideal for stress‑testing algorithms at volume and for probability calibration.
- **Features:** <br>
`CustomerID`: Unique customer key.<br>
`Gender`: Gender of the customer.<br>
`Age`: Age of the Customer.<br>
`Payment Delay`: Delays in Payment.<br>
`Usage Frequency`: Frequency of usage.<br>
`Support Calls`: Number of Support calls made.<br>
`Tenure`: Duration with the company.<br>
`Contract Length`: Contract type.<br>
`Subscription Type`: Type of Subscription.<br>
`Last Interaction`: NUmber of Last interactions with the customer.<br>
`Total Spend`: Total amount spent.<br>
`Churn`: Target churn status.<br>


## 2. `Lead Conversion Data`
- **Description:** Loan application records with demographics, employment, income, loan specifics, and approval status to model conversion.
- **Source:** <a href="https://www.kaggle.com/datasets/arashnic/banking-loan-prediction">Kaggle</a>
- **File:** ![Lead Conversion Data.csv](.datasets/customer-lifetime-management/greater-than-50K/classification/Lead Conversion Data.csv)
- **#Rows:** ~69,000
- **#Features:** 23 (including target)
- **Target:** `Approved`
- **#Views:** Not specified
- **Additional Description:** Requires date parsing, income sanitization, and handling of categorical bank/source codes.
- **Features:** <br>
`ID`: Application identifier.<br>
`Gender`: Applicant gender.<br>
`DOB`: Date of birth.<br>
`Lead_Creation_Date`: Date the lead was created.<br>
`City_Code`: Applicant city code.<br>
`City_Category`: City segmentation category.<br>
`Employer_Code`: Employer identifier.<br>
`Employer_Category1`: Employer category group 1.<br>
`Employer_Category2`: Employer category group 2.<br>
`Monthly_Income`: Monthly income reported.<br>
`Customer_Existing_Primary_Bank_Code`: Existing customer Primary bank code.<br>
`Primary_Bank_Type`: Type/category of primary bank.<br>
`Contacted`: Whether the lead was contacted.<br>
`Source`: Acquisition source channel.<br>
`Source_Category`: Category of source.<br>
`Existing_EMI`: Existing EMI indicator/amount.<br>
`Loan_Amount`: Requested loan amount.<br>
`LoanP_eriod`: Requested tenure.<br>
`Interest_Rate`: Interest rate quoted.<br>
`EMI`: Calculated monthly installment.<br>
`Var1`: Auxiliary risk/segment variable.<br>
`Approved`: Target approval outcome.<br>


## 3. `Airlines customer satisfaction`
- **Description:** Airline passenger survey capturing demographics, trip context, service touchpoints, onboard experience, ground services, delays, and an overall satisfaction label for modeling drivers of satisfaction and NPS‑style outcomes.
- **Source:** <a href="https://www.kaggle.com/datasets/sjleshrac/airlines-customer-satisfaction">Kaggle</a>
- **File:** ![Airlines customer satisfaction.csv](.datasets/customer-lifetime-management/greater-than-50K/classification/Airlines customer satisfaction.csv)
- **#Rows:** See "details of datasets.csv" for the standardized count used in your environment.
- **#Features:** See "details of datasets.csv" for the standardized schema summary.
- **Target:** `satisfaction`
- **#Views:** Not specified
- **Additional Description:** Suitable for feature importance and SHAP analysis across flight distance, delays, and service ratings; supports segmentation by class and customer type for retention and upsell strategies.
- **Features:** <br>
`Gender`: Passenger gender.<br>
`Customer Type`: Customer category.<br>
`Age`: Passenger age.<br>
`Type of Travel`: Travel purpose.<br>
`Class`: Cabin class.<br>
`Flight Distance`: Distance flown.<br>
`Inflight wifi service`: WiFi rating.<br>
`Departure/Arrival time convenient`: Schedule convenience rating.<br>
`Ease of Online booking`: Booking experience rating.<br>
`Gate location`: Gate accessibility rating.<br>
`Food and drink`: Catering quality rating.<br>
`Online boarding`: Online boarding rating.<br>
`Seat comfort`: Seat comfort rating.<br>
`Inflight entertainment`: Entertainment rating.<br>
`On-board service`: Onboard staff rating.<br>
`Leg room service`: Legroom comfort rating.<br>
`Baggage handling`: Baggage experience rating.<br>
`Checkin service`: Check‑in rating.<br>
`Inflight service`: Overall inflight service rating.<br>
`Cleanliness`: Cabin cleanliness rating.<br>
`Departure Delay in Minutes`: Departure delay duration.<br>
`Arrival Delay in Minutes`: Arrival delay duration.<br>
`satisfaction`: Target satisfaction indicator.<br>


