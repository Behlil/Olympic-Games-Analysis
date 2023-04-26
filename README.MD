# Olympic Games Analysis:

## Data Dictionary

|Column   |Explanation                   |
| ------- | ---------------------------- |
|id       |Unique number for each athlete |
|name     |Athlete's name                 |
|sex      |M or F                         |
|age      |Age of the athlete                        |
|height   |In centimeters                 |
|weight   |In kilograms                   |
|team     |Team name                      |
|noc      |National Olympic Committee 3   |
|games    |Year and season                |
|year     |Integer                        |
|season   |Summer or Winter               |
|city     |Host city                      |
|sport    |Sport                          |
|event    |Event                          |
|medal    |Gold, Silver, Bronze, or NA    |


## Data Validation:
- Validate the necessary Categorical columns: sex, season and medal.
- Validate numerical columns: height, weight, and age(all value refer to real Athletes).

## DATA CLEANING
- Fill missing values in the age, height and weight columns.
- Replace missing values in the medal column with "No Medal"
