---
title       : Application for Calculating Relationships of Transmission and MPG
subtitle    : 
author      : T.H.
job         : 
framework   : html5slides   # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

# Application for Calculating Relationships of Transmission and MPG

Date: 2014/12/21

--- .class #id 

## The purpose of this application

Many peaple are interested in
exploring the relationship between a set of variables and miles per
gallon (MPG).
They are particularly interested in the following two questions:
* "Is an automatic or manual transmission better for MPG"
* "Quantify the MPG difference between automatic and manual transmissions"

This application can calculate coefficients of multiple model
fittings.

--- .class #id 

## The characteristics of this application

You can select variables as predectors for mph interactively.

--- .class #id 
## Screen Shot

![Screen Shot](ScreenShot.png)

--- .class #id 
## Examples



* If you choose only am a predector, you can get a result below.


```
##             Estimate Std. Error t value  Pr(>|t|)
## (Intercept)   17.147      1.125  15.247 1.134e-15
## am:manual      7.245      1.764   4.106 2.850e-04
```

* If you choose am and cyl as predectors, you can get a result below.


```
##             Estimate Std. Error t value  Pr(>|t|)
## (Intercept)   34.522     2.6032  13.262 7.694e-14
## am:manual      2.567     1.2914   1.988 5.635e-02
## cyl           -2.501     0.3608  -6.931 1.285e-07
```
