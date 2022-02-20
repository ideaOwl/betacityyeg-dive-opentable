# Visualizing COVID Recovery through Reservations for In-person Dining using OpenTable Data

## Tutorial
[![Video Tutorial for creating the visualization](https://raw.githubusercontent.com/ideaOwl/betacityyeg-dive-opentable/main/images/tutorial-preview.png)](https://youtu.be/TuYLcuwOv9o)

## Potential Visualizations to Create and Explore
Keeping in mind that (restaurant) recovery here means how many reservations are placed for in-person dining as compared to before the pandemic:
- How do countries fare in terms of recovery?  How is Canada different from the U.S., or European countries?
- How do the provinces compare to one another?
- What's the difference between Edmonton and Calgary, given that they are both in Alberta?
- How do cities compare in Canada itself?
- Are the trends shown in this tutorial similar to other provinces?  You'll probably need to download hospitalization data from other open data portals.


## Data Files
Download all three CSV files:

1) [OpenTable data, unpivoted](https://github.com/ideaOwl/betacityyeg-dive-opentable/raw/main/data/unpivoted-opentable-seated-diner-data.csv)
2) [COVID-19 Alberta Statistics](https://github.com/ideaOwl/betacityyeg-dive-opentable/raw/main/data/covid-19-alberta-statistics-summary-data.csv)
3) [Timetable of Alberta Actions on COVID-19](https://github.com/ideaOwl/betacityyeg-dive-opentable/raw/main/data/covid-19-pandemic-response-alberta.csv)

> **Note:** Data was gathered at various dates, mainly in January/February 2022, from [1. OpenTable's State of the Industry dataset](https://www.opentable.com/state-of-industry), [2. Alberta Government's COVID-19 Statistics (summary data)](https://www.alberta.ca/stats/covid-19-alberta-statistics.htm#data-export), and excerpts from a [3. Wikipedia article on the timeline of the pandemic in Alberta](https://en.wikipedia.org/wiki/Timeline_of_the_COVID-19_pandemic_in_Alberta) I summarized.

## Background

Originally created for a [BetaCity Learn/Data-thon](https://www.meetup.com/startupedmonton/events/283522699/) to use OpenTable data to compare in-person dining reservations before and after the pandemic began.

The OpenTable data was unpivoted using a Jupyter notebook on Colab.  It was only a few lines of code, and is [available here](https://github.com/ideaOwl/betacityyeg-dive-opentable/blob/main/betacityyeg_dive_opentable.ipynb) on this repository.