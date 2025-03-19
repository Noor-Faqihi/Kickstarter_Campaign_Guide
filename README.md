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




# Dataset
<div style = "text-align: right">The dataset contains information from various Kickstarter projects, with a total of 4,448 entries. Each project is described by 16 variables, which include details such as project ID, name, URL, category, subcategory, location, status, funding goal, amount pledged, percentage funded, number of backers, funded date, reward levels, updates, comments, and project duration. These variables provide insights into the success and characteristics of different crowdfunding campaigns, helping to analyze trends in project outcomes, funding strategies, and backer engagement.

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
