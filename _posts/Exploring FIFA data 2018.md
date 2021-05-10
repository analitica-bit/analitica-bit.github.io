---
layout: post
title: "Exploring FIFA dataset using the ggplot2 package."
subtitle: "Basic phenotypic requirements needed to be a footballer. Do you think you have them?"
background: '/img/posts/03.jpg'
---

## Football
Football is one of the most lucrative sports. According to [SPORTYTELL](https://sportytell.com/sports/highest-paid-sports-world/), footballers are 8th highest paid sport professionals.

This data analysis takes a subjective stance of the game and also the choice of analytical tools used. It showcases the ways of exploring data using R. it an old project of mine as it shows our wrote my codes as far back as June 6, 2020.

![meme of my code 6 months ago]()

## EDA Process

### Data Description
I think the data is a 2018 data as it has Messi with the highest rating :). it can be found on my Github repository (put link here). Although, I do not lay claim on its authorship as I downloaded it online from a site I can't remember now.



### Installing packages
```
install.package("tidyverse")
library(tidyverse)
```
### Importing data
```
fifa <- read.csv("fifa.csv", header = TRUE)>
```