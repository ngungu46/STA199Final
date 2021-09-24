# Data

During the 2005-2006 school year, Cortez and Silva collected the data from secondary students enrolled in Portuguese class from two public schools (Gabriel Pereira and Mousinho da Silveira) in Alenjeto, Portugal. 

The goal of the study is to use the data mining technique to analyze students' studying performance versus their alcohol consumption. The data contains *649 observations* representing students from these two schools. Each observation contains attributes from grades and number of absences, demographic, social/emotional, and school-related variables. The authors collected data from paper-based school reports (for grades, absences) and questionnaires about personal information. See [1] and [2] for more details about the study and the dataset. Data with a lack of identification was discarded. The data was taken from Kaggle database.

The details of variables are shown below, with four last attributes taken from school reports. Data has 649 observations and 33 variables. 

Variables | Type |Meaning
---- | ---| -----------------------------
`school` | character| student's school ('GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
`sex` | character| student's sex ('F' - female or 'M' - male)
`age` | integer| student's age (from 15 to 22)
`address` | character|student's home address type ('U' - urban or 'R' - rural)
`famsize` | character|family size ('LE3' - less or equal to 3 or 'GT3' - greater than 3)
`Pstatus` |character| parent's cohabitation status ('T' - living together or 'A' - apart)
`Medu` | integer|mother's education (0 to 4)
`Fedu` |integer| father's education (0 to 4)
`Mjob` | character|mother's job ('teacher', 'health' care related, civil 'services' , 'at_home' or 'other')
`Fjob` | character|father's job ('teacher', 'health' care related, civil 'services' , 'at_home' or 'other')
`reason` | character|reason to choose this school (close to 'home', school 'reputation', 'course' preference or 'other')
`guardian` | character|student's guardian ('mother', 'father' or 'other')
`traveltime` | integer|home to school travel time (1 - 10 hours)
`studytime` | integer|weekly study time (1: < 2 hours, 2: 2 to 5 hours, 3: 5 to 10 hours or 4: > 10 hours hours)
`failures` | integer|number of past class failures (n if 0 <= n < 3, else 4)
`schoolsup` | character|extra educational support 
`famsup` | character|family educational support 
`paid` |character| extra paid classes within the course subject
`activities` | character|extra-curricular activities 
`nursery` | character|attended nursery school
`higher` | character|wants to take higher education
`internet` | character|Internet access at home
`romantic` | character|with a romantic relationship
`famrel` | integer|quality of family relationships 
`freetime` | integer|free time after school
`goout` | integer|going out with friends
`Dalc` | integer|workday alcohol consumption
`Walc` | integer|weekend alcohol consumption 
`health` | integer|current health status
`absences` | integer|number of school absences (from 0 to 93)
`G1` | integer|first period grade
`G2` | integer|second period grade
`G3` | integer|final grade

**Note**: Mother and father education (`Medu` and `Fedu`) were valued from 0 to 4 with: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education. For `famrel`, `freetime`, `goout`, `Dalc`, `Walc` and `health` variables, the values were taken from 1 (very low/bad) to 5 (very high/excellent). Variables `schoolsup`, `famsup`, `paid`, `activities`, `nursery`, `higher`, `internet`, and `romantic` variables are measured with yes or no. Grades variables were taken from 0 to 20.

# Reference

1. P. Cortez and A. Silva. Using data mining to pre-dict secondary school student performance. 2008.

2. Student Alcohol Consumption dataset: https://www.kaggle.com/uciml/student-alcohol-consumption.
