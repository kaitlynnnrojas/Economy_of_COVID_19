# Economy_of_COVID_19
Here I look at the relationship between COVID-19 and its impact on numerous economic variables.

Goal of my project - 
The goal of my project was to examine the relationship between COVID-19 and its impact on different economic variables through the use of a wikipedia API. These variables include, but are not limited to, unemployment rate, inflation rate, and the average level of the S&P 500 as an indicator of stock market peformance. From the point of data extraction, I worked to import the wikipedia API in order to find a wiki page about economic factors of COVID-19. I then cleaned and transformed the data to change column names and sort by only the relevant economic variables involved. Then, I charted a bar plot of the April 2020 COVID-19 economic variable data to see the trends between the variables. I chose the month of April as it had the highest unemployment rate, being 14.7%. Knowingly so, this time period reflected a time of economic uncertainity and would give us good headway into seeing just how COVID-19 affected the U.S. economy. 

Relevant API documentation - 
https://www.mediawiki.org/wiki/API:Main_page

Data & License - 
MIT license 
https://en.wikipedia.org/wiki/COVID-19_pandemic_in_the_United_States

Data dictionary -
Job level - int,  monthly change in jobs - int,  unemployment rate - float, number emplyed (millions) - float,  employment:population ratio - float, inflation rate - float,  stock market s&p 500 average level - int, debt held by public (trillion) - float

Potential Issues - 
Potential issues from extraction to analysis of the economic variables could include: unemployment rate doesnt account for those who are actively looking for a job. By seeing those who are actively seeking work vs those who received COVID-19 stimulus checks, we could go further and identify the spirit of the public population during COVID-19. Also, for further studies I would incorporate and merge a wiki api of worldwide covid economy data and covid economy data in China. This would give way to more comparison between China and the United States, vs the world as a whole, to see just exactly how our economy has shifted in that period. Furthermore, a comparison to the modern day economy could help us understand economic policy during COVID-19 and how that has shaped the COVID and post-COVID economy. 
