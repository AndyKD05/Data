# TidyTuesday

TidyTuesday project is a weekly appointment that happens on every Tuesday for practicing making #DataVisualization with datasets provided by the #`R4DS Online Learning Community`

Several TidyTuesday interesting examples can be found in the main repository:

- https://github.com/rfordatascience/tidytuesday

***
#### How to make a #TidyTuesday (more info at the bottom of this page) 

***

# My contributions DataSets
## [2021](data/2021) | [2022](data/2022)

| Week | Date | Data | Source | Article
| :---: | :---: | :--- | :--- | :---|
| 1 | `2021-01-04` | Bring your own data to start 2022! | | |

***
## My contributions are posted on: 

#### Twitter @[fgazzelloni](https://twitter.com/fgazzelloni) and collected in this repository with related code.

## Other #DataViz projects contributions:

### - [30DayChartChallenge-2021](https://github.com/Fgazzelloni/rstats-chart-challenge-2021)
### - [30DayMapChallenge-2021](https://github.com/Fgazzelloni/30DayMapChallenge)


***
## INFO: How to make a #TidyTuesday

- Go to [R4DataScience GitHub repository](https://github.com/rfordatascience/tidytuesday)
- import data found in the [README](https://github.com/rfordatascience/tidytuesday/blob/master/README.md) at the middle bottom of the page is a table with the most updated data provided for the year/week
- click on the corresponding data tab in the table 
- load the data, two options are available: 

    1. Install {tidytuesdayR} package from CRAN via: `install.packages("tidytuesdayR")`, then load the data as suggested assigning a tuesdata variable name using the `tt_load()` function:
    
        `tuesdata <- tidytuesdayR::tt_load("date")`
        
        `tuesdata <- tidytuesdayR::tt_load(year, week)`
    
    2. Import the data directly from the .csv file provided 
