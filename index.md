---
title       : Body Mass Index 
subtitle    : Complete BMI reference accross the world
author      : Sarvesh S G
job         : Student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

Know your Body Mass Index
===

The body mass index (BMI), or Quetelet index, is a measure of relative weight based on an individual's mass and height.

The BMI is used in a wide variety of contexts as a simple method to assess 
how much an individual's body weight departs from what is normal or desirable for a person of his or her height. 

The source is the [wikipedia](http://en.wikipedia.org/wiki/Body_mass_index) entry for BMI
Sample BMI calculation:

```r
weight <- 74
heightInMeter <- 1.7
bmi <- weight/heightInMeter^2
bmi
```

```
## [1] 25.61
```



---
Methods of Calculation & Inference:
===
There is a standard method for calculating BMI in kg/m2.

WHO standard inferences are used to predict/calculate 

except for countries which have their own BMI ranges

---
Age Factor:
===

For children (classified as someone below 20 yrs),

BMI is calculated w.r.t standard deviation of a sample population.

 Overweight: greater than 1 Standard Deviation
 Obesity: greater than 2 Standard Deviation
 Thinness: less than -1 Standard Deviation
 Severe thinness: less than -2 Standard Deviation
 
Health Risk:
====

```r
print("Singapore")
```

```
## [1] "Singapore"
```

The city gives its citizen a health risk profile.

It follows WHO standard BMI ranges.
This health risk are also part of the application.

---
Target Audience
===
This app lets users from all over the world check their BMI
and indicate to them about their health status

It is comprehensive to report BMI form 2 years of age.
