# election_analysis

## Overview of Election Audit

There recently was an election for the US Congressional Precinct in Colorado. An employee from the Colorado Board of Election Committee is requesting support to summarize the results using python. These results will aid in automating the process of auditing and certifying this election, other congressional disticts, and local elections. This analysis also includes more granular statistics like percentage of votes for each county, voter turnout for each county and which had the highest turnout also. 

## Election-Audit Results

- The total number of votes cast in the election was 369,711.

- The counties included in the race were Jefferson, Denver & Arapahoe
  - Jefferson received 10.5% of the votes, which was 38,885 of the total votes
  - Denver received 82.8% of the votes, which was 306,055 of the total votes
  - Arapahoe received 6.7% of the votes, which was 24,801 of the total votes
  
- Denver had the largets number of votes by county 

- The candidates in the race were Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane
  - Charles Casper Stockham received 23.0% of the votes, which was 85,213 of the total votes
  - Diana DeGette received 73.8% of the votes, which was 272,892 of the total votes
  - Raymon Anthony Doane received 3.1% of the votes, which was 11,606 of the total votes
 
- Diana DeGette won the election with 73.8% of the votes, by receiving 272,892 votes of the total 369,711 votes. 

![image_name](Resources/Election_Analysis_Summary_Results.png)

## Election-Audit Summary 
The script provided for this election audit can be altered to fit any other type of election desired. For example, in this election we were looking at the results by county, however we could look at it by state or also by city. The setup for this would be very similar to the setup now, we would just have to ensure that the city or state data is also in the election_results.csv, and then summarize by city or state instead of by county. 
