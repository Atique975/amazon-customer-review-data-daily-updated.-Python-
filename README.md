# Amazon Customer Review Data Analysis

This project focuses on analyzing Amazon customer reviews to extract meaningful insights into customer sentiments, review patterns, and engagement metrics. The analysis was conducted using Python, leveraging a variety of data science libraries and tools. The dataset used for this analysis is updated daily, providing a dynamic view of customer feedback.

## Project Overview

### Data Cleaning and Preparation
- **Handled Missing Values:** Addressed missing data and inconsistencies to ensure a clean dataset for analysis.
- **Column Renaming:** Renamed columns for clarity and standardized data formats for consistency throughout the analysis.

## Exploratory Data Analysis (EDA)
- **Score Distribution:** Visualized the distribution of review scores to gauge overall customer sentiment and prevalence of different ratings.
- **Sentiment Analysis:** Conducted sentiment analysis to understand patterns in customer satisfaction.

### Correlation and Trends
- **Review Length vs. Rating:** Explored the relationship between the length of customer reviews and their ratings. Longer reviews tend to provide more balanced feedback.
- **Thumbs Up Count:** Analyzed how the number of thumbs-up a review received correlates with its score, revealing that higher-rated reviews often receive more thumbs-up.
- **Sentiment vs. Thumbs Up:** Examined how sentiment scores relate to thumbs-up counts, providing further insight into customer engagement.

### Keyword Analysis
- **Common Keywords:** Identified and visualized the most frequent keywords in both positive and negative reviews, highlighting recurring themes and issues discussed by customers.

## Key Findings
- **Review Score Distribution:** The distribution indicates that negative reviews are more prevalent, suggesting potential areas for improvement in customer satisfaction.
- **Sentiment Trends:** Due to the daily updating nature of the data, comprehensive trend analysis over time was not performed. Instead, the focus was on overall sentiment distribution and patterns.
- **Review Content Analysis:**
  - **Common Themes:** Users frequently discuss their experiences with Amazon's app performance, ordering process, account management, customer service, and the need for improvements.
  - **Impact of Review Length:** Longer reviews tend to have lower ratings, possibly reflecting a more balanced perspective where both pros and cons are discussed.
  - **Thumbs-up Counts:** Reviews with more thumbs-up are generally rated higher, indicating that reviews resonating with others are seen as more positive and valuable.

## Future Work
- **Incorporate Product Information:** Including product-specific data could enhance insights into review patterns and sentiments.
- **Extended Sentiment Analysis:** Applying advanced sentiment analysis techniques or sentiment lexicons might yield more nuanced results.
- **Trend Analysis:** Investigating seasonal or event-driven trends could reveal additional patterns in customer feedback.

## Acknowledgments
- **Data Source:** The dataset used for this analysis was sourced from Kaggle.
- **Libraries and Tools:** This project was implemented using Python, with key libraries including Pandas for data manipulation, NumPy for numerical operations, and Matplotlib and Seaborn for data visualization. The development environment was Jupyter Notebook, and the project was executed on Kaggle Kernels to facilitate sharing and collaboration.
