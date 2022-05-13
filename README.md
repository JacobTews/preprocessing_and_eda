# Sample project: Preprocessing and EDA

**"HR has requested some help with a project," my team lead, Jordan, explained**

"They have data from a survey given to a bunch of managers, and they'd like you to go through it to find:
* the average salary for a software engineer for each currency,
* the average salary for a software engineer for each currency _grouped by age_, and
* a comparison of the four currencies which are most common in the data.

"And just a heads up: the data is a bit messy, since there are some free-response text fields in the survey, so it will need some cleaning. You'll also need to grab currency conversions to compare the salaries.

"They need the information by the end of the day."

"I'm on it!" I replied, and headed back to my desk to get started...

## 🎯 Goals
* Explore the dataset, handling missing entries
* Determine the salaries for software developers and engineers in USD
* Determine the average S/E salary for each currency and the average S/E salary for each currency based on age
* Visualize a comparison by plotting the salaries based on age for the top 4 currencies in the merged dataset

## 🏗 Dependencies
* Python 3.9.7
* matplotlib.pyplot
* numpy
* pandas
* re
* seaborn
