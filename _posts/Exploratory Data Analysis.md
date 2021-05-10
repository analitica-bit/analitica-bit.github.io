---
layout: post
title: "Exploratory Data Analysis in R"
subtitle: "Exploratory data analysis, or	EDA, is the first step in any data science	project."
background: '/img/posts/03.jpg'
---

## Exploratory data analysis, or EDA
In 1962, John W. Tukey (Figure 1-1) called
for a reformation of statistics in his seminal paper “The Future of Data Analysis”. 
He proposed a new scientific discipline called data analysis that
included statistical inference as just one component. 

The field of exploratory data analysis
was established with Tukey’s 1977 now-classic book Exploratory Data Analysis.


### What is data?
Data is preprocessed information. Data	comes from many	sources: sensor	measurements events, text, images, and videos.
Majority of data these days are unstructured.
Unstructured data: images are a collection of pixels with each pixel
containing RGB (red, green, blue) color information. Texts are sequences of
words and nonword characters, often organized by sections, subsections, and so
on. Clickstreams are sequences of actions by a user interacting with an app or
web page. Harnessing raw data of these quantity into actionable insights is one of the major challenges of data science. Unstructured raw data has to be processed and manipulated to structured form.

##### Terms for data types
Binary - A special case of categorical data with just two categories of values (0/1, true/false).

Categorical - Data that can take on only a specific set of values representing a set of possible categories.

Continous - Data that can take on any value in an interval.

Discrete - Data that can take on only integer values, such as counts.

Ordinal - Categorical data that has an explicit ordering.

Structured data can be in two forms: categorical or numerical.
Numeric data can be discrete or continuous.
Categorical data takes a fixed set of values. 

Note: data types taxonomy may vary from one software to another.

#### Rectangular Data
Rectangular data  is essentially a two-dimensional matrix with rows indicating
records (cases) and columns indicating features (variables). Most times, data doesn't start in this form. But, unstructured data is processed and manipulated to this form.
In R, the basic rectangular data structure is a data.frame object.
data.table and dplyr are two important packages for multilevel indexes and data.frame object manipulation.


### Reference
Practical Statistics for Data Scientists by Peter Bruce and Andrew Bruce

Photographs by <a href="https://unsplash.com/">Unsplash</a>.</p>
