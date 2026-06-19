# SCT_DA_4

Business Insights Report using Exploratory Data Analysis (EDA)

Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a Marketing Campaign Dataset. The objective is to analyze campaign performance, understand customer engagement, and derive business insights that can help optimize marketing strategies and improve Return on Investment (ROI).

---

Dataset Information

The dataset contains information about various marketing campaigns and includes features such as:

- Campaign ID
- Company
- Campaign Type
- Target Audience
- Channel Used
- Conversion Rate
- Acquisition Cost
- ROI
- Clicks
- Impressions
- Engagement Score
- Customer Segment
- Date

---

Libraries Used

The following Python libraries were used:

- Pandas
- Matplotlib
- Seaborn

---

Data Cleaning and Preprocessing

The following preprocessing steps were performed:

- Loaded the marketing campaign dataset.
- Examined the first few records.
- Checked column names and data types.
- Converted the Date column into datetime format.
- Identified missing values.
- Checked for duplicate rows and removed them.
- Generated statistical summaries using describe().
- Exported the cleaned dataset into a CSV file.

---

Exploratory Data Analysis

Several visualizations and analyses were performed to understand campaign performance.

Campaign Count by Channel

Analyzed the distribution of campaigns across different marketing channels.

"Campaign Count by Channel" (images/campaign_count_by_channel.png)

---

Campaign Type Count

Studied the frequency of different campaign types.

![Campaign Type Count](Images/campaign_type_count.png)

---

Average ROI by Channel

Compared average return on investment across various channels.

"Average ROI by Channel" (images/average_roi_by_channel.png)

---

Conversion Rate by Channel

Analyzed conversion rates for each marketing channel.

"Conversion Rate by Channel" (images/conversion_rate_by_channel.png)

---

Acquisition Cost by Channel

Compared customer acquisition costs among different channels.

"Acquisition Cost by Channel" (images/acquisition_cost_by_channel.png)

---

Clicks by Channel

Examined customer interaction based on click counts.

"Clicks by Channel" (images/clicks_by_channel.png)

---

Impressions by Channel

Studied campaign reach through impressions.

"Impressions by Channel" (images/impressions_by_channel.png)

---

Engagement Score Distribution

Visualized customer engagement levels.

"Engagement Score Distribution" (images/engagement_score_distribution.png)

---

Correlation Heatmap

Analyzed relationships among Conversion Rate, Acquisition Cost, ROI, Clicks, Impressions, and Engagement Score.

"Correlation Heatmap" (images/correlation_heatmap.png)

---

Correlation between ROI and Conversion Rate

Investigated the relationship between ROI and conversion rate to understand campaign effectiveness.

"ROI vs Conversion Rate" (images/roi_conversion_rate.png)

---

Marketing Funnel Analysis

Analyzed customer journey stages using impressions and clicks.

"Marketing Funnel Analysis" (images/marketing_funnel_analysis.png)

---

Business Insights

- Marketing channels are fairly distributed across campaigns.
- ROI varies among channels, indicating differences in campaign effectiveness.
- Conversion rates influence campaign success and profitability.
- Engagement scores provide insights into customer interactions.
- Impressions are significantly higher than clicks, demonstrating a typical marketing funnel pattern.
- Correlation analysis helps identify relationships among important performance metrics.

---

Recommendations

- Allocate more budget to channels with higher ROI.
- Improve underperforming campaigns to increase conversions.
- Focus on enhancing customer engagement.
- Monitor key metrics continuously for better decision-making.
- Use data-driven strategies to maximize marketing performance.

---

Conclusion

This project successfully performed Exploratory Data Analysis on a marketing campaign dataset. The analysis provided valuable business insights regarding campaign performance, customer engagement, conversion rates, and ROI. These findings can support data-driven decisions and improve future marketing strategies.
