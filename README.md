# Surfs Up: A Review of the Weather

### Using Advanced Data Retrieval Techniques with SQLAlchemy

## Purpose of Review

W. Avy wanted the review of two certain months thorughout the year, June and December. These two months are 6 months apart and arre in summer and winter. Looking at the statistical information on the temperatures during these two timeframes will allow W. Avy to determine if the ice cream and surdboard shop is a good investment. In addition, if this first shop is profitable, the business would scale to other locations, and thus this code would need to scale as well. 

This is where SQL Alchemy comes in, we need to use the power that is in this tool to see if the temperature review can scale as much as we need it to. Refactoring some already done code allows us to perform a large amount of analysis is a small amount of code and time.  

## Results: June versus December Weather 

When pulling the data for June and December these were put into a list and converted to a dataframe. After they were put into a dataframe a statistical analysis was completed using the .describe function.

![june_vs_december](https://user-images.githubusercontent.com/100856534/169626583-bd722e4f-944c-42f6-bd37-e2f71bf5f967.png)

When comparing these two months there are several differences that can be observed. 
  - More data is collected in June rather than December.
  - The average temperature is 75 in June, which is warmer by close to 4 degrees than in December
  - The minimum temperatures are a lot more spread apart, with it being 64 in June and 56 in December. 
  - The standard deviation is .5 greater in December than in June, meaning that the temperatures in December would flucuate more than in June. 
  - The mean for both June and December are fairly similar to its 50th percentile, meaning that even though the temperatures would flucuate they remain consistent. 

## Summary

With the temperatures being very nice for both June and December, it would appear that being cold would not be a problem when opening a surf shop that serves ice cream all year round. At these temps, ice cream would always be enjoyable. 

However, weather is not just the temperuature. There are many factors that could effect the surf shop's profitability. Addtional analysis could be done in the following areas when it comes to the weather.
 - Precipitation
 - Cloud Cover
 - Wind/ Windspeeds
 - Average Storms per Month
