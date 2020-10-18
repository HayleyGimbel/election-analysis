# election-analysis
Using Python to complete Module 3

## Project Overview
I am working on a project for the Colorado Board of Elections, who has given me the following tasks to complete an election audit for a recent campaign.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code: 1.50.0
  
## Overview of Election Audit:
The purpose of this election audit is to determine the overal number of votes cast in the election, the number of votes cast for each candidate, and the number of votes cast in each county.  Using these insights, we can determine which county had the largest voter turnout and which candidate won the election.

## Election-Audit Results:
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- Breakdown of votes by county:
  - Jefferson County represents 10.5% of total votes with 38,855 votes cast
  - Denver County represents 82.8% of total votes with 306,055 votes cast
  - Arapahoe Countt represents 6.7% of total votes with 24,801 votes cast
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 of votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 of votes.

## Election-Audit Summary:
The script used to perform this election audit is designed to be reused for any future elections.  The script specifies variables for county, candidate, and vote counts for each which allows the script to function even if the data set is changed.  The script would need to be moified if the data sets for future elections include additional columns of data.  For exmaple, candidate_name = row[2] would need to be edited to ensure the script reads data from the correct column. The script would also need to be edited to reflect the correct path to the new data set.  For example in the script, file_to_load = os.path.join("Resources/election_results.csv"), "Resources/election_results.csv" would need to be replaced with the path to the new data set file. 

