# Hypothesis-Testing-Men-Women-Soccer
Hypothesis Testing Men's and Women's Soccer Matches in Python

In this notebook I'll try to answer one life's great questions:

> Are more goals scored in women's international soccer matches than men's?

Now that is of course written with a twinkle in the eye, nether the less, I think it's an interesting question to answer. Not least in the view of the rapid development of women's football in popularity and commercially in the recent years.  

Football is considered a low scoring game and if we assume that goals are an indicator of entertainment and excitement in a football match. Let's say someone is hesitating between watching a women's international match and a men's international match, and that person wants to watch the most entertaining match, then this question also serves a purpose.

Now let's have a look on how to approach this question. I'm working with two datasets containing the results of every official men's and women's international football match since the 19th century. This data is stored in two CSV files: `women_results.csv` and `men_results.csv`. 

I've decided to limit the data used in the analysis to only official `FIFA World Cup` matches (not including qualifiers) from `2002-01-01` to `2022-12-31`.

I've decided to work with a **10% significance level**, and I use the following null and alternative hypotheses:

$H_0$ : The mean number of goals scored in women's international soccer matches is the same as men's.

$H_A$ : The mean number of goals scored in women's international soccer matches is greater than men's.
