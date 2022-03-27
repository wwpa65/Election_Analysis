## Election_Analysis: Module 3 Python

# Analysis of the Election Audit

## Overview of Election Audit: Explain the purpose of this election audit analysis.
Employees of the Colorado Board of Elections have requested us to prepare an Election Results Audit for the Congressional Elections. Voting data included Ballot ID, Candidate, and County in a Comma Separated Value (CSV) file.

We were asked to do the analysis for counting votes and percentages that each candidate received, the total votes cast in the election, and to declare the winner of the election. In addition, our task included providing the voter turnout for each county, the percentage of votes from each county out of the total count, the county with the highest turnout. 

For this election audit, a python code (PyPoll_Challenge.py: [(Python Code)](PyPoll_Challenge.py) was generated. Python 3.7 and VS Code (for editing and testing) was used. Votes for candidates and counted were calculated by using loop counters. Lists and dictionaries (used to add data. Variables were initialized and the data were analyzed using decision statements, memberships and logical operators, and repetition statements to iterate through la ist or a dictionary. Finally the code was executed for printing the results to the terminal and to a text file. The csv file was imported into python and The code and other files were uploaded to GitHuub. Software used: Python 3.9.7. VS Code 1.65.2, Git tools


## Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

- How many votes were cast in this congressional election?
    - There were 369,711 votes cast in the Colorado congressional election.
  
      (See Figure 1 or text file)

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct. 
  
    - Jefferson: 10.5% (38,855)
  
    - Denver: 82.8% (306,055)
  
    - Arapahoe: 6.7% (24,801)
    
      (See Figure 1 or text file)

- Which county had the largest number of votes?

    - Denver county had the largest number of votes with 306,055 (82.8% of total votes)
  
      (See Figure 1 or text file)

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  
    - Charles Casper Stockham: 23.0% (85,213)
  
    - Diana DeGette: 73.8% (272,892)
  
    - Raymon Anthony Doane: 3.1% (11,606)
  
      (See Figure 1 or text file)

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  
    - Winner: Diana DeGette
  
    - Winning Vote Count: 272,892
  
    - Winning Percentage: 73.8%
  
      (See Figure 1 or text file)
  
  ![VElection Results](/resources/ElectionResults.png)
  
  ## Figure 1. Final vote results of Colorado Congressional Vote (screen shot of the terminal)
 
  ### Link to the text file: [Election Results (text file)](/resources/election_analysis.txt)

- Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.
