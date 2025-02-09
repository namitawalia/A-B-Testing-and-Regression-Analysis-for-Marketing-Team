# A/B Testing and Regression Analysis for Facebook and AdWords Ads

## Business Problem
As a marketing agency, our primary objective is to maximize the return on investment (ROI) for our clients' advertising campaigns. We have conducted two ad campaigns, one on Facebook and the other on AdWords, and we need to determine which platform yields better results in terms of clicks, conversions, and overall cost-effectiveness. By identifying the most effective platform, we can allocate our resources more efficiently and optimize our advertising strategies to deliver better outcomes for our clients.

The dataset comprises a collection of data comparing the performance of two separate ad campaigns conducted throughout the year 2019. Specifically, the data covers a Facebook Ad campaign and an AdWords Ad campaign. The dataset includes various performance metrics for each ad campaign, providing insights into their effectiveness and efficiency over time.

## Findings

### Data Distribution
All the histograms show a somewhat symmetrical shape. This suggests that the number of clicks and conversions is relatively evenly distributed, with few extreme outliers on either the high or low end.

- Facebook had more frequent higher conversion days than AdWords, which had very low conversion rates (less than 6 and 6-10).
- There is a significant variance in the number of high conversion days between the two campaigns.
- The absence of any days with conversions between 10-15 and more than 15 in AdWords indicates a need to review what strategies were changed or what external factors could have influenced these numbers.

### Correlation Analysis
- A correlation coefficient of **0.87** indicates a strong positive linear relationship between clicks on Facebook ads and sales, suggesting that as the number of clicks increases, sales tend to increase as well.
- This strong correlation suggests that **Facebook ads are highly effective in driving sales**.
- A correlation coefficient of **0.45** for AdWords ads and sales indicates a **moderate** positive relationship. While AdWords contributes to sales, other factors may influence its effectiveness.

### Statistical Testing
- The **mean number of conversions** from Facebook ads (**11.74**) is substantially higher than AdWords ads (**5.98**).
- The **T statistic (32.88)** and **extremely small p-value (9.35e-134)** provide strong evidence against the null hypothesis, indicating that Facebook ads generate more conversions.
- The results suggest **reallocating resources toward Facebook advertising**.

### Regression Analysis
- The **Linear Regression model achieved an R² score of 76.35%**, indicating strong predictive power for Facebook ad conversions.
- The model can help businesses make informed decisions about **resource allocation, budget planning, and campaign optimization**.

### Time-Based Trends
- **Conversion rates remain consistent** across weekdays, with **Monday and Tuesday** showing the highest rates.
- Conversion rates fluctuate across months, with dips in **February, April, May, June, August, and November**.
- **CPC values** are lowest in **May and November**, indicating periods of cost-effective advertising.

## Recommendations
- **Increase investment in Facebook ads**, as they have shown a higher conversion rate.
- **Optimize AdWords campaigns** by identifying factors affecting lower conversion rates.
- **Allocate more budget during May and November**, when CPC is lower, to maximize cost-efficiency.
- **Leverage Monday and Tuesday** for ad campaigns, as these days show the highest conversion rates.
- **Conduct further analysis** on factors influencing conversion rate dips in specific months.
- **Use regression insights** to set realistic campaign goals and optimize budget allocation.

## Methodologies Used
- **A/B Testing**
- **Regression Analysis**
- **Hypothesis Testing**

```

