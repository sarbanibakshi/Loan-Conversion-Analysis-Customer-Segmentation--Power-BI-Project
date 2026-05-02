# Loan Conversion Analysis & Customer Segmentation--Power BI Project

This project analyzes customer data to understand loan conversion behavior and identify key segments that are more likely to accept personal loan offers. 
Using data sourced from Kaggle, the analysis combines exploratory data analysis (EDA) and customer segmentation techniques to generate actionable business insights.

## Dataset:

The dataset used in this project was obtained from Kaggle and contains customer-level banking information such as:

* Demographics (Age, Education)
* Financial attributes (Income, Credit Card Average spending - CCAvg)
* Account information (CD Account, Personal Loan, Securities Acoount, Mortgage)
* Loan acceptance status (Target variable)

## Objective:

The primary goals of this project are:

* Analyze patterns in loan acceptance
* Identify high-conversion customer segments
* Understand how financial and demographic factors influence decisions
* Provide data-driven recommendations for targeted marketing

## Key Metrics:

* Total Customers: 5000
* Loan Customers: 480
* Loan Conversion Rate: 9.6%
* Average Credit Card Spending (CCAvg): 1.94

![Loan Conversion](https://i.postimg.cc/1Rg6pPD7/Screenshot-2026-05-02-234416.png)

# Dashboard Overview:

The dashboard provides a clear, visual breakdown of customer behavior and loan conversion patterns, enabling quick identification of high-value segments and key drivers of conversion.

## Loan Conversion by Age Group:

* Conversion rates are relatively stable across age groups, ranging from ~8.8% to ~10.2%.
* Highest conversion observed in: 60+ (10.24%), 30–39 (10.18%), and Under 30 (10.04%).
* Lowest conversion in: 50–59 (8.85%).

Insight: Age alone is not a strong differentiator, though slightly higher conversions appear at younger and older extremes.

## Loan Conversion by Education:

* Advanced degree holders: 13.66% (highest)
* Graduates: 12.97%
* Undergraduates: 4.44% (significantly lower)

Insight: Education level has a strong impact on loan acceptance, with highly educated customers being much more likely to convert.

## Income vs Credit Card Spending (CCAvg):

* Strong positive correlation between income and credit card spending.
* As income increases:Spending increases and Loan size and likelihood of conversion also increase.

Insight: High-income, high-spending customers represent a premium target segment.

## Loan Acceptance by Income Category:

Customer distribution is highest in:
* Middle income (1909 customers)
* Low income (1869 customers)

However, acceptance is more prominent in: High and Very High income segments.

Insight: Larger segments don’t necessarily drive conversions—higher-income groups yield better results despite smaller sizes.

## Loan Conversion by CCAvg:

* Very High (5+): 28.51% conversion
* High (3–5): 25.81% conversion
* Medium (1–3): Very low conversion (~5%)
* Low (0–1): Minimal conversion (~2.5%)

Insight: Credit card usage is one of the strongest behavioral indicators of loan acceptance.

## Loan Conversion by CD Account Usage:

* Customers with CD accounts: 86.5% of total conversions
* Customers without CD accounts: 13.5%

Insight: Existing relationship with the bank (via CD accounts) significantly increases trust and likelihood of conversion.

# Key Insights:

* High-income and high-spending customers are the most valuable targets.

* Education level plays a critical role in financial decision-making.

* Credit card usage strongly correlates with loan acceptance.

* Customers with existing financial products are far more likely to convert.

* Age has minimal impact compared to financial and behavioral factors.


# Business Recommendations:

* Focus marketing campaigns on: High-income customers, High CCAvg segments, Customers with CD accounts.

* Design tailored offerings for: Advanced and graduate-level customers.

* Use behavioral signals (spending patterns) for predictive targeting.

* Reduce spend on low-conversion segments (low income, low CCAvg).



