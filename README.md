# Election Results

##Purpose

###
The purpose of this challenge is to assist with the election audit of the Colorado US Congressional precinct and provide additional data as requested by the election commission.

##Results

###
The election results were provided in a CSV file. Python code was used to assist with analyzing the data, the following is a summary of key facts. 

  •	There were 369,711 total votes cast in the congressional election. 

  •	Jefferson county received 38,855 votes or 10.5% of total votes, Denver county received 306,055 votes or 82.8% of total votes and Arapahoe county        received 24,801 votes or 6.7% of total votes. 

  To determine the number of votes for each county in the precinct, an “if” statement was used with the membership operator “not in.”  

IMAGE

  •	Denver county had the largest turnout with 306,055 votes. 

  To determine the county with the largest turnout, a for loop and “if” statement were used. 

IMAGE

  •	The winner of the election is candidate Diana DeGette, having received 272,892 votes or 73.8% of total votes. 

  To determine the winning candidate, a for loop and “if” statement were used. 

	IMAGE

Summary

In some elections, the winning candidate is named after having received a majority vote that exceeds a specified threshold, such as 50%. The code can be modified in section 8, such that the “if” statement includes a comparison that the vote_percentage is greater than the specified threshold. 
