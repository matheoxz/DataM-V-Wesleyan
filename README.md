Thats a repository to the Wesleyan University Coursera course of Data Management and Visualization
The blog to the assesments is https://gapmindersuicide.tumblr.com/

# GapMinder Democracy Rate and Suicide

After reading the GapMinder code book, i began really interested in democracy rate and its impacts. So, the first question that comes to mind is if the democracy rate is correlated to the suicide rate.

A quick search in the Google Scholar returned [a very brief paper](https://journals.sagepub.com/doi/abs/10.2466/pr0.1999.85.2.518) that aims to answer the question if democracy rate is correlated to the homicide and the suicide rate. The data analysed was separated in two: before and after 1965, where the first seems not to be correlated and the second is. The metric used was Pearson’s correlations. <br>

Another paper found was [“Democracy, Autocracy, and Direction of Lethal Violence: Homicide and Suicide”](https://journals.sagepub.com/doi/abs/10.1177/1088767918775465), which discovered “that people in a democratic nation are likely to direct violence inward rather than outward, blaming themselves for their failures and frustrations. By contrast, those in ideal autocratic nations are likely to use violence toward others, directing blame outwards for personal failures and frustrations.” <br>

So, the second question is if the democracy rate is correlated to gender equality. A quick search returned the paper ["Democracy and Gender Equality"](https://link.springer.com/article/10.1007/s12116-009-9043-2) which found that “countries with greater stocks of democracy and longer experience of women’s suffrage have a higher proportion of the population that is female, a greater ratio of female life expectancy to male life expectancy, lower fertility rates, and higher rates of female labor force participation.” <br>

To answer the questions I will use the GapMinder database and codebook, specifically the variables **“polityscore”**, **“suicideper100TH”** and **“femaleemployrate”**. <br>

**polityscore:** <br>

2009 Democracy score (Polity). Overall polity score from the Polity IV dataset, calculated by subtracting an autocracy score from a democracy score. The summary measure of a country's democratic and free nature. -10 is the lowest value, 10 the highest. Source: Polity IV Project.

**suicideper100TH:**<br>
2005 Suicide, age adjusted, per 100 000 Mortality due to self-inflicted injury, per 100 000 standard population, age adjusted. Souce: Combination of time series from WHO Violence and Injury Prevention (VIP) and data from WHO Global Burden of Disease 2002 and 2004.

**femaleemployrate:** <br>
2007 female employees age 15+ (% of population) Percentage of female population, age above 15, that has been employed during the given year. Source: International Labour Organization.

