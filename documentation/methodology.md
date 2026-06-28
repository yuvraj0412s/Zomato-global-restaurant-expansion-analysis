# Methodology

## Data Cleaning & Preparation
- **Missing Value Treatment**: Imputed missing ratings using geographical averages where appropriate, and removed records with incomplete critical attributes.
- **Data Standardization**: Standardized currency symbols, cuisine formats, and location data to ensure consistency across the global dataset.
- **Outlier Detection**: Identified and isolated extreme outliers in "Average Cost for Two" and "Votes" using statistical thresholds.

## Feature Engineering
- **Categorization**: Grouped continuous pricing data into defined `Price_range` brackets (1-4) for clearer segmentation.
- **Geographic Hierarchy**: Built a structured Country-City-Locality hierarchy mapping to facilitate regional drill-down analysis.
- **Engagement Scoring**: Synthesized rating, votes, and rating text to create a composite restaurant engagement metric.

## Analytical Approach
- **Pivot Tables & Aggregation**: Used advanced Pivot Tables to summarize restaurant distribution, average ratings, and delivery options by country and city.
- **Cohort Analysis**: Analyzed restaurant cohorts based on pricing tiers to identify trends in user preferences and market saturation.
- **Benchmarking**: Compared emerging markets against established benchmarks (like India and the US) to identify white-space expansion opportunities.
