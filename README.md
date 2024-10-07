# Youtube-Data-Analytics
Basic Data Analysis on Youtube Data Set

This project is an analysis of YouTube trending videos using various machine learning and statistical techniques. It explores the engagement metrics, title analysis, trending patterns, and channel frequencies from a dataset containing YouTube video trends.

Table of Contents
Project Overview
Dataset
Technologies Used
Project Structure
Key Findings
Usage
Conclusion
Project Overview
The main goal of this project is to analyze trending YouTube videos across different categories and identify key patterns such as word usage in video titles, engagement rates (likes, dislikes, comments), and category popularity. The analysis covers both statistical and visual approaches to understanding YouTube trends.

Dataset
The dataset used in this project is the US YouTube trending video dataset, containing columns such as:

video_id: Unique identifier for the video.
title: Title of the video.
channelTitle: Name of the channel.
categoryId: Category of the video.
view_count, likes, dislikes, comment_count: Engagement metrics for each video.
The dataset can be found on Kaggle, and it consists of trending videos from various categories such as entertainment, music, sports, and more.

Technologies Used
Python: Main programming language.
Libraries:
numpy, pandas: Data manipulation and analysis.
matplotlib, seaborn: Data visualization.
sklearn: Machine learning models and clustering.
nltk: Natural Language Processing for title analysis.
scipy: Statistical analysis.
Project Structure
Data Cleaning: Handling missing values, converting date columns to datetime objects, and removing irrelevant columns.
Exploratory Data Analysis (EDA): Analyzing video trends, engagement metrics, and title word usage.
Statistical Analysis: Performing ANOVA and Chi-square tests to understand the relationships between categories and engagement.
Clustering: Using K-Means clustering to segment videos based on engagement metrics.
Visualizations: Creating heatmaps, bar charts, and scatter plots to visualize trends in the data.
Key Findings
Top Trending Categories: Categories such as entertainment, music, and sports dominate the YouTube trending videos.
Title Word Analysis: Commonly used words in video titles include "trailer," "official," and "season," which contribute to higher engagement.
Engagement Patterns: Videos with a high like-to-dislike ratio and active comment sections tend to perform better in terms of views.
Channel Trends: Channels like NFL, NBA, and MrBeast are among the top trending channels.
Video Trending Time: Some categories of videos take longer to trend after being published, while others trend quickly.
