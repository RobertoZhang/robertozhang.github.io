---
title       : Area Converter Guide
subtitle    : An Assignment to Data Product 
author      : Tianyuan Zhang
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

--- .class1

## Motivation

- United States uses US Customary Unit, which is different from the rest of the world.
- International real estate investor finds it difficult to visualize the side of property.
- This gives reason to develop a web-based converter for the investors.

--- .class1


## From US Customary Unit to Metrics
- The system for measuring length in the United States customary system is based on the inch, foot, yard, and mile, which are the only four customary length measurements in everyday use. Since July 1, 1959, these have been defined on the basis of 1 yard = 0.9144 meters except for some applications in surveying
- 1 mile=5280 ft, 1 yard=3ft...

--- .class1

## From Square foot to Square Meter
- 1 foot = 0.3048 meter
- 1 square foot = 0.092903 Square meter
- Therefore, area( in square foot) * 0.092903= area(in square meter)

--- .class1

## Mechanism


```r
AreaFt<-100000
AreaMeter<-(AreaFt*0.092903)
AreaMeter
```

```
## [1] 9290.3
```

--- .class1

## Instruction
- Access the converter through the link
https://ztyrobert.shinyapps.io/Area_Converter/ 
- Input the area in text box, and adjust the amount with the trangles.
- Click the "Submit", and observe the result on the right side of the page. 

