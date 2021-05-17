# Election_Analysis

## Overview of Election Audit

### Purpose

The purpose of this is to determine the voter turnout for each county, the percentage of votes received by each county and the country with the highest voter turnout. 

For loop and conditional statement would need to be used to compile the aforementioned requested results. The result would then be printed to the command line and saved into a txt file. The results and the method used to arrive at the results would be presented to the election commission.  

## Election-Audit Results

The Python code uses repetition statements, conditional statements and logical operators to print the election results to a command line and also saves them into a text file. 
Please see below for five election outcomes
1. Total Votes in this congressional election: 369,711
2. A breakdown of the number of votes and the percentage of total votes for each county in the precinct:
   * Jefferson: 10.5% (38,855)
   * Denver: 82.8% (306,055)
   * Arapahoe: 6.7% (24,801)
3. County that had the largest number of votes: Denver
4. Breakdown of the number of votes and the percentage of the total votes each candidate received
   * Charles Casper Stockham: 23.0% (85,213)
   * Diana DeGette: 73.8% (272,892)
   * Raymon Anthony Doane: 3.1% (11,606)
5. Winning Candidate, their vote count, their percentage of total votes
   * Winner: Diana DeGette
   * Winning Vote Count: 272,892
   * Winning Percentage: 73.8%

Please see below snippet from the command line showing the result. 

![results in anaconda](https://github.com/shayanafzal/Election_Analysis/blob/98bf54a7713e799857dafdd69fbdabae89007148/Resources/Results%20Displayed%20in%20Anaconda%20Prompt.png)

Please see below snippet from the text file showing the result. 

![Results in txt file](https://github.com/shayanafzal/Election_Analysis/blob/733c3702c0561ef801f5f9da2a7882bb28e15322/Resources/Result%20in%20text%20file.png)

The text file can also be accessed [here](https://github.com/shayanafzal/Election_Analysis/blob/444a2e90498617fdfbd85faaa975ebf3e9490d76/Resources/election_analysis.txt).

## Election-Audit Summary

### Script Usage
This script relies on data obtained from csv file. The advantage of using a csv file is that the same script can be used on a different election data file that is formatted in the same manner. 

### Suggestions for Modifying the Script

1.	The script can be modified to take validly into account. For example, a person not residing in the county should not be voting in that country. The script can be modified to check the voters address and to ensure that the voters reside in the county where they are voting. The total voter turnout can be compared with the population of voter in the county who are eligible to vote. 

2.	The current CSV file uses ballot ID, County and Candidate information. This can be expanded to include additional data. For example, the voters age, gender and political affiliation data can be collected. The Python script can then be further modified to determine the voter spread across age, gender and political party affiliation under each county.





