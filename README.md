# Employee Database with SQL

## Overview of the Analysis

### Purpose
Pewlett Hackard is a large company that consists of several thousand employees and its employees that are baby boomers are retiring at an accelerated rate. For this latest part of the analysis the goal is to look at determine the needs of the company with the oncoming 'silver tsunami'. After importing the data provided by the company the latest set of queries will determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program.
  
  
## Results

After the careful analysis and queries that took place in pgAdmin the following conclusions coalesced.

* There is a very large number of employees that are going to retire with the oncoming 'silver tsunami'. The original query produced a table that inflated this numbers because there were duplicate entries due to an individual having worked under different titles.

* Even with the removal of the duplicates there is still a very large amount of employees that are retiring.

* When looking at the number of employees in particular positions it becomes clear that some areas are more urgent than others. The amount of employees needed with the title of 'Senior Engineer' and 'Senior Staff' far outweigh the other groups' needs.

* There is hope though because if the company acts quickly there is still time to create a mentorship program that utilizes the skillset and knowledge of those that will be retiring.


## Summary

After summing the amount of employees retiring based on count per title, there are 72,458 individuals that expected to retire in the immediate future. This is very significant and impactful amount of the workforce for the company.

There are a total of 1549 employees that are eligible to be mentors in the proposed program. If mentorship was the sole resource for finding replacements, each mentor would need to take on about 47 employees each, which is not tenable. This shows there simply are not enough mentors to make this successful without looking into complementary programs.

In order to do further analysis there are most likely more queries that can take place to glean more information. One such would be to look at the number of current employees that are not in the retiring group and break them down into departments by job title to look at tracks for them to follow. This would help to match them up with possible mentors. On the flip side, it would also be important to know what the count is for the job titles for those that are eligible for mentor roles. The program can be a successful attribute but the program needs the proper analysis to be so.
