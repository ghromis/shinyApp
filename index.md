---
title       : Shiny App
subtitle    : presentation
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## About the App

Shiny app contains information about the Dow Jones Industrial Average index. You
can use it to track returns and index composition.





```r
library(portfolio)
head(DJIA)
```

```
##      symbol                         name price      sector cap.bil
## 140      AA                    ALCOA INC 31.42   Materials   27.35
## 214      MO             ALTRIA GROUP INC 61.10     Staples  125.41
## 270     AXP          AMERICAN EXPRESS CO 56.37  Financials   70.75
## 294     AIG AMERICAN INTERNATIONAL GROUP 65.67  Financials  171.04
## 946      BA                    BOEING CO 51.77 Industrials   43.47
## 1119    CAT              CATERPILLAR INC 97.51 Industrials   33.27
##      month.ret
## 140  -0.060789
## 214   0.044681
## 270  -0.051488
## 294   0.009441
## 946  -0.022600
## 1119 -0.082199
```


--- .class #id 

## Plot

This page shows Dow Jones Industrial Average (DJIA) index returns for the chosen
period.

You can select log scale or nominal scale.

You can also select to see returns adjusted for the inflation.

--- .class #id 

## Summary

You can see more about the Down Jones Industrial averge index here.

--- .class #id 

## Table

You can see a table with the information about index components here. 
