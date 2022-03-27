## Election_Analysis: Module 3 Python

# Analysis of the Election Audit

## Overview of Election Audit: Explain the purpose of this election audit analysis.
Employees of the Colorado Board of Elections have requested us to prepare an Election Results Audit for a Congressional Election. Voting data included Ballot ID, Candidate, and County in a Comma Separated Value (CSV) file. There were three candidates in the congressional district with 3 counties. 

We were asked to do the analysis for counting votes and percentages that each candidate received, the total votes cast in the election, and to declare the winner of the election. In addition, our task included providing the voter turnout for each county, the percentage of votes from each county out of the total count, the county with the highest turnout. 

For this election audit, a python code (PyPoll_Challenge.py: [(Python Code)](PyPoll_Challenge.py) was generated. Python 3.7 and VS Code (for editing and testing) was used. Votes for candidates and counties were calculated by using loop counters. Lists and dictionaries (used to add data. Variables were initialized and the data were analyzed using decision statements, memberships and logical operators, and repetition statements to iterate through la ist or a dictionary. Finally the code was executed for printing the results to the terminal and to a text file. The csv file was imported into python and The code and other files were uploaded to GitHuub. Software used: Python 3.9.7. VS Code 1.65.2, Git.


## Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

The Figure 1 below shows the results of the voting of the Colorado Congressional district (printed to the terminal). 

  ![Winner](/resources/ElectionResults.png)
   
  ## Figure 1. Final vote results of Colorado Congressional Vote (screen shot of the terminal)
  
  The link to the text file: [Election Results](/resources/election_analysis.txt)
  
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
  
    - Charles Casper Stockham: 85,213 (23.0%) 
  
    - Diana DeGette: 272,892 (73.8%)
  
    - Raymon Anthony Doane: 11,606 (3.1%)
  
      (See Figure 1 or text file)

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  
    - Winner: Diana DeGette
  
    - Winning Vote Count: 272,892
  
    - Winning Percentage: 73.8%
  
      (See Figure 1 or text file)

- Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

An election audit was performed using a python script to find a winner for a congressional disctrict of Colorado. There were three candidates: Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane contested for the district. The winner of the election can be declared as Diana DeGette with 73.8% the total votes. The largest voter turnout was in the Denver county.

Business proposal: This Python script was written for Election-Audit for the congressional district. This script can be extended to include Election-Audit for any elections in Colorado with additional modifications.

Example 1.
Adding additional visualization: Pie Chart, Bar graph)

Example 2. 
Defining and including functions for each calculation and printing
For example, calculation for county can be one function and calculating candidate results can be another function 


***Additional information***
Some important parts of the code. 

 - code for File import and Intializing variables:
 
![Election Results-code](/resources/Initializing.png)

- code for counting votes:
      
![Election Results-code](/resources/Code_Counting_Votes.png)

- code for printing results:
- 
![Election Results](/resources/Code-Election-Results.png)
