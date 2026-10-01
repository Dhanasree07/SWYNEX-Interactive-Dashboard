# SWYNEX-Interactive-Dashboard
# SWYNEX Netflix Interactive Dashboard

## Project Overview

This project is an interactive Netflix Content Analytics Dashboard created using Microsoft Power BI as part of my internship at SWYNEX Technologies.

The dashboard provides a visual overview of Netflix's content library and allows users to explore the data using interactive filters and visualizations.

## Objective

The main objective of this project is to transform a cleaned Netflix dataset into an interactive dashboard that helps users understand:

* The distribution of Movies and TV Shows
* Netflix content by country
* Content distribution by rating
* Content trends by release year
* Popular genre categories
* Overall Netflix content volume

## Dataset

The project uses a cleaned Netflix titles dataset containing information about movies and TV shows available on Netflix.

### Main Columns

* `show_id` – Unique identifier for each title
* `type` – Movie or TV Show
* `title` – Title name
* `director` – Director of the title
* `cast` – Cast members
* `country` – Country associated with the title
* `date_added` – Date the title was added to Netflix
* `release_year` – Original release year
* `rating` – Content rating
* `duration` – Movie duration or TV show seasons
* `listed_in` – Genre/category
* `description` – Title description

## Data Preparation

The dataset was cleaned and prepared before creating the dashboard.

The preparation process included:

* Checking for missing values
* Identifying duplicate records
* Removing duplicate records using the unique `show_id`
* Checking data types
* Handling inconsistent data
* Preparing the dataset for visualization

## Power BI Dashboard

The interactive dashboard contains:

### KPI

* **Total Netflix Titles**

### Visualizations

* **Netflix Content Distribution by Type**
* **Titles by Release Year**
* **Top 10 Countries by Title Count**
* **Netflix Titles by Rating**
* **Netflix Titles by Genre**
* **Top 10 Netflix Genres by Content Volume**

### Interactive Filters

Users can filter the dashboard using:

* **Content Type**
* **Content Rating**
* **Country**

These filters allow users to explore different parts of the Netflix dataset interactively.

## Tools & Technologies

* Microsoft Power BI
* Power Query
* DAX
* Python
* Pandas
* Google Colab
* GitHub

## Project Files

```text
SWYNEX_Netflix_Interactive_Dashboard/
│
├── SWYNEX_Netflix_Interactive_Dashboard.pbix
└── README.md
```

## Key Outcome

The project converts a raw Netflix dataset into an interactive Business Intelligence dashboard, making it easier to explore content distribution and identify patterns across different categories such as type, country, rating, genre, and release year.

## Internship

**SWYNEX Technologies – Data Analytics Internship**

This project demonstrates practical experience in data preparation, visualization, dashboard development, and Business Intelligence using Power BI.
