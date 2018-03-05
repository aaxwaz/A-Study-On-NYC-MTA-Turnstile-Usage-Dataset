# A study on NYC MTA Turnstile Usage Dataset

Original data is from: 
http://web.mta.info/developers/turnstile.html

All data files have been pre-loaded into .h5 database, which will be accessed through using pandas data frame. 

Basically, the study is trying to answer the below questions in two parts: 

-- Data Analysis: 

1. What is the total number of entries & exits across the subway system for August 1, 2017?
2. If we define the "busy-ness" as the sum of entry & exit count, what station was the busiest on August 1, 2017? What turnstile was the busiest on that date?
3. What were the busiest and least busy stations in the system over all of July 2017?
4. Which station had the highest average number of entries between midnight & 4am on Fridays in July 2017?
5. If we compare the month of July 2016 to the month of July 2017, what stations have seen the highest usage growth/decline?
6. What other findings from this dataset would you consider potentially significant? Do you notice any inconsistencies or irregularities (e.g., outliers)? If so, what might you infer from them? How should these irregularities be treated in any predictive modeling on this data?

-- Modelling:

Following the data analysis, we'd be eager for you to engage in predictive modeling:
1. Please develop, fit, and evaluate a model that can predict the exit count for any given turnstile device and date, taking care to walk us through each step of your process.
2. Based on your model: What features are explored? How does this model perform?
