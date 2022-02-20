# Election Analysis

## Project Overview

A Colorado Board of Elections employee has given us the following tasks that need to be completed for the election audit of a recent local congressional election.

1. Total number of votes cast
2. The voter turnout for each county
3. County with the highest turnout
4. A complete list of candidates who received votes
5. Total number of votes each candidate received
6. Percentage of votes each candidate won
7. The winner of the election based on popular vote

## Resources

* Data source: election_results.csv
* Software: Python 3.7.10, Visual Studio 1.59

## Results
The analysis of the election results shows that:

* There were 369,711 votes cast
* The voter turnout for each county was:
	* Jefferson had 38,855 voters which was 10.5% of all the voters
	* Denver had 306,055 voters which was 82.8% of all the voters
	* Arapahoe had 24,801 voters which was 6.7% of all the voters
* The county with the largest voter turnout:
	* Denver
* The three candidates were
	* Charles Casper Stockham
	* Diana Degetter
	* Raymon Anthony Doane
* The candidate results were:
	* Charles Casper Stockham received 23.0% of the vote and 85,213 votes
	* Diana DeGette received 73.8% of the vote and 272,892 votes
	* Raymon Anthony Doane received 3.1% of the vote and 11,606 votes
* The winner of the election was:
	* Diana DeGette who received 73.8% of the vote and 272,892 votes

In addition to the above recap below is the print screen of the results from the terminal and here is a link to results in the [election analysis.txt](https://github.com/timbialek/Election_Analysis/blob/main/Resources/Election_Results_Text.PNG)
![](https://github.com/timbialek/Election_Analysis/blob/main/Resources/Election_Results_Terminal.PNG) 

## Summary

>The code used to calculate the election results can be used in any election or to even gather more data from the already existing file with just a few modifications.  For example, in the already existing file we could add some additional coding to see the results for each candidate in each of the counties. Furthermore, if we added town to the file, we could write some additional coding to provide results by county and town which would help the candidates to focus their campaigning.   Since this script is very scalable if can really be used to calculate votes for any kind of election from as large as a nationwide election by state or even as small as a local school board election.
