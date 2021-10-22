# Kickstarting with Excel: Kickstarter Analysis

## Overview of Project

This project had me utilize Excel to analyze data on hundreds of fundraising initiatives around the world and their goals, along with any factor that may have had a role in their success/failure. 


### Purpose

The purpose of this challenge was to be able to analyze data on a plethora of kickstarter campaigns and test how their success or failure fared when it came to their **launch dates** and **fundraising goals**. 


## Analysis and Challenges

The main challenges a newer coder like myself would face here are getting accustomed to filtering many columns at once and how the resulting arrangement can be used. Gaining confidence working with several open sheets was tricky, but repetition was the key to getting better at it. Highlighting and filtering with conditionals with a big help in the analysis, and combing through the data over again helps a lot with getting a solid mental foundation of what the given data set exhibits. 

### Analysis of Outcomes Based on Launch Date
![Outcomes Based on Launch Date Graph](/Users/michael/Desktop/Challenge Resources/Theatre Outcomes by Launch Date.png)

The launch dates of kickstarter campaigns had a sizable role in their success, as campaigns launched mid-year (May-July) experienced the most success. Overall, there were more successes than failures. 
	

### Analysis of Outcomes Based on Goals
![See chart of Outcomes Based on Goals](https://github.com/mtryergreen/kickstarter_analysis/blob/main/Outcomes_vs_Goals.png)

	Based on the data that our line graph communicates, projects with lower goals often meet their goal while only a narrow portion of high-goal projects meet their desired outcome. <1,000 to 19999 is a pretty safe spot to keep a goal, while the next safest goal range is 35000 to 49999. 

### Challenges and Difficulties Encountered

	Analysis was made easier with the use of filters on the column heads. The main challenge I faced was the trial and error process of witching the filters, columns, rows and values around to make a graph the way I wanted. Another tricky bit was the assignment using "countifs()", which took me a while because these bits of code were much longer, therefore mistakes took me more time to find and fix.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Theater programs were more likely to find success if they were launched mid-year, between April and July. The peak month for launches of successful programs was May. 

Additionally, the least successful initiatives were launched at the end of the year, with the most failures occurring in October and the least success being in December. 


- What can you conclude about the Outcomes based on Goals?

More project outcomes are successful when their goal funding amount is lower, as evidenced by the highest percentage successful was in the range of less than $1,000 to $1,000 to $4,999. 

There is a slope between $20,000 and $35,000 where many projects fail, and an even higher rate of failure at $45,000. This seems to be the region where smaller projects fail and larger projects have a better chance at succeeding. Much fewer projects have a chance to succeed when they aim for higher funding goals. 


- What are some limitations of this dataset?

It's very likely that this dataset does not capture all kickstarter efforts around the world, thus it's missing some information that could change the conclusions I can make from it right now. 

There are most likely other variables that impact the success or failure of fundraising efforts that this dataset is not considering

An additional limitation of the dataset was the need to further dissect the parent category from the subcategory, as on its own it provided less useful information for those seeking specific data on "plays". The data is all there, but needs to be filtered through in order to be accessed readily. 

- What are some other possible tables and/or graphs that we could create?

We could create pie charts to showcase what proportions of kickstarter campaigns succeed versus which fail. Admittedly, these seem to be faulty becuase pie charts have a value limit (or so my Mac tells me), so only a small chunk of the data can be evaluated at a time. 


We can also produce line graphs showing how average donations compare to the percentage funded over the course of the year. 
