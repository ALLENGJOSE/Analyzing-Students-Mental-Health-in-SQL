# Analyzing-Students-Mental-Health-in-SQL

## Project Overview
To explore the students database from an international university and find out what factors may impact students' mental health.

### Data Sources
Data of International and domestic students:students.csv

### Tools
PostgreSQL:DATA ANALYSIS

### EXPLORATORY DATA ANALYSIS
-Checked how many international and domestic students are in the table

### DATA ANALYSIS

Include some code/features with

```sql
SELECT stay,
ROUND(AVG(todep) , 2) ,
 WHERE ,
ORDER BY
```
### RESULT

As the question here states to focus on 3 aspects for international students with regards to their stay :
1.Total score of depression (PHQ-9 test) 
2.Total score of social connectedness (SCS test)
3.Total score of acculturative stress (ASISS test) 
The conclusion here through the query is that with longer stay depression increases and social connectedness and acculurativee stress also tend to remain high.
