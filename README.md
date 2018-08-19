# The most dangerous cities for cyclists or the use of probability in a news story

As part of my final project of the MA in Data Journalism at Birmingham City University, I have been examining statistical methods for journalistic stories.

On this occasion, I have explored the use of probability for a story about the most dangerous cities for cyclists in the West Midlands. 

As in my previous analysis, I have used R to find the model and analyse the data. I also have done the charts using ggplot library. 

![Picture_casualties_cyclists](https://github.com/Carmen-Aguilar/cyclists-probability/blob/master/cyclists_casualties.png)

### Get the data

The figures used for this analysis come from the <a href="https://www.gov.uk/government/statistics/reported-road-casualties-great-britain-annual-report-2016" target="_blank">road casualties 2016 report, published by the Department of Transport</a>. 

I downloaded the information related to cyclists and I filtered only for the West Midlands' towns. As the statistical model also required the population, I looked for the 2016 population in each local authority. 

[Here is the final dataset I worked with.](https://github.com/Carmen-Aguilar/cyclists-probability/blob/master/casualties_cyclist.csv) 

### Get the analysis

The cyclists' casualties follow a Poisson distribution

To find and understand the statistical model needed I counted on [Carlos Gil Bellosta's](https://www.datanalytics.com/) help. 
