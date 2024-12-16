# Shopping Trends Analysis Project

This project analyzes the location-specific performance of **Roots**, focusing on customer satisfaction and sales growth over the past four seasons. The goal is to identify high-performing locations, understand the factors driving their success, and provide actionable recommendations for improving service quality and revenue.

---

## Dataset

- **Name**: Shopping Trends
- **Source**: [Kaggle](https://www.kaggle.com)  
- **Description**: This dataset contains information on sales performance and customer satisfaction for various locations of Roots, covering four seasons of data.  
- **Fields**: 19 (including `Location`, `Review Rating`, `Purchase Amount`, and seasonal performance metrics)

---

## Problem Statement

### Objectives:
1. Identify the location with the highest average customer satisfaction.
2. Determine the location with the highest sales growth and analyze the product categories contributing to this growth.

---

## Tools and Technologies Used

1. **SPSS**: Statistical analysis and customer satisfaction trends.
2. **IBM Cognos Analytics**: Sales growth analysis and regional insights visualization.

---

## Methodology

### Step-by-Step Analysis:

1. **Data Acquisition**:
   - Downloaded the dataset from Kaggle and imported it into SPSS for preprocessing.
   
2. **Data Cleaning**:
   - Verified the data for inconsistencies and missing values.
   - Ensured proper formatting for fields like `Location`, `Review Rating`, and `Purchase Amount`.

3. **Data Aggregation**:
   - Grouped the data by `Location` to calculate:
     - **Mean Review Rating**: To evaluate customer satisfaction.
     - **Sum of Purchase Amount**: To measure total sales.

4. **SPSS Analysis**:
   - Created heatmaps to visualize customer satisfaction trends by location.
   - Summarized seasonal variations in `Purchase Amount` and `Review Rating`.

5. **Cognos Analysis**:
   - Analyzed sales growth trends across locations.
   - Identified the product categories driving sales growth in top-performing locations.

6. **Correlation Analysis**:
   - Assessed the relationship between `Purchase Amount` and `Review Rating`.
   - Found a weak correlation (0.031), indicating other factors influence sales growth.

7. **Visualization**:
   - Created detailed reports using tables and heatmaps to highlight regional and seasonal trends.

8. **Recommendations**:
   - Proposed actionable insights to replicate the success of high-performing locations.

---

## Key Insights

1. **Highest Customer Satisfaction**:
   - California recorded the highest average satisfaction scores over four seasons.
2. **Highest Sales Growth**:
   - Florida showed the most significant sales growth, driven by specific product categories.
3. **Seasonal Trends**:
   - Sales peaked during specific seasons in certain regions, presenting opportunities for seasonal promotions.
4. **Weak Correlation**:
   - Minimal relationship between customer satisfaction and sales, emphasizing the importance of other business strategies.

---

## Recommendations

Based on the insights, the following strategies are recommended:

1. **Targeted Marketing**:
   - Develop location-specific promotions based on high-performing location data.
2. **Seasonal Campaigns**:
   - Introduce discounts and product launches during underperforming seasons.
3. **Customer Engagement**:
   - Enhance customer service in low-performing areas with staff training and direct feedback.
4. **Localized Offerings**:
   - Cater to the cultural preferences and needs of customers in underperforming regions.
5. **Enhanced Online Presence**:
   - Strengthen regional marketing efforts through digital ads and influencer collaborations.

---

## How to Run This Project

1. **Dataset Preparation**:
   - Download the `shopping_trends.xlsx` dataset from Kaggle.
   - Import the dataset into SPSS and Cognos for analysis.

2. **SPSS Workflow**:
   - Perform data aggregation and calculate key metrics.
   - Generate visualizations to identify satisfaction and seasonal trends.

3. **Cognos Workflow**:
   - Analyze sales growth and identify regional and product-specific insights.
   - Export visualizations for reporting.

4. **Result Interpretation**:
   - Consolidate findings to derive actionable recommendations.

---

## Conclusion

This project demonstrates the power of data analytics in uncovering trends and providing insights to enhance business performance. By implementing the recommendations, Roots can optimize its operations, replicate successful strategies, and address underperforming areas effectively.

---


