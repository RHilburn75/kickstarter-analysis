# kickstarter-analysis

## Overview of Project

### Purpose
The overview of the project was to analyze the main report, the kickstarter Challenge, to see how other campaigns fared compared to Fever. By using the Kickstarter Challenge data given, the data was broken down into 2 datasets so we can give Louise a cleear and concise report on our findings. We'll breakdown the data using two different types of Excel spreadhseets, pivot tables and formulas (COUNTIF).

## Analysis and Challenges

  In order to perform the Analysis, we had to 1st figure out what kind of data we were using and whate data was needed in order to tell lthe story. In order to do this we had to figure out the following:
 1. What were the outcomes by their start date?  H 
 
  

### Analysis of Outcomes Based on Launch Date

 Theatre Outcomes by Launch date - We gathered information from the Kickstarter data and created a Pivot table on our information. Our key components of data consisted of our filters, Parent company, which in this cases is "theatre", and "years" to get the timeframe.
    a. I decided to use the date of conversion to get the timeframe, in this case, I'm looking for the months in the year. 
    b. Finally, I wanted to see how each one fared, "successful, "canceled", or "failed".  I grabbed the total counts of those pieces of data and created columns
    c. Once I created the table, I wanted to see how it would look visually - I'm a visual person, so by creating a chart, I thought it would be easier to "see" our findings
    d. See below Links on my findings
    
    
    ![image](https://user-images.githubusercontent.com/94253815/143724949-120c9feb-e0d3-4939-9435-e2e7881f7c23.png)


    
    
 
 
    
 

### Analysis of Outcomes Based on Goals

2. The second piece of data we needed to see were the outcomes based on goals - Breaking down the number of "successful", "failed", and "canceled" pledges, based on dollar amount or dollar amount Range.
    a) We needed to create a table in which we could see the number of "successfu", "failed" and Canceled" pledges based on multiple goal ranges.  In order to do this we used a countIF formula in Excel to help us find those ranges.
    b.) Once those ranges were found, we did a sum of all of the projects from each goal dollar range.
    c)  Next, we found the percentage of "successful", "failed", and "canceled" for each dollar range
    d) Finally, we created a line chart that shows the results of our findings.
    
    
    
   
    
### Challenges and Difficulties Encountered

The biggest challenge that I came across was in the "outcomes based on on Goals" data.  The countIF formulas were difficult to get started but the good thing is that once you started, you could copy and paste the formula with just a few tweeks n the formula itself, in order to get the correct data

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

 1. "successful" outcomes began climbing beginning of March and peaked in May. After May, "successful Outcomes" began to decline throughout the rest of the year.
 2. Failed Pledges remained consistant throughout the year.

- What can you conclude about the Outcomes based on Goals?
 1. That all dollar goals between $0 and $19999 had a higher "Successful" pledge goal or 68% (673 of 985), than failed - 312 ,or 32%

- What are some limitations of this dataset?
 1. Too Broad-  The data is a high view point of plays throughout the world.  If you could drill down to individual countries, you would get a better sample of data

- What are some other possible tables and/or graphs that we could create?

