# kickstarter-analysis

## Overview of Project

### Purpose
  The overview of the project was to analyze the main report, the kickstarter Challenge, to see how other campaigns fared compared to Fever. By using the Kickstarter Challenge data given, the data was broken down into 2 datasets so we can give Louise a cleear and concise report on our findings. We'll breakdown the data using two different types of Excel spreadhseets, pivot tables and formulas (COUNTIF).

## Analysis and Challenges

  In order to perform the Analysis, we had to 1st figure out what kind of data we were using and whate data was needed in order to tell lthe story. In order to do this we had to figure how to set up our data in a way it would tell the story.  We will compare 2 pieces of data, the first being the "OutcomesBased on Launch Date".  This will show all of our outcomes by month and it will show what succeeded, what failed and what canceled by month.  The data is from all parts of the world and covers all theatre.
  
  The 2nd piece of data will be the outcomes based on goals.  For this dataset, the focus will be on goals based on acertain range of pledges (Dollar Amount).  In this analysis, the data will be broken down into a monatary range and from that set range, we'll be able to identify what succeeeded, what failed and what was canceled.  From that, we can also get a percentage of what worked, what didn't and what was canceled.
 
 
  

### Analysis of Outcomes Based on Launch Date

 Theatre Outcomes by Launch date - We gathered information from the Kickstarter data and created a Pivot table on the information. Our key components of data consisted of our filters, Parent company, which in this cases is "theatre", and "years" to get the timeframe.
   -  I decided to use the date of conversion to get the timeframe, in this case, I'm looking for the months in the year. 
   -  Finally, I wanted to see how each one fared, "successful, "canceled", or "failed".  I grabbed the total counts of those pieces of data and created columns
   - Once I created the table, I wanted to see how it would look visually - To create a visual, a chart was created, to "see" what was found.
   -  See below Links on my findings
    
    
   ![image](https://user-images.githubusercontent.com/94253815/143725091-1ffe87a2-adf2-4426-bf33-e58c4b724a85.png)




    
    
 
 
    
 

### Analysis of Outcomes Based on Goals

2. The second piece of data we needed to see were the outcomes based on goals - Breaking down the number of "successful", "failed", and "canceled" pledges, based on dollar amount or dollar amount Range.
    a) We needed to create a table in which we could see the number of "successfu", "failed" and Canceled" pledges based on multiple goal ranges.  In order to do this we used a countIF formula in Excel to help us find those ranges.
    b.) Once those ranges were found, we did a sum of all of the projects from each goal dollar range.
    c)  Next, we found the percentage of "successful", "failed", and "canceled" for each dollar range
    d) Finally, we created a line chart that shows the results of our findings.
    
    
     ![image](https://user-images.githubusercontent.com/94253815/143725046-625f33e7-bfab-4755-bf2e-64729ee0a80e.png)
    
    
    
    
   
    
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

