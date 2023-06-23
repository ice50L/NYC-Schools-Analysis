# NYC-Schools-Analysis

## Introduction: 

New York City education can be one of the most prestigious in the country in terms of high schools, such as one of the most known schools, Stuyvesant high school and Townsend Harris. However, from these standout schools known for their prestige, there are some schools in New York that do not fare as well. In this project, the main goals of the analysis is to show the average SAT scores for each school, the gender/race ratios per school compared to the SAT scores, etc. Some in-depth looks in the analysis are based on the top 10 schools in NYC based on the average SAT score and the individual critical reading, math, and writing skills. The data was sourced from: https://data.world/dataquest/nyc-schools-data, which contains all of New York City's education data in 2015-2016. 

## Questions:
- Which schools has the highest overall average SAT score?
- Is there a race trend for the top schools in NYC?
- What are the boroughs of the top schools?
- Overall, is the critical reading score higher than the math score?


## Findings:
![image](https://github.com/ice50L/NYC-Schools-Analysis/assets/115594312/70673002-f436-4fff-8e9a-1d108a0f7782)

The top 10 schools and their corresponding boroughs. The barplot shows that Manhattan has the most schools that have the highest SAT score (4), followed by the Bronx and Queens with 2 schools each. 

![image](https://github.com/ice50L/NYC-Schools-Analysis/assets/115594312/01ce938f-6bf5-4a2a-b69f-cddd1f37ba1d)

From this distribution, it appears that the percentage of female and male students do not impact the outcome of the average SAT score per school. From the barplot, it seems that some school has more male students and for the other top schools, it seems that there are much more female students in attendance, such as Townsend Harris.

![image](https://github.com/ice50L/NYC-Schools-Analysis/assets/115594312/921b3998-7c0d-4243-90f2-16d568ce79cd)

It appears from this that there are a large disproportionate race distribution for each of the top 10 schools. It seems that there are never a majority Hispanic or African American population in any of these schools, the races that make up the majority of the races are usually Asian and white. And this is usually in a large disproportionate amount as well. Some schools like Stuyvesant high school and Bronx High School of Science has over 60% Asian students, while Elanor Roosevelt High School and Bard has over 50% white. The average indicated displays that Asian and white students always make up the majority of the school population compared to Hispanic and African American students. 

![image](https://github.com/ice50L/NYC-Schools-Analysis/assets/115594312/5bbd9d8e-b04b-42a7-86b3-73c87d9389b6)

Manhattan's upper quantile is about 1750 while the upper quantile for the Bronx is about 1300. The difference between the 2 boroughs is substantial, Manhattan's median score is almost the same as the upper quantile for the Bronx, which really shows the clear issues of education difference between the 2 boroughs. Manhattan is known for being the center of the city and the most well funded compared to the Bronx, which is commonly known as a "dangerous" and underfunded place to live. This can explain the clear inequality on the SAT scores, since schools in the Bronx are usually underfunded and therefore the education quality would be lacking as well. 

![image](https://github.com/ice50L/NYC-Schools-Analysis/assets/115594312/c5318e46-afb1-4270-9fae-6d5c44179301)

A comparison for all of the boroughs (not including Staten Island due to the small school sample size), it shows that Queens and Manhattan has the highest average SAT score, which can be due to the fact that both Queens and Manhattan have large government funding support while the Bronx and Brooklyn do not have the same amount of funding and education quality as the 2 other boroughs. 

![image](https://github.com/ice50L/NYC-Schools-Analysis/assets/115594312/70ab5ceb-4a44-4269-b260-9f1926c77f8c)
![image](https://github.com/ice50L/NYC-Schools-Analysis/assets/115594312/2aa1b179-6fd8-4ff0-a59b-22e77e834078)

The regression plots show that the average class size and the average SAT score does have a positive correlation between one another. For the dropout rates and score comparison, as expected it appears that the higher the dropout rate, the more likely the average SAT score would suffer, large dropout rates can be correlated with the education quality of the school and the amount of funding they recieve. 

![image](https://github.com/ice50L/NYC-Schools-Analysis/assets/115594312/a57ca6c3-a81d-4b44-9cd3-32b657bed83c)
![image](https://github.com/ice50L/NYC-Schools-Analysis/assets/115594312/a718f8d9-c238-4938-aae2-d2e7830a914c)

From the distribution plot, there appears to be about a normal distribution for both the SAT math and critical reading section. The average for both critical reading and math are about the same at around 400-450, while the math section having a larger right skew in score distribution, which means more people perform better on the math section compared to the critical reading section of the SAT. 
