# TikTok Dataset Analysis

## Overview

This project involves analyzing a TikTok dataset to gain insights into user engagement, content performance, and author statistics. The analysis includes visualizations and statistical summaries to understand patterns in views, likes, and other metrics. The project uses Python and various data analysis libraries, including Pandas, Matplotlib, and Seaborn.

## Analysis Objectives

The goal is to better optimize content and improve product operations. To achieve this, analysis focuses on two main aspects:

- **Operational Performance:**
  - Analyzing platform views over time
  - Music usage statistics
  - Volume of content published
  - Completion rates of content

- **User Characteristics:**
  - **Clustering:** Segment users into clusters for targeted operational strategies. Users can be categorized into three main groups: User, Author, and Content.
    - **User:** Metrics include views, likes, and the number of authors followed.
    - **Author:** Metrics include total works, total views, total likes, completion rates, and music usage.
    - **Content:** Metrics include views, likes, and music associated with the content.

## Dataset

The dataset `tiktok_dataset.csv` contains the following columns:
| Field         | Description            | Field      | Description       |
|---------------|------------------------|------------|-------------------|
| uid           | User ID                | like       | Whether liked      |
| user_city     | User City              | music_id   | Music ID           |
| item_id       | Item ID                | duration_time | Item Duration     |
| author_id     | Author ID              | real_time  | Publish Time       |
| item_city     | Item City              | H          | Hour (Published)   |
| channel       | Channel                | date       | Day (Published)    |
| finish        | Finished Watching      |            |                   |


## Installation

To run this analysis, you need to have Python installed along with the following libraries:
- `pandas`
- `matplotlib`
- `seaborn`

You can install the necessary libraries using pip:

```bash
pip install pandas matplotlib seaborn
```
## Usage and dataset 

Place the tiktok_dataset.csv file in the project directory.

[Link](https://drive.google.com/drive/folders/1nFF3p1CP_pvSQn4XJP2McMT8Hq8988Fj?usp=drive_link) to download dataset: 


## Analysis and Visualizations

1. **Number of Items per Day**

   Visualizes the number of items posted per day, showing the distribution of content over time.

2. **Daily Stats: Number of Items and Finish Rates**

   Shows the number of items and finish rates for each day. This dual-axis plot illustrates trends in the quantity of items and the finish rate over time.

3. **Views vs. Likes Scatter Plot**

   Displays the relationship between the number of views and likes for each item, highlighting how visibility correlates with engagement.

4. **Correlation Heatmap of Author Statistics**

   Provides a heatmap showing correlations between different author statistics such as total works, views, likes, plays, and music usage. This visualization helps to identify relationships and dependencies among various metrics.

## Insights

- **Content Visibility:** Items that receive more views tend to receive more likes, reinforcing the idea that visibility often translates to engagement.
- **Daily Trends:** Analyzing the number of items and finish rates daily provides insights into content distribution and performance trends.
- **Author Statistics:** Correlation analysis of author metrics can guide content strategy by revealing relationships between different performance indicators.
