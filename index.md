---
title       : Slidify Presentation
subtitle    : Coursera's Developing Data Products
author      : Fturrado
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## Slide 1: Welcome

In the next slides we will show some features of the slidify R package.

For all the examples we will use the iris dataset.

The main goal of this app is to classify new instances of data using a Random Forest Classifier trained over the original dataset.



--- .class #id 

## Slide 2: Data

The iris dataset contains 150 obervations of 5 features: Sepal.Width, Sepal.Length, Petal.Width, Petal.Length and Species. 


```
##   Sepal.Length   Sepal.Width    Petal.Length   Petal.Width 
##  Min.   :4.30   Min.   :2.00   Min.   :1.00   Min.   :0.1  
##  1st Qu.:5.10   1st Qu.:2.80   1st Qu.:1.60   1st Qu.:0.3  
##  Median :5.80   Median :3.00   Median :4.35   Median :1.3  
##  Mean   :5.84   Mean   :3.06   Mean   :3.76   Mean   :1.2  
##  3rd Qu.:6.40   3rd Qu.:3.30   3rd Qu.:5.10   3rd Qu.:1.8  
##  Max.   :7.90   Max.   :4.40   Max.   :6.90   Max.   :2.5  
##        Species  
##  setosa    :50  
##  versicolor:50  
##  virginica :50  
##                 
##                 
## 
```

--- {tpl: twocol}

## Slide 3: Feature Overview

In this slide you will find an overview of the numeric features.

*** {name: left}

- Sepal.Width
- Sepal.Length
- Petal.Width
- Petal.Length

*** {name: right}

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2.png) 

--- 

## Slide 4 : Thanks

Please enjoy the app at the shinyapp's site:

https://fturrado.shinyapps.io/dataprod/




