# DSS5-ReproducibleResearch-Week4
Population Health Impact and Economic Consequences of Storms

## Introduction

Storms and other severe weather events can cause both public health and economic problems for communities and municipalities. Many severe events can result in fatalities, injuries, and property damage, and preventing such outcomes to the extent possible is a key concern.

This project involves exploring the U.S. National Oceanic and Atmospheric Administration's (NOAA) storm database. This database tracks characteristics of major storms and weather events in the United States, including when and where they occur, as well as estimates of any fatalities, injuries, and property damage.

## Data

The data for this assignment come in the form of a comma-separated-value file compressed via the bzip2 algorithm to reduce its size. I downloaded the file from the course web site:

[Storm Data 47Mb](https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2FStormData.csv.bz2)

There is also some documentation of the database available. Here I found how some of the variables are constructed/defined.

[National Weather Service Storm Data Documentation](https://d396qusza40orc.cloudfront.net/repdata%2Fpeer2_doc%2Fpd01016005curr.pdf)
[National Climatic Data Center Storm Events FAQ](https://d396qusza40orc.cloudfront.net/repdata%2Fpeer2_doc%2FNCDC%20Storm%20Events-FAQ%20Page.pdf)

The events in the database start in the year 1950 and end in November 2011. In the earlier years of the database there are generally fewer events recorded, most likely due to a lack of good records. More recent years should be considered more complete.

## Assignment

The basic goal of this assignment is to explore the NOAA Storm Database and answer some basic questions about severe weather events. I used the database to answer the questions below and showed the code for my entire analysis. My analysis consists of tables, figures, or other summaries.

### Questions

My data analysis addresses the following questions:

Across the United States, which types of events (as indicated in the EVTYPE variable) are most harmful with respect to population health?

Across the United States, which types of events have the greatest economic consequences?

## Requirements

For this assignment I used some specific tools:

* RStudio: I used RStudio to publish my completed analysis document to RPubs, and also to edit/write your analysis.
* knitr: I used the knitr package in order to compile my R Markdown document and convert it to HTML.

### Document Layout

* Language: My document is written in English.
* Title: My document has a title that briefly summarizes your data analysis.
* Synopsis: Immediately after the title, there is a synopsis which describes and summarizes my analysis in less than 10 complete sentences.
* There is a section titled Data Processing which describes (in words and code) how the data were loaded into R and processed for analysis. In particular, my analysis started from the raw CSV file containing the data. I didn't do any preprocessing outside the document. Some preprocessing was time-consuming so I used the cache = TRUE option for certain code chunks.
* There is be a section titled Results in which my results are presented.
* The analysis document contains 3 figures, with multiple plots in some of the figures.
* I show all my code for the work in my analysis document. This may make the document a bit verbose, but that is okay.

### Publishing Your Analysis
For this assignment I published my analysis on RPubs.com to [http://rpubs.com/bkkesseler/stormevents](http://rpubs.com/bkkesseler/stormevents)