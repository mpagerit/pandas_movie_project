# Team-11-project-1
# Show Me the Money! Movie analysis project

**Team Members:**
* Jason O'Day
* John Clark
* Marianne Pagerit
* Nicole Fejfar

## Description
Using the Open Movie Database, analyze the top box office and academy award winning movies over the last 20 years, (2000-2019) to determine the impact of release date and genre on a movie’s commercial and critical success.

This project was originally performed with a group. You can see the original repo here: https://github.com/mpagerit/Team-11-project-1

## Hypothesis
1. Summer movies (May through July) tend to make more money than movies released at other times of the year. 
1. However, most Oscar winners tend to be released during "Oscar Season" (November and December)

1. Bonus, time and data allowing: The Action movie genre tends to make the most money, while Drama tends to win more awards.


## Null Hypotheses
1. Movies released during summer blockbuster season make the same amount of money as movies released the rest of the year (the time of year makes no difference in money made).
1. Movies released during Oscar season win the same number of awards as other movies (time of year makes no difference.)
1. Genre has no impact on money made or awards won.

## Questions to Answer
1. Does the date released affect the amount of money a movie makes?
    1. Is there a relationship between money made and viewer ratings?
    1. Is there a relationship between money made and critical rating?
1. Do Oscar winners tend to be released in the same timeframe as the box office winners?
    1. Does box office success equate to more awards success? 
    1. Do viewer ratings correlate with oscar wins? 
    1. Do critic ratings correlate with oscar wins?
1. Bonus: What impact does genre have on box office or awards?

## Analysis:
Please see the [Analysis file](Analysis.ipynb) for full analysis writeup.

## Visualisations:
![top 40 by genre](/images/top_40_by_genre.png)

![avg box office](/images/avg_box_office.png)

![% box office](/images/%_box_office_season.png)

![oscars by time year](/images/oscars_time_year.png)

![%oscars_by_time](/images/%_oscars_time.png)

![oscars_pie_%](/images/oscars_pie.png)

![awards vs rating](/images/awards_vs_rating.png)

![metascore_vs_oscars](/images/metascore_vs_oscars.png)

![oscars by genre](/images/oscars_genre.png)

![box_office_genre](/images/avg_box_office_genre.png)

![avg_box_office_genre](/images/box_office_genre.png)

## DataSets
* [OMDB API](http://www.omdbapi.com/)
* [The Numbers](https://www.the-numbers.com/data-services)

## Task Breakdown
* Pulling Data from “The Numbers” to compile top grossing movies per year
* Pull Data from the API
* Merge & Clean CSVs
    * Create working dataframe with found movies - use to create analysis code
    * Create dataframe of missing/incorrect movies
        * Clean up data
        * Remove movies that can't be found
        * Double-check numbers
    * Fix Movie names, re-run API
    * Merge updated moves back into dataframe
* Analyze Data
    * Hypothesis testing
    * Plot data
* Written Analysis
* Prepare Presentation

## Time of Year Definitions
* [Winter and Summer Dump Months](https://en.wikipedia.org/wiki/Dump_months)
* [Oscar Season](https://en.wikipedia.org/wiki/Oscar_season#:~:text=Oscar%20season%20usually%20begins%20in,and%20dependent%20on%20the%20year)
* [Summer Blockbuster Season](https://datebook.sfchronicle.com/movies-tv/summer-movies-2020-the-season-of-the-blockbuster-is-now-the-season-of-uncertainty#:~:text=For%20the%20last%20two%20years,tracks%20box%20office%20revenue%20worldwide)
