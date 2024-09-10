[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QM6TDYML)

Team Members:

Dimple Singh
Jay Balaram Sankhe
Debangana Ghosh
Jeremy Anton
Ritika Sanjay Kale


Introduction: This project explores the potential of social media data in identifying and analyzing trends within the movie industry, specifically focusing on popular movies, TV shows, and genres. By analyzing posts and comments related to movies and TV shows on platforms like Reddit and The Movie Database (TMDb), we aim to uncover insights into audience preferences and emerging trends.
Reddit and TMDb, two widely used platforms, generate vast amounts of text data through posts and comments. To achieve our objectives, we employed APIs from Reddit and TMDb to collect posts associated with relevant subreddits such as "r/movies" and "r/tv".
We analyze the distribution of discussions and engagement across different movie genres to reveal emerging preferences and shifts in audience taste. 
In this analysis, we utilized various types of graphs to visually represent trends and patterns within the movie and TV genre landscape sourced from Reddit and The Movie Database (TMDb). Collectively, our findings present a data-driven analysis of trending movies and TV genres over a specified timeframe, providing insights into the dynamic nature of the entertainment industry within this particular domain. 

The project demonstrates the potential of combining social media data with API-driven analyses to gain actionable insights into current trends, contributing to a more informed understanding of the evolving landscape in the movie and genre domains. 
This project will contribute to a deeper understanding of how social media shapes movie popularity and influences genre trends, providing valuable insights for filmmakers, distributors, and anyone interested in the dynamics of the movie industry.

Libraries requirements:

1)flask
2)psycopg2
3)pandas
4)io
5)base64
6)matplotlib.pyplot
7)seaborn
8)os



How to Run the code:
configure apache config file to point to the venv and python flask app. 
Run sudo systemctl restart apache command. 

Create Virtual Environment using virtualenv package
virtualenv -p python3 env
Create postgres database and keep it open for connection
systemctl restart postgresql@16-main.service
Activate the virtual environment
 source env/bin/activate
Run the python script
python3 app.py


