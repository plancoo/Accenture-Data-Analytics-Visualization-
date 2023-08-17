# `ACCENTURE DATA ANALYTICS AND VISUALISATION VIRTUAL EXPERIENCE PROJECT`

### In this fictional and immersive online experience, I am a Data Analyst at Accenture, and I work on an analysis of sample data sets with visualisations to understand the popularity of different content categories. Within my larger team, each member has a different role and level of responsibility. My team has been assigned a new project for a client called Social Buzz. 

### Although in the project, data cleaning, modelling, analysis and visualisation are all done on Excel, I wanted to use Pandas for data cleaning and modelling, PostgreSQL for database solution and Grafana for data visualisation. 

----

# Project tasks:
Read through the client brief and understand the client and business problem at hand.

Analyse the background information provided to identify the requirements that I need to deliver as a data analyst. 

Identify which task should be assigned to me to ensure my team is aligned on deliverables.

----

# Client
Social Buzz is a San Francisco based fast growing company which tracks anonymous user reactions on contents. We are running a 3-month POC focusing on these tasks: ​

- An audit of their big data practice ​

- Recommendations for a successful IPO ​

- An analysis of their content categories that highlights the top 5 categories with the largest aggregate popularity​

# Business Problem

The client has reached a massive scale within recent years and does not have the resources internally to handle it.
 the client stated that scale was a big problem of theirs and they are struggling to manage the scale with the resources that they currently have. The brief said that the client is looking for help with the management of their journey into such a large scale

Over 500 million active users each month producing over 100,000 ​pieces of content per day! ​

How to see where they are with this highly unstructured big data?​

An analysis of their content categories that highlights the top 5 categories with the largest aggregate popularity​

# Solution

**Our data analysis system** will obtain, process, and collate the volume of data and provide data analysis to the client and business to make strategic business decisions.

----
# The Approach

![](./docs/data_analytics_process.jpg)
1) Data Understanding: Identify right data set to work on among 7 data sets (Reaction, Content, Reaction Types​)
2) Data Cleaning: Removing rows with missing values, changing the data type of some values within a column, and removing irrelevant columns ​
3) Data Modelling: Create a final data set by merging the three tables together​
4) Data Analysis: Figure out the Top 5 performing categories​
5) Uncover Insights: Bring the data to life using visualisations​


# Getting Started

## Installing

Creating virtual environment:
`py -m venv .venv`

Activating virtul environment:
`.venv\Scripts\activate`

Upgrading pip:
`python.exe -m pip install --upgrade pip`

Installation of pandas:
`pip install pandas`

Installation of notebook:
`pip install notebook`

Installation of SQLAlchemy to insert dataframe values to the database:
`!pip install SQLAlchemy Flask-SQLAlchemy`

Related GitHub commands:
```
git clone + SSH LINK
git status
git add .
git commit -m "COMMIT MESSAGE"
git push
```
Installing PostgreSQL and Docker container:
* to install psycopg2: `py -m pip install psycopg2` 
* to install python-dotenv: `py -m pip install python-dotenv`
* to pull PostgreSQL docker image: `docker pull postgres`
* to start the container: `docker-compose up -d` 

![](./docs/database_schema.jpg)

## Data Visualisations

What are the top 5 popular categories?

![](./docs/social_buzz_top_5_popular_products_viz.jpg)

![](./docs/social_buzz_percentage_of_top_5_popular_products_viz.jpg)

How many unique categories are there?

![](./docs/social_buzz_total_unique_categories.jpg)

![](./docs/social_buzz_unique_categories_viz.jpg)

How many reactions are there to the most popular category?

![](./docs/social_buzz_total_reactions_to_animals_category_viz.jpg)

![](./docs/social_buzz_total_positive_reactions_to_animals_category_viz.jpg)

What was the month with the most posts?

![](./docs/social_buzz_month_with_most_posts_viz.jpg)

How many unique contents are there?

![](./docs/social_buzz_total_number_of_unique_contents_viz.jpg)

What was the month with the most posts for each popular category?

![](./docs/social_buzz_month_with_most_posts_for_each_category_viz.jpg)

## Data Analysis

Animals, science, healthy eating, technology and food are the most popular content categories.​

#### INSIGHT​

* Healthy eating and food categories get most posts in May. Client could use this insight to create a campaign launched in this month and work with healthy eating brands to boost user engagement.​

* 1050 of 1897 reactions for the most popular  category, animals, are positive. This might suggest that the audience more likely give positive reactions to animal related posts. Client may want to post more cute animals.​
