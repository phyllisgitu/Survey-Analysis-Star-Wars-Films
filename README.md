# Survey-Analysis-Star-Wars-Films

The team at [FiveThirtyEight](https://fivethirtyeight.com/features/americas-favorite-star-wars-movies-and-least-favorite-characters/) became interested in answering some questions about Star Wars fans. In particular, they wondered: Does the rest of America realize that “The Empire Strikes Back” is clearly the best of the bunch?

The team needed to collect data addressing this question. To do this, they surveyed `Star Wars` fans using the online tool SurveyMonkey. They received 835 total responses, which you can download from their [GitHub repository](https://github.com/dataquestio/solutions/blob/master/Mission201Solution.ipynb).

The data has several columns, including the following:

- RespondentID — An anonymized ID for the respondent (person taking the survey)
- Gender — the respondent's gender
- Age — the respondent's age
- Household Income — the respondent's income
- Education — the respondent's education level
- Location (Census Region) — the respondent's location
- Have you seen any of the 6 films in the Star Wars franchise? — a Yes or No response
- Do you consider yourself to be a fan of the Star Wars film franchise? — a Yes or No response

There are several other columns containing answers to questions about the Star Wars movies. For some questions, the respondent had to check one or more boxes. This type of data is difficult to represent in a column. As a result, this dataset needs a lot of cleaning.

These are the questions I endeavor to investigate in this project:

-  Among the six Star Wars movies released between 1977 and 2003; which is the most favorite and what is the order of movie preference from first to sixth among the viewers surveyed?

-  Is there a relationship between movie preference and the number of people who watched the movies?

- Do male and female viewers agree on the order of movie preference from first to sixth? 

-  Is there any difference in movie preference among Age groups and Education level?

- There are fourteen characters identified in the survey who were portrayed in some or all of the movies identified. Who were the top 5 most liked and the bottom 5 most disliked?
