Project Overview

This project presents an interactive Netflix Content Analysis Dashboard created using Tableau. The objective of this project is to explore and visualize the Netflix titles dataset to understand the distribution of movies and TV shows based on country, rating, release year, and content type.

The dashboard transforms raw Netflix data into meaningful visualizations that make it easier to identify patterns, trends, and characteristics of Netflix's content library.

This project is designed as a Data Visualization / Data Analytics project and demonstrates the use of Tableau for exploratory data analysis and dashboard creation.

🎯 Objectives

The main objectives of this project are:

To analyze the overall distribution of Movies and TV Shows on Netflix.
To understand the contribution of different countries to Netflix's content library.
To analyze the distribution of content according to ratings.
To understand how Netflix content is distributed across different release years.
To create an interactive and visually appealing dashboard using Tableau.
To convert raw data into meaningful insights that can be easily understood by users.
📂 Dataset

The project uses the Netflix Titles Dataset, which contains information about movies and TV shows available on Netflix.

Important columns used in this project:
Column	Description
Show Id	Unique identifier for each Netflix title
Type	Specifies whether the title is a Movie or TV Show
Title	Name of the movie or TV show
Director	Director of the title
Country	Country or countries associated with the title
Date Added	Date on which the title was added to Netflix
Release Year	Original release year of the title
Rating	Age/content rating of the title
Duration	Duration of a movie or number of seasons for a TV show
Listed In	Categories or genres associated with the title

Only selected columns are used for the dashboard to focus on the most relevant analytical questions.

🛠️ Tools & Technologies
Tableau – Data visualization and dashboard development
CSV Dataset – Data source
Git & GitHub – Version control and project hosting
📊 Dashboard Components

The dashboard consists of four major visualizations.

1. 🌍 Content by Country

This visualization shows the number of Netflix titles associated with different countries.

Fields used:
Rows: Country
Columns: Count of Show ID
Color: Rating
Purpose:

This chart helps identify countries that contribute a larger amount of content to Netflix.

Insight:

The visualization shows that the number of Netflix titles varies considerably between countries. Some countries contribute significantly more titles than others, while several countries have relatively smaller amounts of content.

This allows us to understand the geographical distribution of Netflix's content library.

2. ⭐ Country-wise Rating Distribution

This visualization analyzes Netflix content based on Country and Rating.

The ratings include categories such as:

TV-MA
TV-14
TV-PG
PG
PG-13
R
TV-G
TV-Y
TV-Y7
NR
G
NC-17
UR
Fields used:
Country
Rating
Count of Netflix titles
Purpose:

The visualization helps understand how content ratings are distributed across different countries.

Insight:

The chart demonstrates that Netflix content consists of a wide variety of ratings. The distribution of ratings differs across countries, showing that Netflix's content library contains content intended for different audience groups.

3. 📅 Content by Release Year

A Treemap is used to visualize the distribution of Netflix titles according to their release year.

Fields used:
Release Year
Count of Netflix titles
Purpose:

The treemap provides a quick visual representation of the number of titles associated with different release years.

Insight:

Larger sections represent years with a larger number of titles, while smaller sections represent years with fewer titles.

This visualization makes it easy to identify periods in which a greater amount of Netflix content was released.

4. 🎥 Movies vs TV Shows

This visualization compares the number of Movies and TV Shows available in the dataset.

Fields used:
Columns: Type
Rows: Count of Show ID
Purpose:

The purpose of this chart is to understand the overall composition of Netflix's content library.

Insight:

The visualization clearly shows that Movies form a considerably larger portion of the dataset than TV Shows.

Therefore, based on this dataset, Netflix has more movie titles than TV show titles.

📌 Key Insights

The dashboard provides several important insights into Netflix's content library:

1. Movies dominate the dataset

The number of Movies is considerably higher than the number of TV Shows.

This indicates that movies make up the larger share of the Netflix titles represented in the dataset.

2. Content varies significantly by country

Netflix's content is distributed across many countries, but the number of titles associated with each country is not equal.

Some countries contribute a much larger number of titles than others.

3. Netflix contains a wide range of ratings

The dataset contains many different rating categories, ranging from ratings intended for children to mature audiences.

This demonstrates the diversity of Netflix's content for different age groups.

4. Content is distributed across multiple release years

The release-year visualization shows that Netflix contains titles released across many different years.

Some years contain significantly more titles than others.

5. Multiple dimensions can be analyzed together

By combining Country, Rating, Release Year, and Type, the dashboard provides a broader understanding of Netflix's content rather than focusing on only one characteristic.

🎨 Dashboard Design

The dashboard combines four different visualizations into a single view:

┌──────────────────────────────────────────────────────┐
│             NETFLIX CONTENT ANALYSIS                 │
├──────────────────────────┬───────────────────────────┤
│                          │                           │
│   Content by Country     │ Country-wise Rating       │
│                          │ Distribution              │
│                          │                           │
├──────────────────────────┼───────────────────────────┤
│                          │                           │
│   Content by Release     │ Movies vs TV Shows        │
│   Year                   │                           │
│                          │                           │
└──────────────────────────┴───────────────────────────┘

Skills Demonstrated
This project demonstrates the following skills:
Data Visualization
Exploratory Data Analysis
Tableau
Dashboard Development

The dashboard makes it easier to understand:
What type of content Netflix has, where the content comes from, how content is distributed by rating, and how the content is distributed across release years.
