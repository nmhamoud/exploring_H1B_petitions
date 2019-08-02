---
title: "README"
author: "Nabeel Hamoud"
output: 
  html_document: 
    keep_md: yes
---



## About the project

The H-1B is a visa in the United States under the Immigration and Nationality Act, section 101(a)(15)(H) which allows U.S. employers to employ foreign workers in specialty occupations (source: [Wikipedia]( https://en.wikipedia.org/wiki/H-1B_visa>)). In this project, data from the US Department of Labor is cleaned and explored. The data consists of 11 variables and over 3M observations over 6 years (i.e. 2011-2016). The approaches used include descriptive analysis, data visualization and word clouds.

## Files needed

1- The dataset is named "h1b_kaggle.csv", and can be found at [Kaggle](https://www.kaggle.com/nsharan/h-1b-visa). 

2- After separating the WORKSITE variable, we replaced the state names with their abbreviations. The file used for this process is named **"states.csv"**.

3- To filter the occupations that belong to the STEM majors, I created a file with those occupations with their indices/code. The file is named **"SOC.csv"**


## Libraries used

library("tidyr")

library("dplyr")

library("data.table")

library("ggplot2")

library("stringr")

library("knitr")

library("kableExtra")

library("stringdist")

library("readr")

library("tm")

library("SnowballC")

library("wordcloud")

library("RColorBrewer")


## Contact
Nabeel Hamoud: [LinkedIn](https://www.linkedin.com/in/nmhamoud/)
