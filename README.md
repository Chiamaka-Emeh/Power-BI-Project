# Digital Marketing Campaign Analysis

## Table of Content

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Key Business Questions](#key-business-questions)
- [Tools and Methodologies](#tools-and-methodologies)
- [Key Insights](#key-insights)
- [Summary & Recommendations](#summary-&-recommendations)
- [References](#references)

 ## Project Overview
  This project evaluates the performance of a digital marketing campaign in India using Microsoft Power BI. With 242M impressions,the campaign achieved exceptionally wide visibility.However, a deep dive into the data revealed a critical data integrity issue: the raw dataset incorrectly summed up individual row-level ROIs, leading to an inflated total that misrepresented actual performance. To establish a reliable source of truth, I created a custom DAX measure to calculate the true weighted ROI. The corrected analysis confirms that the campaign was incredibly profitable and cost-effective, driven by high revenue generation. The key recommendations are to Increase ad spend on top-performing product categories that yield both high ROI and substantial revenue, Introduce targeted incentives, such as limited-time discounts, to convert high-intent users who clicked the ads but did not complete a purchase—effectively narrowing the gap between total clicks and total conversions.
   
![Digital Marketing Campaign Dashboard](DIGITAL_MARKETING_CAMPAIGN_DASHBOARD.png)

## Objectives
The main objectives for this campaign is to:
- Drive Brand Visibility
- Maximize Sales & Revenue 
- Optimize Conversion Efficiency 
- Achieve High Profitability (ROI )

## Key Business Questions
1. How effectively are we turning displays into clicks and clicks into sales?
2. Which categories are delivering the highest ROI?
3. Is the campaign profitable?

## Tools and Methodologies
*Tool Used:* *Microsoft Power BI* [Website](https://www.microsoft.com/en-us/power-platform/products/power-bi)

### Techniques
1. DAX Implementation for advanced calculations and metrics
2. Data Visualization for interactive and insightful dashboards
3. Comprehensive Project Documentation for clear reporting of insights

## Key Insights
1. *How effectively are we turning displays into clicks and clicks into sales?*
- An exceptional 5.09% CTR proves the ads caught the right eyes, and a strong 9.81% Conversion Rate proves the landing pages successfully closed the deal.

![CTR and Conversion Rate](CTR%20&%20CONVERSION%20RATE.png)

2. *Which categories  are delivering the highest ROI?*
- The categories Household, Groceries, and Beverages are the top three performers for both Conversion Rate and ROI.

3. *Is the campaign profitable?*
 - The campaign is massively profitable, with an Overall ROI of 14.15k%. This was driven by a Total Revenue of ₹344.33M against a relatively small Ad Spend of ₹2.42M.

## Summary & Recommendations 
### Summary of Key Findings: 
1. With 242M impressions the campaign had wide visibility.
2. The raw dataset showed an ROI of 359.92k, but your DAX measure (ROI_Double_Checked %) corrected this to 14.15k%. The automated DAX calculation is the correct one to use for business decisions. The higher figure was a result of incorrectly summing non-additive ratios. By using the weighted ROI, the business is getting a realistic and accurate view of performance rather than the inflated one.
3. The campaign is massively profitable, with an Overall ROI of 14.15k%.
4. Household, Groceries, and Beverages are the top three categories that generated high ROI.
5. Cold drinks, Biscuits, and Dishwasher liquid are the top three revenue generators.
### Strategic Recommendations: 
1. To minimize the gap between the 12M Clicks and 1M Conversions, offer incentives like limited-time discounts to convert high-intent users who clicked the ads but did not complete a purchase because of the price.
2. Increase ad spend on top-performing product categories that yield both high ROI and substantial revenue.

### References
[power bi](https://www.google.com/search?q=power+bi&oq=power+bi&gs_lcrp=EgZjaHJvbWUqDQgAEAAYgwEYsQMYgAQyDQgAEAAYgwEYsQMYgAQyDQgBEAAYgwEYsQMYgAQyBggCEEUYPDIGCAMQRRg8MgYIBBBFGDwyBggFEEUYQTIGCAYQRRhBMgYIBxBFGEHSAQgyOTk2ajBqN6gCALACAA&sourceid=chrome&ie=UTF-8)
