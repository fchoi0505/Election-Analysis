# Election Analysis

## Overview of Election Audit:

Use of Python code to analyze election votes cast to determine election results for a precinct of interest.

### Purpose:

Using Python code to read and analyze election voting data collected, we are able to quickly process over 360,000 votes cast to determine election winners and voting number breakdowns, such as votes by county and per candidate for the precinct of interest.

## Summary of Election Outcomes

### County Outcomes
For the counties included in this voting data set, 369,711 total votes were cast in this congressional election.

The three counties included in the precint, Jefferson, Denver, and Arapahoe, have the following vote breakdown:

* Jefferson County accounted for 38,855 votes or 10.5% of the total precinct votes
* Denver County accounted for 306,055 votes or 82.2% of the total precinct votes
* Arapahoe County accounted for 24,801 votes or 6.7% of the total precinct votes

With 82.2% of the total precinct votes, Denver County had the largest voter turnout in this precint.

### Candidate Outcomes
For the three candidates included in the precint, Charles Stockham, Diana DeGette, and Raymon Doane, the votes tallied as follows:

* Charles Stockham received 85,213 votes or 23% of the total precinct votes
* Diana DeGette received 272,892 votes or 73.8% of the total precinct votes
* Raymon Doane received 11,606 votes or 3.1% of the total precinct votes

Diana DeGette, with 272,892 votes, is the winning candidate receiving 73.8% of the total precinct votes.

!{} (images/election_results.png)

### Election Audit Summary

Reading and analyzing the voting records using Python code enabled quickly processing a large volume of data and executing configured calculations for the analysis to determine voting results and additional detailed voting breakdowns.

Performing these activities using code also allows data reading and analysis to be easily and repeatedly executed providing  latest results as voting progresses (near real-time) rather than having to wait until all votes have been cast for only final results.  

Modifying the code to create a user friendly front end interface opens up the capability for anyone to execute the code without need for particular expertise and receive consistent result types.  Additionally code can be expanded to process multiple precincts (additional counties and candidates).  Adding a county to precint link will allow for futher vote result breakdowns such as number of counties in the precint, voter turnout by precint (not only by county), and largest precinct turnout for the state.
