![ff](https://newlightdigital.com/wp-content/uploads/2023/08/Marketing-Strategies-Any-Business.png)

# Analyzing Kickstarter Campaigns: A Path to Crowdfunding Success
Kickstarter Campaign: Exploratory data analysis project.

# Project Overview
Description
<div style = "text-align: right">This project focuses on analyzing Kickstarter campaigns to identify key factors that contribute to successful crowdfunding efforts. Successful campaigns not only help project founders achieve their funding goals but also enhance the overall effectiveness of the Kickstarter platform.The goal of this project is to uncover insights that can guide creators in developing more effective crowdfunding strategies.</div>

By performing exploratory data analysis (EDA), this project aims to:

1. Identify patterns and trends in successful Kickstarter campaigns.
2. Understand the impact of factors such as campaign length, funding goals, and launch timing.
3. Provide actionable recommendations for project founders to optimize their campaigns.
4. This analysis can help creators enhance their campaign strategies, improve backer engagement, and ultimately increase the likelihood of funding success, leading to better outcomes for both project founders and backers.

# Data
## 1.How to run
Google Colab Users:
Upload the raw dataset found in "kickstarters_dataset" to you google drive 

## 2.Dependencies
The following is a list of libraries used in this project:-
The following is a list of libraries used in this project:-

Data Manipulation: packages like pandas and numpy that are used to handle and import datasets.
import pandas as pd
import numpy as np
Data Visualization: packages that were used to plot graphs for analysis or to comprehend matplotlib and seaborn.
import matplotlib.pyplot as plt matplotlib was used to create basic visualizations like bar charts and histograms
import seaborn as sns: builds more advanced and aesthetically pleasing plots, such as heatmaps and pair plots, to explore relationships in the data. Together, these libraries enable efficient analysis and visualization of medical appointment no-shows.


# Dataset

The dataset includes **4,448 Kickstarter projects**, described by **16 variables** such as project ID, name, URL, category, status, funding goal, amount pledged, percentage funded, and number of backers. These variables offer insights into project success, funding trends, and backer engagement.

**Kickstarter** is a crowdfunding platform that allows creators to fund their projects through small contributions from a large number of people. It supports a wide range of categories, including art, technology, film, and music, enabling innovators to bring their ideas to life while engaging with a community of backers.


| Variable             | Type      | Description                                                                                     |
|----------------------|-----------|-------------------------------------------------------------------------------------------------|
| Project id           | int64     | Unique identifier for each Kickstarter project.                                               |
| Name                 | object    | The title of the Kickstarter project.                                                          |
| Url                  | object    | The URL link to the Kickstarter project page.                                                 |
| Category             | object    | The main category under which the project is listed (e.g., Film & Video, Music, Games).       |
| Subcategory          | object    | More specific category of the project (e.g., Animation, Documentary).                         |
| Location             | object    | The geographical location of the project creator or where the project is based.               |
| Status               | object    | The current status of the project (e.g., successful, failed, live).                           |
| Goal                 | float64   | The funding goal set by the project creator (in USD).                                         |
| Pledged              | float64   | The amount of money backers contribute to the campaign. Pledges vary by reward tier.           |
| Funded Percentage    | float64   | The percentage of the goal that has been funded.                                              |
| Backers              | int64     | An individual who pledges money to a crowdfunding campaign, supporting the project.            |
| Funded Date          | object    | The date when the project was funded or the funding period ended.                             |
| Levels               | int64     | The number of different reward levels offered to backers.                                      |
| Reward Levels        | object    | The monetary amounts for each reward tier (e.g., $1, $10, $25).                              |
| Updates              | int64     | The number of updates provided by the project creator.                                         |
| Comments             | int64     | The number of comments made by backers or the public.                                         |
| Duration             | float64   | The duration of the funding period in days.                                                   |





Jupyter Notebook/Lab Users: 
- Download the dataset and the notebook
- Make sure that the dataset is in the same folder as the notebook
- Uncomment the "cell"
- Run all cells


# Machine Learning Framework Implementation
