---
layout: post
title: "Support Vector Machine for Programmers part 2"
date: 2013-08-15 18:43
comments: true
categories: data svm4p
---
# SVM for Programmers, part 2

Let's start with a concrete example to taste a flavor of how SVM works.

body.data ([source site][1]) is the input file containing the statistical heights and weights of females and males. Here is the raw data:

{% include_code lang:yaml body.data %}

Then we can easily load the data to R and use libsvm to classify genders by heights and weights.

{% include_code lang:r svm4p2.r %}

Line 4 renders the picture of the data.

![body.data]({{root_url}}/downloads/code/body.data.png)

Line 8 renders the picture of how the svm classifying the data.

![body.svm]({{root_url}}/downloads/code/body.svm.png)

With the trained model m1, we can guess if a new person if male or female by his/her height and weight:

``` r
predict(m1, data.frame(Height=71, Average=155))
predict(m1, data.frame(Height=67, Average=175))
```

Results:

- Height 71in (180cm), Weight 155lbs (70kg) => -1 Female
- Height 67in (170cm), Weight 175lbs (79kg) => +1 Male

[1]: http://www.healthyyounaturally.com/nutrition/age_height_weight_chart.htm 
