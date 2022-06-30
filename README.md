# Election_Analysis

## Project Overview 
During the course of this module, we had to perfom an analysis on a dataset for a recent congressional election within the Colorado Board of Elections. The purpose of the analysis was to determine who the winning candidate was and identify where the largest voter turnuout was based on each of the 3 listed counties. 

### The analysis required the following to be calculated:
1. The total number of votes cast.
2. The list of all candidates in the election.
3. The total number of votes received per candidate.
4. The total number of votes per county.
5. The percentage of votes for each candidate.
6. The winner of the election.
7. The county with the largest voter turnout.

## Election-Audit Results 

### After reviewing the data and performing an analysis, these are the following insights I'd like to showcase: As seen from the below image, there was a total of **369,111** votes cast collected from the 3 counties (Jefferson, Denver, Araphoe) in the precint.

1. Denver, which was notably the largest voter county turnout of **306,055 votes**, had **82.8%** of the total votes. 
2. Jefferson, was the *second largest* vote county turnout accounting for **38,855 votes**, had 10.5% of county votes. *72.3% difference from Denver.*
3. Araphoe, was the final vote county. This county had a turnout of **24,801**. They had only 6.7% of the total votes. *76.1% difference from Denver.*

![image](https://user-images.githubusercontent.com/102767530/176586874-90b0f23c-1481-4ddf-8d69-781d9f2af76b.png)

### Candidates: 
The following is the list of the candidates that ran in the election and reflects the data gathered from each candidate.

1. Charles Casper Stockham
- Won **23.0%** of the vote
- Total Votes: **85,213**

#### 2. Diana DeGette
- Won **73.8%** of the vote
- Total Votes: **272,892**

3. Raymon Anthony Doane
- Won **3.1%** of the vote
- Total Votes:**11,606** 


*Diana DeGette was the winner of the election as she received the majority of the votes (**272,892!**)*

![image](https://user-images.githubusercontent.com/102767530/176588798-15891e12-67d7-44b7-af40-12815f68b947.png)

## Election-Audit Summary

The script used in this analysis was very thorough and effecient and easily digestable. It can be easily recreated and customized to be used in larger scale elections to analyze larger sets of data (i.e Federal Elections).

Couple recommendations to consider: 
1. Adding the more fields to get more granular on the type of data we get. For example, modifying by target regions to get data by demographic groups. 
- This can be done by performing surveys, researching administrative records, etc.
2. When saving txt.files - creating more specific names to save the results so it can be shared individually. 
- The benefit of this method would be the key stakeholders can be focused on a subset of the results and not all key results.


## Resources
Data Source: election_results.csv Software: Python 3.10, Visual Studio Code
