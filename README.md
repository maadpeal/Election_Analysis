# Election_Analysis

## Project Overview

    A Colorado Board of Elections employee has given you the following tasks to complete the election audit of
    a recent local congressional election
    
    1. Calculate the total number of votes cast.
    2. Get a complete list of candidates who received votes.
    3. Calculate the total number of votes each candidate received.
    4. Calculate the percentage of votes each candidate won.
    5. Determinate the winner of the election based on popular vote.
    

### Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1


## Summary
The analysisof the election show that:
- There were "369.711" votes cast in the election
- The candidate were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham: received 23.0% of the vote and (85,213) number of votes.
    - Diana DeGette: received 73.8% of the vote and (272,892) number of votes.
    - Raymon Anthony Doane: received 3.1% of the vote and (11,606) number of votes.
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the voted and 272.892 number of votes.

## Challenge Overview

It seeks to determine the total number of votes by counties this time, to see in this way the scope of the 
participation by county.
    
- County Votes:
    - Jefferson: received 10.5% of the vote and (38855) number of votes.
    - Denver: received 82.8% of the vote and (306055) number of votes.
    - Arapahoe: received 6.7% of the vote and (24801) number of votes.
- Largest County Turnout was Denver with 306055 votes.
    
## Challenge Summary

    Due to the way this script is created like this it can be used for any type of elections involving counties,
    If you want to use for the states you would have to add the state variable, as the United States is a country 
    with collegiate elections then it would be a question of determining by counties and then by state who was
    the winner to count the collegiate votes, in such case determine who is the winning president of an election that you want to review,
    After determining who wins in which states, a process should be created to add the votes by states for a certain trend,
    You should have a dictionary with the number of votes that each state has.
    
    If the modifications are made to calculate the above, very probably little would have to be modified to repeat the same operation
    In the case of governors, in fact it is a less complex level due to the number of votes that would be significantly lower, but
    With the same base structure, some variables should be renamed and the console prints should obviously change.
