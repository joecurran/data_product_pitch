---
title       : MPG estimator
subtitle    : 
author      : Joe Curran
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Problem Description  

#### You are interested in buying a used car and will try a few used car dealers.  Recently, gas prices are rising so the miles per gallon (mpg) metric is important to you. Unfortunately, the used car dealers have no information about the used car's mpg.  Used car lots typically have a garage where they fix car's prior to selling them.  The mechanic can measure the wieght of cars.  


#  what can you do?

---
## Enter MPG Estimator!

This application allows you to get a rough estimate of a car's mpg.  Simply ask the mechanic to weight the car you are intrested in. 


--- 
## How it works

MotorTrends has published reliable data on a series of cars.  
We use a simple linear model, represented by red line, to  
estimate mpg from weight.

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 

The vertical black line is the input for weight=2.7.

---

#### Please try it out at https://jcurran.shinyapps.io/shinyapp_centering

## Thank You!

