---
title       : Get Your MPG
subtitle    : Get the expected miles per gallon of your car
author      : Ralf
job         : Coursera Data Product
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---


## Introduction

Energy is one important factor in wealth.
Carbon related Energy also a an important environmental factor
Therefore is helps to understand how I can contribute to save energy

I have compiled a little app showing dependency of the miles a car can go with a gallon depending on some other features.

--- .class #id 
## This is the output of the App
![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 

--- .class #id 

## Some Data science background

The app uses a provided Data set called: MTCARS
Analysis revealed that the main factor for determining the mpg of a car are the weight and the acceleration.


Other factors like horsepower of such a strong correlation to those two that including them would distort the result. 

--- .class #id 

## How to use the app

You will find on the left hand two sliders allowing you to input the weight and cceleration of te car.

Below the slides you get based on this the expected miles per gallon. 

On the right hand side a graphic visualize the values you entered comparing to the test set MTCARS.
