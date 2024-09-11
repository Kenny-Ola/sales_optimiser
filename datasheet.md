# Datasheet: Proprietary Sales Dataset

## Motivation

- Dataset was created to provide a comprehensive view of sales performance across different product categories and regions.
- It is being used to train our AI-driven sales optimization model for enhancing business processes related to sales and cost management.

## Composition

- The dataset contains historical sales data including Sales, Cost, Revenue, and Product Categories.
- Instances: 100,000 sales records
- Features: Sales, Cost, Revenue, Product Category, Customer Segment, Region
- Missing data: Less than 1% missing values, imputed using mean for numerical and mode for categorical data

## Collection Process

- Data was collected from multiple retail outlets over a period of 2 years
- Sampling strategy: Random sampling of transactions, ensuring representation across all product categories and regions
- Time frame: January 2021 to December 2022

## Preprocessing/Cleaning/Labeling

- Outliers were removed using the Interquartile Range (IQR) method
- Currency values were normalized to USD
- Product categories were standardized across all regions

## Uses

- The primary use is for sales optimization and cost management in businesses.
- This dataset should not be used for individual customer profiling or any purpose that may infringe on privacy rights.

## Distribution

- The dataset is proprietary and not publicly available.
- Access is restricted to authorized personnel within the company.

## Maintenance

- The dataset is maintained by our data science team
- It is updated quarterly with the latest sales data