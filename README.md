# ggplot() Workshop

ggplot2() workshop
CAS Studio April 2021
Britta Schumacher

RPubs (published knitted html) can be found [here](https://rpubs.com/blschum/CAS-ggplot-workshop).

## Getting started
If you are participating in the workshop, you may either (a) work on the [ggplot-workshop-TEMPLATE.Rmd](https://github.com/blschum/CAS-ggplot-workshop/blob/main/ggplot-workshop-TEMPLATE.Rmd), which leaves space for participants to type code with instruction, or (b) follow along along in the [ggplot-workshop-KEY.Rmd](https://github.com/blschum/CAS-ggplot-workshop/blob/main/ggplot-workshop-KEY.Rmd), which has all of the information and code we will be working with. Download the [ggplot-workshop-KEY.html](https://github.com/blschum/CAS-ggplot-workshop/blob/main/ggplot-workshop-KEY.html) for a knitted (and much easier to read) version of the KEY.

Outline
1. Reminder: How do we use the tidyverse?
2. Useful functions to know for data wrangling, subsetting, manipulating, and summarising data
3. What is ggplot?
4. Plotting data + bonus intro to sf()

## Data source
All [dragon data](http://search.r-project.org/R/R/library/DALEX/html/dragons.html) is from the DALEX package. We will also be using EPA air quality data, wrangled by Ellie Smith-Eskridge and Dakoeta Pinto.

## Species of interest
We'll be wrangling and plotting data for a subset of chromatic dragons:

|     Common name     |      Scientific name      |
|---------------------|---------------------------|
|     Common black     |     *Jaggermeryx ozzyi*    |
|     Scaley longtail    |    *Jaggermeryx whido*    |
|     Sharptoothed flier    |     *Jaggermeryx strummeri*    |
|     Fiery blue     |    *Sauroniops naida* |
|     Four-toed scale-back   |     *Sauroniops reike*    |
