### BuzzScale IPO & Data Optimization Project

Overview
The BuzzScale IPO & Data Optimization Project is focused on analyzing social media content to drive insights for optimizing BuzzScale’s upcoming IPO. The project uses data from multiple sources, including content performance, reactions, and sentiment analysis. The primary goal is to uncover insights that can inform business strategies for content creation and engagement.

Key components:

Data Understanding: Analysis of content, reactions, and sentiment from BuzzScale's social media interactions.
Data Cleaning: Preparation of clean datasets from original raw data, including three key CSV files (Content, Reactions, Reaction Types).
Data Modeling: Aggregate score calculations, category ranking, and workflow optimization.
Data Analysis: Insights into the top-performing content types and reaction trends.
Visualization: Dashboards and charts created using Power BI/Tableau for strategic decision-making.

1. Key Objectives:

- Analyze top-performing content categories to identify which categories have the highest engagement.
- Assess sentiment across content to understand how audiences react to various types of content.
- Provide recommendations based on the data to help optimize content strategy ahead of BuzzScale’s IPO.
- Datasets Used
- The analysis relies on three datasets:

2. Content Dataset:

- Columns: Content ID, Content Type, Category
- Describes different types of content (videos, articles, etc.) along with their respective categories.
- Reactions Dataset:

3. Columns: Category, Aggregate Score

- Contains aggregated data on audience reactions to various content categories.
- ReactionTypes Dataset:

4. Columns: Type, Sentiment Type, Score

- Provides sentiment scores (positive, neutral, negative) for each reaction type across different content.

### Project Workflow

1. Data Understanding:
We began by exploring the structure and contents of the datasets to gain insights into how the data could be utilized.
The Content Dataset provided the backbone for understanding different categories and content types.
The Reactions Dataset helped identify the aggregate performance of content based on user engagement.
The ReactionTypes Dataset was used to analyze sentiment, helping gauge audience reactions across categories.

2. Data Cleaning & Feature Engineering:
Data Cleaning: We handled missing values, removed duplicates, and ensured consistency across the datasets. This process was key to ensuring the reliability of the insights.
Feature Engineering: New features, such as sentiment scores for each category and aggregate scores for reactions, were created to facilitate better analysis. Using Microsoft Excel, we ensured data accuracy and consistency through various data cleaning techniques. Missing values were handled using IFERROR(), IFNA(), and IF(), while duplicates were removed using the Remove Duplicates feature. Data standardization was achieved with TEXT(), TRIM(), PROPER(), and SUBSTITUTE(), and Data Validation was applied to maintain input integrity. Power Query was leveraged for automating transformations like merging, filtering, and reshaping datasets. For feature engineering, advanced Excel formulas such as IF(), COUNTIF(), AVERAGEIFS() were used to create sentiment scores, while Pivot Tables and SUMIF() helped aggregate reaction-based insights. Lookup and data mapping were facilitated using VLOOKUP() and INDEX MATCH, ensuring seamless data integration. Additionally, FILTER(), UNIQUE(), and SORT() enabled dynamic data categorization, making the dataset more structured and analysis-ready. By integrating Excel’s Advanced Functions, Power Query, Pivot Tables, and Data Validation, we created a robust foundation for accurate and insightful analysis.

3. Data Modeling:
Using Power BI, relationships between datasets were modeled to enable seamless analysis.
Three key tables were connected: Content, Reactions, and ReactionTypes, allowing for cross-filtering and data-driven insights.

4. Data Analysis and Visualization:
Visualization 1: Top 5 Categories by Aggregate Score:
A bar chart was created to highlight the top 5 content categories based on their aggregate scores. This visualization allows BuzzScale to focus on categories that drive the most engagement.

Visualization 2: Sentiment Distribution Across Categories:
A pie chart visualizes the distribution of sentiment (positive, neutral, negative) across content categories. It shows the audience's emotional response to each type of content.
Interactive Slicers: The dashboard includes slicers that allow users to filter by each category along with it's percentage share

5.Key Insights
Top 5 Categories:

The top-performing categories are:
Animal – 21.4%
Science – 20.3%
Healthy Eating – 19.8%
Technology – 19.6%
Food – 19.0%

These categories should be the focus for content creation leading up to the IPO.

Sentiment Analysis:

The majority of content receives positive engagement, particularly in the Technology and Healthy Eating categories. However, the Science category has a higher proportion of neutral or negative sentiment.
This indicates an opportunity for BuzzScale to refine its messaging in certain categories.

Conclusion
The BuzzScale IPO & Data Optimization project successfully uncovered key insights into social media content performance by analyzing and optimizing reaction data across various categories. Through data cleaning, feature engineering, and visual analysis, we were able to identify top-performing content categories and understand user sentiment patterns. Our findings highlight the value of targeted content strategies to enhance engagement, improve brand sentiment, and maximize social media reach. The application of advanced data analytics techniques, such as aggregate scoring and reaction-based analysis, provided actionable recommendations that can help guide BuzzScale in optimizing their social media content strategy for future growth and market expansion.
