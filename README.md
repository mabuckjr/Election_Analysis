# Election_Analysis
## Project Overview
A Colorado Board of Elections employee gave me the following tasks to complete the election audit of a recent local congressional election.

  1. Calculate the total number of votes cast
  2. Get a complete list of candidates that received votes
  3. Calculate the total number of votes each candidate received
  4. Calculate the percentage of votes each candidate won
  5. Determine the winner of the election based on popular vote.
  6. Calculate the amount of votes cast in three counties (Jefferson, Denver, and Arapahoe)
  7. Calculate the percentage of total votes cast in each county
  8. Determine the county with the largest voter turnout

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.5

## Results
The analysis of the election shows:
- There were 369,711  votes cast in the election
- There were 3 candidates, and their names were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doanne
- The results for each candidate were:
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)
- Dianna Degette won the elction in a landslide victory with 73.8% of the popular vote (272,892 total)
- The results for each county were:
-   Jefferson: 10.% (38,855)
-   Denver: 82.8% (306,055) 
-   Arapahoe: 6.7% (24,801)  
- Denver County had the largest turnout with 82.8% of all votes cast (306,055 in total)

[Here](https://github.com/mabuckjr/Election_Analysis/blob/main/Resources/Photo_of_Election_Results.PNG) is a photo of the printed output of my code. It lists all of the county and candidate votes as well as the winner of the election.
## Summary
The python code that I created both efficiently and accurately analyzed the senatorial election in Colorado. I believe that this code could be used again for other elections, but it would likely need to be modified for elections that aren't of the exact same type. For instance, a local election committe may want to use this to find the outcome for a county elected position, but then the county column would not be helpful in that case. Instead, it might be helpful to have another description for where they live, like neighborhoods, zip codes, or cities. Conversely, the code would need to have even more detail on geographic location of a ballot if it was being used for a national election. If we wanted to analyze the presidential election, we would likely want columns for congressional districts, states, and possibly even more information. This would mean that I would need to create more for loops to run through and print the other columns of data. Lastly, if we wanted to use this code for an election that was electing the top 2-3 candidates (like a schoolboard), we would need to adapt the code to find and print the top 3 candidates (instead of just the 1 with the most votes).
