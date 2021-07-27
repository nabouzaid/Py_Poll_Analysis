# Election Audit Analysis

## Overview of Election Audit
The purpose of this election audit is to extract key figures regarding candidate and county performance from the tabulated results of a Colorado election with automated processes that can be applied to other election results.

## Election-Audit Results

[Election Results terminal screenshot] (Election_Results_Terminal.png)

[Election Results text file] (analysis/election_analysis.txt)

* Votes Cast: 369, 711

* Votes Cast By County:

	* Denver: 306, 055 (82.8%)
	* Jefferson: 38, 855 (10.5%)
	* Arapahoe: 24, 801 (6.7%)

* Denver had the largest number and largest percentage of votes. 

* Votes cast by candidate:

	* Diana DeGette: 272, 892 (73.8%)
	* Charles Casper Stockham: 85, 213 (23.0%)
	* Raymon Anthony Doane: 11, 606 (3.1%)

* Dianna DeGette won the election with 272, 892 votes and 73.8% of the total vote.

## Election-Audit Summary
While these election results tallied votes across two categories (by candidate and county, not including the ballot ID), other elections may use any number of categories (i.e. may elect different candidates for multiple positions). The script could first create a list of categories based on the headers then iterate through the list to create a list of options, calculate total votes, the vote breakdown (percentage and raw number), and the item receiving the largest proportion of votes, as well as print and save the results in a generalized format for each list item as it currently does for candidates and counties. 

