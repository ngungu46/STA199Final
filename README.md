# Analyzing the relationship between student alcohol consumption and school performance

[Project](https://sta199-fa20-002.netlify.app/project/) for STA 199 - Fall 2020

*Daniel Bolja, Elyse McFalls, Nathan Nguyen, Damla Ozdemir*

Conventionally, student alcoholism is linked to academic performance deficiencies. Students with higher alcohol consumption may experience lower performance in many aspects, such as lower grades, lower study times, higher absences, and failing more classes. We investigated this relationship between alcohol consumption and study performance based on a dataset collected in two public Portugal secondary schools during the 2005-2006 school year. We considered the correlations between workday and weekend alcohol consumption with school-related attributes that were expected to affect study performance, which are **grades**, **weekly study time**, **number of absences**, and **number of failed classes**. We also used linear models to predict these attributes from alcohol consumption as predictors, and chi-square tests to analyze the existence of relationships between those variables. Our analyses revealed a significant relationship between alcohol consumption and study performance attributes. Our results indicated that there negative correlations between alcohol consumption and **grades**, **weekly study time**, and there are positive relationships between alcohol consumption and **absences**, **number of failed classes**. We concluded from the results that alcohol consumption significantly predicts study performance in negative ways, regardless of some conditions.
Our main focus will be on these variables:

Variables | Type |Meaning
---- | ---| -----------------------------
`reason` | character|reason to choose this school (close to 'home', school 'reputation', 'course' preference 
`studytime` | integer|weekly study time (1: < 2 hours, 2: 2 to 5 hours, 3: 5 to 10 hours or 4: > 10 hours hours)
`failures` | integer|number of past class failures (n if 0 <= n < 3, else 4)
`Dalc` | integer|workday alcohol consumption (from 1 to 5)
`Walc` | integer|weekend alcohol consumption (from 1 to 5)
`absences` | integer|number of school absences (from 0 to 93)
`G1` | integer|first period grade (from 1 to 20)
`G2` | integer|second period grade (from 1 to 20)
`G3` | integer|final grade (from 1 to 20)

## Reference

1. P. Cortez and A. Silva. Using data mining to pre-dict secondary school student performance. 2008.

2. Student Alcohol Consumption dataset: https://www.kaggle.com/uciml/student-alcohol-consumption.
