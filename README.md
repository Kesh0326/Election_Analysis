# Election_Analysis

## Project Overview
To perform an election audit for the Colorado Board of Elections on a recent local congressional election to retrieve and display the following - 

  1) The total number of votes cast
  2) A complete list of counties and candidates that received votes
  3) The percentage of votes each candidate won and each county received 
  4) The total number of votes each candidate won and each county received 
  5) The winning candidate and county with largest voter turnout based on popular vote
  

## Resources
* Data source: election_results.csv
* Software: Python 3.7.6, Visual Studio Code, 1.48.2

## Analysis Summary
#### The analysis of the election show that:
* There were 369,711 votes cast

#### The candidates were:
* Charles Casper Stockham
* Diana DeGette
* Raymon Anthony Doane

#### The participating counties were:
* Jefferson
* Denver
* Arapahoe

#### The candidate results were:
* Charles Casper Stockham received 23.0% of the votes and 85,213 votes
* Diana DeGette received 73.8% of the votes and 272,892 votes
* Raymon Anthony Doane received 3.1% of the votes and 11,606 votes

#### The county results were:
* Jefferson county received 10.5% of the votes and 38,855 votes
* Denver county received 82.8% of the votes and 306,055 votes
* Arapahoe county received 6.7% of the votes and 24,801 votes

#### The winner of the election was:
* Diana DeGette, who received 73.8% of the votes and 272,892 votes 

#### The county with the largest voter turnout was:
* Denver, with 82.8% of the votes and 306,055 votes

## Recommendation Summary
The script provides an analysis of the counties and candidates taking part in the election along with the winner/entity with the largest vote count in the respective categories. This analysis can be extrapolated to an election that involves multiple counties/states to include a sample size of the entire United States along with multiple candidates
''' 
##### Get the candidate name from each row.
        candidate_name = row[2]

##### Extract the county name from each row.
        county_name = row[1]
'''
By changing the index value '[]' above, the script can be modified to include column name regardless of its position in the csv file and is flexible to include a large dataset that includes multiple candidates/counties/states/countries.

