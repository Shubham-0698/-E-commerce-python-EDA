# E-commerce-python-EDA
E-commerce Marketing and Shopping EDA &amp; Hypothesis testing with Python
**Problem statement:**
To conduct a thorough exploratory data analysis (EDA) and hypothesis testing on two comprehensive datasets one containing information on customers visiting the shopping site for purchase and another that has demographic, purchase, and marketing information about the group of people

**Dataset:**
https://drive.google.com/drive/folders/11o4VGwvJKFOElwikEDiLCViWhy2E404R

**Data Dictionary:**

The data dictionary is available here: https://docs.google.com/document/d/1UX0GipJik6ubEv1GxCYtTdfs5L6z4sZxDpSSosK8JZM/edit?usp=sharing

**Expectations:**
The project expects you to Analyze user behavior across different page categories, engagement time, and other features. Gain insights into factors influencing purchase decisions and identify areas for optimization. Formulate some hypotheses on the dataset and check if they are correct.

**Shopping dataset**
Column Descriptions:
Administrative: This is the number of pages of this type (administrative) that the user visited. Eg: account, addresses, cart, orders etc
Administrative_Duration: This is the amount of time spent in this category of pages.
Informational: This is the number of pages of this type (informational) that the user visited.
Informational_Duration: This is the amount of time spent in this category of pages.
ProductRelated: This is the number of pages of this type (product related) that the user visited.
ProductRelated_Duration: This is the amount of time spent in this category of pages.
BounceRates: The percentage of visitors who enter the website through that page and exit without triggering any additional tasks.
ExitRates: The percentage of pageviews on the website that end at that specific page.
PageValues: The average value of the page averaged over the value of the target page and/or the completion of an eCommerce transaction.
More information about how this is calculated
SpecialDay: This value represents the closeness of the browsing date to special days or holidays (eg Mother's Day or Valentine's day) in which the transaction is more likely to be finalized. More information about how this value is calculated below.
Month: Contains the month the pageview occurred, in string form.
OperatingSystems: An integer value representing the operating system that the user was on when viewing the page.
Browser: An integer value representing the browser that the user was using to view the page.
Region: An integer value representing which region the user is located in.
TrafficType: An integer value representing what type of traffic the user is categorized into.
VisitorType: A string representing whether a visitor is New Visitor, Returning Visitor, or Other.
Weekend: A boolean representing whether the session is on a weekend.
Revenue: A boolean representing whether or not the user completed the purchase.
Campaign dataset

**Column Details:**
ID: Customer's Unique Identifier
Year_Birth: Customer's Birth Year
Education: Customer's education level (Graduation, Master, PhD, 2n Cycle(Diploma), Basic)
Marital_Status: Customer's marital status
Income: Customer's yearly household income
Kidhome: Number of children in customer's household
Teenhome: Number of teenagers in customer's household
Dt_Customer: Date of customer's enrollment with the company
Recency: Number of days since customer's last purchase
MntWines: Amount spent on wine in the last 2 years
MntFruits: Amount spent on fruits in the last 2 years
MntMeatProducts: Amount spent on meat in the last 2 years
MntFishProducts: Amount spent on fish in the last 2 years
MntSweetProducts: Amount spent on sweets in the last 2 years
MntGoldProds: Amount spent on gold in the last 2 years
NumDealsPurchases: Number of purchases made with a discount
NumWebPurchases: Number of purchases made through the company's web site
NumCatalogPurchases: Number of purchases made using a catalogue
NumStorePurchases: Number of purchases made directly in stores
NumWebVisitsMonth: Number of visits to company's web site in the last month
AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise (Target variable)
AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise (Target variable)
AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise (Target variable)
AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise (Target variable)
AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise (Target variable)
Complain: 1 if customer complained in the last 2 years, 0 otherwise
Country: Customer's location
