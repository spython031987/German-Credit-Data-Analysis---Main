# German-Credit-Data-Analysis - Main
## German Credit Data Dashboard Link:  https://app.powerbi.com/reportEmbed?reportId=23b733e5-31bc-41e8-a46a-01e08c040e37&autoAuth=true&ctid=bdb74b30-9568-4856-bdbf-06759778fcbc

## Overview
The German Credit Data Dashboard is a comprehensive visualization tool designed in **Power BI** to analyze credit data and loan distributions across different customer segments. This interactive dashboard provides insights into customer demographics, loan durations, and credit history patterns with two distinct views: **Multidimensional Risk View** and **Key Influencer View.**

### Mutlidimensional Risk View

* Displays important portfolio statistics.
* Shows loan purpose analysis for key drivers of credit ratings
* Provides snapshot of distribution of loans among different customer age groups and corresponding average loan duration.

![German_Credit_Data_Analysis_1](https://github.com/user-attachments/assets/e07d7e12-b3bb-48a3-850d-ad6ebaa0231c)


### Features of Multidimensional Risk View

**1. Portfolio Statistics Panel**

Displays key metrics including total customer count, average credit duration and average credit amount.
Shows aggregated statistics for the entire portfolio.
Current statistics show 1000 customers with an average credit duration of 20.90 months.

**2. Age Group Analysis**

Bar chart visualization showing customer distribution across age groups.
Dual-axis representation displaying:

* Number of customers (bars)
* Average loan duration in months (line)


Age groups range from 10-19 to 70-79 years.
Peak customer concentration in 20-29 age group with approximately 400 customers.

**3. Loan Purpose Analysis**

Horizontal bar chart showing average loan amounts by purpose
segmented by Key Influencers of Customer Ratings.

Categories of Purpose of Loans include:

* Others (up to 18K average loan amount)
* Business
* Car
* Education
* Domestic Purpose

**4. Average Loan Amount Distribution by Key Influencers of Credit Ratings**

Doughnut chart representing the distribution of Average amount of loans across Key Influencers of Credit Ratings: 

* Credit History
* Checking Account
* Savings Account
* Property
* Debtors / Gurantors
* Housing


Percentages and amounts clearly displayed for each segment


**5. Interactive Features**

* Multidimensional Risk View toggle
* Customer Rating filters
* Left sidebar navigation for Key Influencers of Customer Ratings :

  
### Key Influencer View

* Focuses on factors affecting customer credit ratings
* Visualizes relationships between Number of Loans and Customer Age & Duration bifurcating into good/bad customer outcomes
* The visualizations also gives information on the relative size of the loans for customers through bubble sizes. 

![German_Credit_Data_Analysis_2](https://github.com/user-attachments/assets/f8f96817-a713-422d-8801-36c261f4eb94)

### Features of Key Influencer View

**1. Key Influencer Visualization**

* Displays relative importance of factors affecting customer credit ratings
* Shows likelihood multipliers for good/bad customer outcomes
* Key influencers of credit ratings ranked by impact

**2. Scatter Plot Visualizations**

**A) Duration & No. of Loans Analysis**

* X-axis: Loan Duration (0-60 months)
* Y-axis: Number of Loans
* Color-coded for Good/Bad Customers
* Bubble size indicates credit amount


**B) Age & No. of Loans Analysis**

* X-axis: Customer Age (20-80 years)
* Y-axis: Number of Loans
* Color-coded for Good/Bad Customers
* Bubble size indicates credit amount
* Shows age-based risk distribution




### Technical Notes

* Dashboard updates in real-time based on filter selections
* All monetary values are displayed in thousands (K)
* Duration metrics are shown in months
* Color coding used consistently across visualizations for credit history categories

### Usage Guidelines

* Use the top-right toggle for switching between risk view modes
* Apply filters through the Customer Rating dropdown
* Navigate different aspects of credit analysis through the left sidebar
* Hover over charts for detailed tooltips and specific values

For technical support or data-related queries, please contact the dashboard administrator.
