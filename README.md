# Election Analysis

## Project Overview
This is a practice audit of the results for a local congressional race for the Colorado Board of Elections. The purpose of the assignment
was to import, read, and analyze election results in Python to produce a comprehensive summary of the race. The tasks included:

1. Calculating the total number of votes cast in the race.
2. Getting a complete list of candidates who received votes, and counties in which votes were cast.
3. Calculating the total number of votes each candidate received, and the total number of votes in each county.
4. Calculating the percentage of votes each candidate won and the percentage of total votes cast in each county.
5. Determining the winner of the election based on popular vote, and the county in which the highest number of votes were cast.

## Resources
Data source: election_results.csv
Software: Python 3.7.6

## Results
The analysis shows:
- There were 369,711 votes cast in the election
- The candidates were:
1. Charles Casper Stockham
2. Diana DeGette
3. Raymon Anthony Doane

- Charles Casper Stockham received 23.0% of the vote with 85,213 total votes
- Diana DeGette received 73.8% of the vote with 272,892 total votes
- Raymon Anthony Doane received 3.1% of the vote with 11,606 total votes

- The winner of the election was **Diana DeGette**, who received **73.8% of the vote and 272,892 votes.

- Exactly 306,055 of the votes in the race came from Denver County. That was the top total of any county, amounting to 82.8% of all votes cast in the race
- Jefferson County contributed 38,855 votes (10.5%) in the race, while Arapahoe County added 24,801 (6.7%).

## Summary
Although the code and analysis focus on a single congressional race, the product can easily be modified to summarize future elections. For starters, let's 
assume we want to compile similar summary statistics, but for a more localized race in which votes are tallied by precinct instead of county. The changes 
are really more conceptual than substantive (the same exact code could theoretically work just fine for such a race if the raw data is formatted similarly), 
but to help visualize, we could simply indicate to future users that the code is geared toward precinct rather than county tallies:

![image](https://user-images.githubusercontent.com/1015285/118376775-a4840b80-b58f-11eb-89db-eab8dc389b92.png)

![image](https://user-images.githubusercontent.com/1015285/118376809-deeda880-b58f-11eb-8c53-515ff0425b78.png)

Additionally, the code would only need slight tweaks 

