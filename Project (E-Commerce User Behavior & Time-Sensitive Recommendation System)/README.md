# E-Commerce User Behavior Analysis & Recommendation System

## Project Description
This project analyzes e-commerce user behavior from a dataset of over 4.2 million events in October 2019. It includes data cleaning, exploratory analysis (behavior, affinities, customer metrics, categories), time-sensitive collaborative filtering recommendations, user segmentation, journey visualization with abandonment analysis, predictive purchase timing, and A/B testing simulation.

## Structure
- `data/raw/`: Raw dataset.
- `data/processed/`: Cleaned data.
- `src/`: Notebook.
- `visuals/`: Saved plots (subfolders per task).
- `reports/`: Final report with insights.

## Methodology Summary
- **Data Cleaning**: Parsed timestamps, filled missing values, removed duplicates/anomalies.
- **EDA**: Aggregations for events, visitors, affinities; visuals with seaborn/matplotlib.
- **Recommender**: Weighted collaborative filtering with cosine similarity; time filters.
- **Segmentation**: KMeans on scaled behavioral features.
- **Visualization**: Seaborn lines/pies for journeys/abandonment.
- **Predictive**: Hourly price aggregation.
- **A/B**: Randomized simulation with t-test.

## Key Insights
- Users mostly view products; purchases are rare.
- Popular categories: electronics.smartphone, appliances.
- Recommendations use collaborative filtering with time features.

- 96% views, 93% cart abandonment
- Electronics: 43% traffic, smartphones top subcategory
- Recommender Precision@5: 0.123
- Segments: 84% browsers, 14% buyers, 2% abandoners
- Optimal buy hour: 1 AM
- A/B lift: +11% engagement
