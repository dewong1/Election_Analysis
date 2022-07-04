# Election_Analysis
Performing analysis on Election data to determine Election Results 


## Overview of Election Audit 

Given an Excel dataspreadsheet with Colorado election results, the purpose of this election audit analysis was to create a Python script that will deliver the following information when the script is run: 1) *Total number of votes cast*, 2) *Complete list of candidates who received votes*, 3) *Total number of votes each candidate recevied*, 4) *Percentage of votes each candidate won*, and 5) *The winner of the election based on popular vote*. The Excel dataspreadsheet included three columns: Ballot ID, County (Jefferson, Denver, & Arapahoe), and Candidate (Charles Casper Stockham, Diana DeGette, & Raymon Anthony Doane).


## Election-Audit Results 

Below is a screenshot of the Election Results (in Visual Studio Code terminal):

<img width="270" alt="election_results (cropped)" src="https://user-images.githubusercontent.com/107021231/177129529-39c6c4ce-f1ff-4c3f-9c5a-ae55a6231463.png">

* There were a total of 369,711 votes cast in this congressional election.

* For the county Jefferson, there were a total of 38,855 votes (10.5% of total votes);
  For the county Denver, there were a total of 306,055 votes (82.8% of total votes);
  For the county Arapahoe, there were a total of 24,801 votes (6.7& of total votes).
  
* The county with the largest number of votes were Denver. 

* For the candidate Charles Casper Stockham, there were a total of 85,213 votes (23.0% of total votes);
  For the candidate Diana DeGette, there were a total of 272,892 votes (73.8% of total votes);
  For the candidate Raymon Anthony Doane, there were a total of 11,606 votes (3.1% of total votes).
  
* The candidate that won the election was Diana DeGette, with a winning vote count of 272,892, and winning percentage of 73.9% of total votes.



## Election-Audit Summary 

The Python script (for this Colorado Election Analysis) --with some modifications-- can be used for any election. The first modification is applied to the coding where you *Add a variable to load a file from a path* & *Add a variable to save the file to a path*:

<sub> *Add a variable to load a file from a path*.
  
<sub> file_to_load = os.path.join("Resources/election_results.csv")
  
<sub> *Add a variable to save the file to a path*.
  
<sub> file_to_save = os.path.join("analysis", "election_results.txt") </sub>
  

Input the new Election data accordingly in the Visual Studio Code so you are gathering data from the correct data source and having the results be printed in a new .txt file. If given similar data from this Colorado Election Analysis (e.g. Ballot ID, County, Candidate), this script will be able to deliver the same eleciton results from the new data (e.g. total number of votes, total number of votes from each county, total number of votes each candidate received, percentage of votes each candidate won, the winner of the election). 
  
If there is additional data provided (e.g. *demographics*) other than *candidate* and *county*, the script can be modified to include the additional variables. Below is an example of the Python Code for *candidate* and *county*. The additional data (based on any new data that you want or need) can be added to the script by using the same format below. 
  
<sub> *Candidate Options and candidate votes*.
  
<sub> candidate_options = [  ]
  
<sub> candidate_votes = {  } 

<sub> *Create a county list and county votes dictionary*.
  
<sub> county_options = [  ]
  
<sub> county_votes = {  } 



