# Election Analysis

Using Python to analyze election results

## Overview of Election Audit

An analysis of election results to find the number of votes in each county, distribution of votes to each candidate, and the winning candidate of the election.

### Purpose

Assisting a Colorado Board of Elections employee, Tom, for a precinct in Colorado. I have been tasked to find the total number of votes cast, the total number and percentage of votes for each candidate, and the winner of the election based on the popular vote. Additionally, the Colorado Board of Elections would like to know the turnout of voters in each county. This includes the total number and percentage of votes in each county and the county with the largest turnout.

## Election Audit Results

The election results were presented in a CSV file with headers Ballot ID, County, and Candidate.

- Using the CSV, Python determined there were 369,711 votes counted.
- The counties and their results recorded were:
  - Jefferson county with 38,855 votes or 10.5% of the total votes.
  - Denver county with 306,055 votes or 82.8% of the total votes.
  - Arapahoe county with 24,801 votes or 6.7% of the total votes.
 - With 82.8% of the total votes, Denver county was the county with the largest turnout.
 - The possible candidates and their results recorded were:
  - Charles Casper Stockham received 85,213 votes or 23.0% of the total votes.
  - Diana DeGette received 272,892 votes or 73.8% of the total votes.
  - Raymon Anthony Doane received 11,606 votes or 3.1% of the total votes.
 - With 7.8% of the total votes, Diana DeGette won the popular vote.
 
 Below is a snapshot of the txt file created by Python to show the results.

![election_results](https://user-images.githubusercontent.com/108373151/180626105-3f89903b-f8df-4fd6-b792-83795da87337.png)

## Election Audit Summary

- The script in Python was created in such a way to be easily adaptable to future elections in this same precinct or in other precincts with limited changes. A similar CSV file with the 3 columns (Ballot ID, County, and Candidate) will need to be created to reflect all the votes in the precinct. And then the code will need to be updated to point to that new CSV file. The file_to_load scipt on line 9 is the code that will need to be updated with the saved location of the new file. There is no code that is restrictive to this precinct or these candidates, so the updates required will be minimal.

 - Additionally, the Python script could be used on a larger scale with state-wide elections for governor or state legislature. The references to county and candidate would stay the same. The code is not limited to 3 counties and 3 candidates. It was created to process and analyze any number of counties and any number of candidates.

 - The Python script could even be scaled down for mayoral or other municipal elections. Any references to county counts, percentages, and turnout will need to be changes to city counts, percentages, and turnout to make sense. Any references to candidates would not need to be changed.






