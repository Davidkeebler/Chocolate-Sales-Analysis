# Chocolate Sales Analysis and Prediction

## Project Overview
This project aims to delve into the trends and dynamics affecting chocolate sales using a comprehensive dataset. By analyzing key sales metrics such as total sales amount, number of boxes shipped, and geographical distribution, we can extract valuable insights. We also explore seasonal trends and the performance of various products and sales personnel, aiming to create a model that can predict future sales patterns. Our ultimate goal is to derive actionable business strategies to optimize sales performance.

The other main goal of this project was to leverage Mito AI, an extension for jupyterlab that integrates agentic AI directly into your notebooks, to create a high-quality portfolio project as quickly as I can. I'd say it was a great success - this project was done in about an hour and a half across two sittings. Hard to be more efficient than that!

## Methodology
1. **Data Acquisition & Preparation**: Downloaded the dataset using Kaggle\'s `kagglehub` library and prepared the data by cleaning and formatting necessary columns, such as the 'Amount'.

2. **Exploratory Data Analysis (EDA):**
   - Analyzed seasonal sales trends by aggregating sales data by year and month.
   - Investigated geographical sales distribution and product performance to reveal key insights.
   - Conducted a correlation study to identify potential features influencing sales amount.

3. **Modeling:**
   - Developed a linear regression model to predict sales amounts based on the number of boxes shipped. Despite `Boxes Shipped` showing potential as a predictor, the model exhibited a low R-squared value, indicating scope for model improvement.
   - Applied KMeans clustering to identify distinct customer segments based on purchasing behaviors, deriving clusters that guide strategic initiatives.

## Results
- Seasonal and geographical analysis provided actionable insights into high and low sales periods, along with product preferences across regions.
- Linear regression modeling highlighted the limitations of using a single feature for predictions, emphasizing the need for a comprehensive feature set.
- KMeans clustering uncovered three customer segments:
  1. **Cluster 0**: Low spenders with moderate box volumes, suitable for targeted promotions.
  2. **Cluster 1**: Average spenders with high box volumes, ideal for bulk offers.
  3. **Cluster 2**: High spenders with lower box volumes, benefiting from personalized engagement.

## Business Applications
- **Targeted Marketing**: Customize campaigns for each customer segment to boost conversion and retention.
- **Inventory and Product Management**: Align product planning with demand patterns identified through clustering.
- **Customer Experience**: Enhance personalization to foster engagement and loyalty through tailored interactions and loyalty programs.

This analysis and its insights serve as a foundation for driving data-informed sales strategies, optimizing operational decisions, and improving organizational sales performance.

