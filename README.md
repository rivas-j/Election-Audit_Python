# Election Analysis

## Overview of Election Audit: Explain the purpose of this election audit analysis.

### It's Election season! The local election commission needs our help auditing the results in a quick, efficient manner. Our solution was to build PyPoll, a Python program that will automate the counting process of the audit. The program will certify the numbef of votes cast for each candidate, the winner, and voter turnout per county. We accomplished this by processing a CSV file containing the 369,000 votes with PyPoll, which in turn analyzed the votes and generated a handy text file summarizing the results.


## Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

- PyPoll determined that there were 369,711 total votes cast in this congressional election. We utilized the following for loop to tally the total vote count:
```
 # For each row in the CSV file, add to the total vote count
    for row in reader:
        total_votes = total_votes + 1
```
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
- Which county had the largest number of votes?
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

## Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

