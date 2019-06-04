# Visualize European Soccer Database
## by Jeremy Sung
## Objective
In this report I inspected Kaggle's European Soccer Database and explore interesting insight using techniques in Python.
### Dataset Overview
[Kaggle European Soccer Database](https://www.kaggle.com/hugomathien/soccer), is in RDBMS format (SQLite DB) and contains European Professional Football records for 25k+ soccer matches, 11 lead championships in Europe and 79 players & teams attibutes between 2008 and 2016.
- I used the sqlite3 module and Pandas to retrieve SQLite tables to dataframes. In the process, involved analytics and visualization modules are listed as follows,
 - Analytics: numpy, scipy, nltk, and pandas.
 - Data visualization techniques: matplotlib, seaborn, mpl_toolkits, plotly, folium, networkx, PIL, and wordcloud.
- Instead of SQL join, I used Pandas Merge to combine data in dataframes and conduct analyses.
## Story
Like baseball and basketball, Soccer is a team sport. Both players and teams are the center of focus when it comes to evaluation and prediction. Matches and leagues are built around them, followed by countries and others.

Analyzing the league, country, player, player attributes, team and team atributes tables gave a better understanding of the data. Once the respective features are joined and merged with the match table, machine learning algorithms can be used to predict the winner of the future soccer matches in the european league. This kernel also allows for the opportunity to practice using the seaborn library and visualizing the data.

Domain knowledge is essential in data analysis. In this case deep understanding of the meaning of each attributes can certainly helps on these decision:
- Choose relavent categories when making radar charts,
- Recognize key attributes to evaluate players,
- select criteria to identify so-called top rated players, etc.

Fortunately, search engines are our friends. Blogs, news, tutorials can be good resouces and are only a few keystrokes away to build required knowledge.  

In this project I created graphic illustration to answer questions. I created Team Comparator and Player Comparator. Some of the questions are listed as follows,

- **Does Player's "Overall Rating" depend on any Player Attribute(s)?**
- **What are the similarities and differences in terms of skills among Top Overall_Rating Players?**
- **Create a Word Cloud for players with Overall Rating beyond 88**
- **Does the proportion of preferred foot change between all players and top players with overall rating higher than 80?**, etc.
