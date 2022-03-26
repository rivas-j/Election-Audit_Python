# Election Analysis

## Overview of Election Audit

### It's Election season! The local election commission needs our help auditing the results in a quick, efficient manner. Our solution is PyPoll, a Python program that automates the counting process of the audit. This program certifies the numbef of votes cast for each candidate, the winning candidate, and voter turnout per county. We're achieving this with PyPoll by processing a CSV file containing the 369,000 votes, analyzing the votes and generating a handy text file summarizing the results.


## Election-Audit Results

- PyPoll determined that there were 369,711 total votes cast in this congressional election. We utilized the following for loop to tally the total vote count:
```
 # For each row in the CSV file, add to the total vote count
    for row in reader:
        total_votes = total_votes + 1
```
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
![County Summary](https://github.com/rivas-j/election_analysis/blob/9ae7d85de56693a115af3cb4209bd23b02d6cc5b/Resources/County_Summary.png)
- Which county had the largest number of votes?
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
![Election Results](https://github.com/rivas-j/election_analysis/blob/9ae7d85de56693a115af3cb4209bd23b02d6cc5b/Resources/Election_Results.png)
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
![Election Winner](https://github.com/rivas-j/election_analysis/blob/9ae7d85de56693a115af3cb4209bd23b02d6cc5b/Resources/Election_Winner.png)

## Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

