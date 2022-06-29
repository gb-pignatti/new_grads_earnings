# Visualizing Earnings and Gender Disparity Based on College Majors

## Project Overview

All around the world, both governments and independent institutions crucially rely on data related to the education industry to assess the health status of this sector and, more in general, of the labor market. Common metrics such as unemployment rates among new graduates are constantly monitored and, in case of particularly critical numbers, the appropriate departments might advance reform proposals to fix the issue. In some multicultural countries like the US, furthermore, data regarding the ethnicity composition (or even just the sex) of the student population can serve as a gauge for the national level of inclusivity and equal opportunities.       

Following these guidelines, in this project we use data visualization to investigate the job outcome and gender disparity among new graduates from US colleges. Along our analysis we will touch on many important topics, both social and economic.   

## Notebooks Description

1. **visualizing_earnings.ipynb**: we study the distribution of the median salary earned by students who graduated from US colleges between 2010 and 2012 across 173 different majors; to get a more compact picture, we group these majors into 16 categories and determine if the categories which give access to the best paying jobs are also the most popular ones (i.e., the ones with more graduates). We then focus on the gender breakdown of each major and check if this feature has an influence on the median salary (spoiler alert: it does 😔). Finally, we analyze the unemployment rate among new graduates.
2. **visualizing_gender_gap.ipynb**: we use a dataset which contains the percentage of female bachelor's graduates at US institutions among 17 different majors and across the academic years 1970-71 to 2011-12. In the end, we obtain a picture (contained in the `gender_gap.png` file) which shows how this percentage has evolved over the given period of time and across all given majors.

## Insights Achieved

After analyzing the data and drawing the appropriate plots, we conclude that:

1. The majority of employed new graduates has a median salary that ranges between \\$33,300 and \\$36,600.
2. The major categories that give access to the highest paying jobs are *Engineering*, *Business*, *Computers & Mathematics*, *Law & Public Policy* and *Physical Science*. More in general we see a dominance of STEM fields over Humanities and Social Sciences.
3. There is no correlation between median salary and total number of graduates. This means that the most popular majors don't necessarily coincide with the richest ones.
4. About 56% of all majors have more women graduates than men. However, when we group by major category, the gender imbalance gets more extreme: only 6 out of the 16 different categories are predominantly male.
5. There is a strong disproportion regarding the richest majors. In particular, all top 5 majors are predominantly male and all bottom 5 majors are predominantly female. A similar polarizing situation appears if we use major categories instead.
6. More than half of the majors report an unemployment rate among new graduates which is below 8%. This is lower than the unemployment rates recorded nationally in the US during the same time span.
7. Unemployment rates are related neither to median salary nor to total number of graduates. In particular, high unemployment rates are recorded in top ranked majors as well as very low ranked majors. We infer that unemployment rates might be influenced by factors that are uniquely specific to each major.   
8. Most of the STEM majors are historically (and still to these days) largely dominated by men.
9. In the Liberal Arts category all majors (apart from *Social Sciences and History*) have a stronger female participation.
10. For the other majors the scene is quite mixed.

## Note

I completed this project a long time ago, when I was still at the beginning of my data science journey. The two notebooks have since then lived on my remote computer and I have just recently decided to push them to GitHub. This is to say that the code and style of the project will inevitably result more rudimental when compared to some of the repos I have previously created.    
