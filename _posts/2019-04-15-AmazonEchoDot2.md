---
title: "Natural Language Processing: Amazon Echo Dot 2 Reviews"
date: 2019-04-15
tags: [machine learning,data science,neural network]
header:
  image:"/assets/images/amazonechodot2.jpg"
excerpt: "Machine Learning, Natural Language Processing, Data Science"
---

# Amazon Echo Dot 2 Reviews Analysis & Text Processing


Data Source: Please drop a note to hrushikesh.mahapatro.97@gmail.com for More Info. <br>

The Amazon Reviews dataset consists of reviews of fine foods from Amazon.<br>

Number of reviews: 53048<br>
Number of Attributes/Columns in data: 12 

*Attribute Information:*

1. Uniq Id: Unique Id of the review.
2. Crawl Timestamp - Web Crawl Time: Time of collection of data.
3. Pageurl - URL of the webpage.
4. Title - Title of the review.
5. Review Text - The actual Review. (Text value)
6. Review Color - Product Color : Black/White 
7. User Verified - Whether the user is a verified buyer or not.
8. Review Date - Date of the review given.
9. Review Useful Count - Number of people found to be useful.
10. Configuration Text - Product Configuration Echo Dot or Echo Dot + Sony XB10 Speaker or Echo Dot + Philips Hue Smart Lighting Kit or Echo Dot + Vaux Speaker
11. Rating - Number of starts out of 5
12. Declaration Text -  Reviewer Declation/Specility Such as (VINE VOICE, TOP 500 REVIEWER, TOP 1000 REVIEWER, HALL OF FAME, TOP 50 REVIEWER, #1 HALL OF FAME)


#### Objective:
Given a review, determine whether the review is positive (Rating of 4 or 5) or negative (rating of 1 or 2).<br>
**[Q]** How to determine if a review is positive or negative<br>
**[Approach:]** We could use the Score/Rating. A rating of 4 or 5 could be cosnidered a positive review. A review of 1 or 2 could be considered negative. A review of 3 is nuetral and ignored. This is an approximate and proxy way of determining the polarity (positivity/negativity) of a review.

## Loading the data

The dataset is available as a CSV file
1. Train_Test.csv file

Here as we only want to get the global sentiment of the recommendations (positive or negative), we will purposefully ignore all Scores equal to 3. If the score id above 3, then the recommendation wil be set to "positive". Otherwise, it will be set to "negative".











# H1 Heading
## H2 Heading
### H3 Heading

Some basic text

*Some italic text*

Some **BOLD** text

Visit to google search engine [link](https://www.google.co.in)

Here is a list

* E1
+ e2
- e3

Numbered List
1. First
2. Second
3. Third

Python code block
```python
for i in number:
    i++;
```
R code block:
```r
library(tidyverse)
df<-read_csv("file.csv")
head(df)
```

Some inline code `x+y`

An image:
<img src="{{site.url}}{{site.baseurl}}/assets/images/logo.jpg" alt="Image is broken">


some math
$$z=x+y$$
