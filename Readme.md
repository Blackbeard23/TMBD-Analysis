# The Movie Database Analysis
## Introduction
The film industry as of 2019 was worth over 100 billion dollars. It's first time ever. With Box office making $48.2 billion globally and home/mobile entertainment making $52.8 billion.

The growth in the industry's worth is due to the rapid rise of streaming platforms such as Netflix, HBO Max, Hulu and Amazon Prime. Which allowed people to watch contents anywhere over cost, and led to an increase in consumer spending, heace a growth in revenue.

The growth in revenue encouraged film production houses to invest in high quality contents and would result in movies being a hit once released.

## Dataset
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings, popularity, budget, vote count, vote average, cast, genres, director and revenue.

## Objectives
The data analysis was be use to answer these questions;

    Which Year has the highest number of released movies
    Directors with the highest Revenue
    Genres with the overall average Revenue
    Top 5 Highest movie revenue
    Top 10 Actors with most apperance in Movies
    What kinds of properties are associated with movies that have high revenues
    How many movies are considered successful compare to unsuccessful movies

## Summary of Findings
1. From the research question posed and the analysis carried out, we could see that the year 2011 has the highest number of the movie released followed by 2013 and 2010
2. Top 5 directors with the highest average revenue of all time are
- Jennifer Lee
- Irwin Winkler
- David Yates
- Joss Whedon
- Pierre Coffin
- Mike Thurmeier
- Raman Hui
- Colin Trevorrow
- Robert Stromberg
3. Genres with overall average revenue were animation, adventure, fantasy etc.
4. Top 5 highest movie revenue were 102 Dalmatians, 101 Dalmatians, 10,000 BC, 10 things i hate about you and (500) days of summer.
5. Top 5 Actors with the most appearance were Robert De Niro, Bruce Willis, Samuel L. Jackson, Nicolas Cage and Matt Damon
6. After selecting the data frame of revenue that is considered high(75% Quantile), the test of correlation (a statistical of the relationship between two variables) between revenue as the dependent variable and other columns as independent were all found to be moderate to strong correlation, so therefore as the independent variable increases the dependent variable (revenue) increases. This tells us those columns are characteristic of movies with high revenue.
5. They were more unsuccessful movie (52.9%) compare to successful movies (47.1%).

## Limitation
The limitation of the analysis report is that they were many zero values in the Budget and Revenue which were 4751 and 5022 respectively, although the runtime column contained just about 13 zero values. Dropping the zero value in either of the three columns drastically reduced the number of rows from 9,772 to 3,805 which is about 62% of the number of the dataset dropped. This might have caused a huge change in the result of the analysis and findings.
