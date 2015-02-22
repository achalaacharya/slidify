---
title       : Expenditure by year App
subtitle    : Visualizing Expenditure by Year
author      : Achala Acharya
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction 
Have you ever wondered how much the US population spends on different categories such as food, health and education?

Now you have an app that tells you how much was spent on Food and Tobacco, Household Operation, Medical and Health, Personal Care and Private Education Categories in a bar plot.


---
The data used for this app comes from the Datasets package in R. It is the USPersonal Expenditure dataset.

The app lets you select the year and visualize the amount of dollars spend on Food and Tobacco, Household Operation, Medical and Health, Personal Care and Private Education Categories in a bar plot.

This app makes it easier to compare how the expenditure across those categories compares for a given year.

--- 

Here is a summary of the dataset.

      1940             1945             1950            1955      
 Min.   : 0.341   Min.   : 0.974   Min.   : 1.80   Min.   : 2.60  
 1st Qu.: 1.040   1st Qu.: 1.980   1st Qu.: 2.45   1st Qu.: 3.40  
 Median : 3.530   Median : 5.760   Median : 9.71   Median :14.00  
 Mean   : 7.522   Mean   :13.743   Mean   :20.51   Mean   :25.94  
 3rd Qu.:10.500   3rd Qu.:15.500   3rd Qu.:29.00   3rd Qu.:36.50  
 Max.   :22.200   Max.   :44.500   Max.   :59.60   Max.   :73.20  
      1960      
 Min.   : 3.64  
 1st Qu.: 5.40  
 Median :21.10  
 Mean   :32.63  
 3rd Qu.:46.20  
 Max.   :86.80  

---.
So please try out the app and check back later for an update that includes years past 1960.











