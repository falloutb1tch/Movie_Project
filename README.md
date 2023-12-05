# ![MBresize](https://github.com/falloutb1tch/Movie_Project/assets/149413838/ca3cbd87-7899-49fe-a7e0-6523b686c0f7)

# You come to me, on the day of my daughter's wedding, and ask me for a movie presentation?
## Overview

Our team, consisting of Whitlee, Yiyi and Jacob, was asked to present three business recommendations as our company establishes its very own movie studio.

## Business Understanding

As fun as it sounds to make movies, Tom Cruise (and others) have taught us that the business of making movies can be a... wait for it... Risky Business. Anyway, our company had no real knowledge of what makes a good movie or how to make a movie profitable, so our team was tasked with exploring data and running tests upon that data in order to provide that information and inform our business recommendations.

## Data Understanding

We were provided five (5) data files, from various sources, and our first task was to decide which of those data files were viable for our purposes and which were, for lack of a better word, useless. Of those five (5) available choices, "bom.movie_gross.csv.gz" contained financial information and only that, so we discarded it as we could find that information elsewhere. Additionally, "rt.movie_info.tsv.gz" and "rt.reviews.tsv.gz" were synopses and reviews respectively, and full of strings that would be quite difficult to quantify and proved unnecessary.

Therefore, we settled on using "im.db", a SQL database for IMDB. IMDB (or, the International Movie Database) is a very popular movie-ranking website. The IMDB dataset contained such fare as ratings, directors, and actors. This data spanned from 2010 to 2027 as it dealt with production budgets and movies still being made and scheduled.

Additionally, we chose to use "tmdb.movies.csv.gz". This data came from "The Movie Database", and spanned the years 2013 to 2018. We chose this dataset because it contained a rating system, as well as title information.

Finally, as our third data source, we chose "tn.movie_budgets.csv.gz". This data came from The Numbers, and features such information as budget (what a movie cost to make), domestic gross and worldwide gross. These figures are very important for mathematical calculations, and answering the question of how much a movie is worth in a quantifiable amount. Finally, in terms of our basic data understanding, we must load in the IMDB SQL Database and attempt to discover roughly the same information, though the schema is very different and so therefore is the information contained within.

## Data Preparation
## Analysis and Recommendations
## Conlusion and Next Steps
## Repo Structure
