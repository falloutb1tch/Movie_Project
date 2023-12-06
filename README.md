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

Our team moved through the three aforementioned data sources, standardizing and cleaning up the data as needed. Both Pandas and SQL was employed for this.

## Analysis and Recommendations
#Recommendation 1
[IMDb_Ratings_M_1.pdf](https://github.com/falloutb1tch/Movie_Project/Images/IMDb_Ratings_M_1.pdf)

Our data shows a clear preference in audience opinion for action, adventure, and science-fiction films. The next few popular genres are drama, romance, comedy and fantasy, but even those are mixed with yet more and adventure. Furthermore, our data shows that it is not even a close comparison between "first place" and any following.

#Recommendation 2
[IMDb_Budgets_M_1.pdf](https://github.com/falloutb1tch/Movie_Project/files/13590499/IMDb_Budgets_M_1.pdf)

We were not given a budget for our movie enterprise, so we have established a range of genres that would be acceptable for budgetary reasons. Action, adventure and science-fiction once again reign supreme in terms of revenue, but they are also the most expensive to make. Depending on our available resources, this may not be the best option. Fantasy, comedy and animation are all acceptable choices for what could be considered a "medium" available budget, and animation has the further benefit of potentially employing larger-status actors or actresses without as much cost, since it is voice work. 

#Recommendation 3[A_List_Actors.pdf](https://github.com/falloutb1tch/Movie_Project/files/13590515/A_List_Actors.pdf)

Our research shows that there is a clear preference for certain actors or actresses involved in a project. Further statistical testing proved this to be the case (pending) and it is clear that Robert Downey Jr. would be a preferred actor for our first movie venture. As before, it may be possible to opt for voice work for budgetary purposes.

## Conlusion and Next Steps
## Repo Structure
