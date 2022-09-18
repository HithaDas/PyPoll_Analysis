# PyPoll_Analysis

A Colorado Board of Elections has requested to complete the election audit of a recent local congressional election.

- Calculate the total number of votes cast.
- Get a complete list of candidates who received votes.
- Calculatae the total number of votes each candidate received.
- Calculate the percentage of votes each candidate won.
- Calculate the amount of votes and percentage per county.
- Calculate the counties with the largest county voter turnouts.
- Determine the winner of the election based on popular vote.

# Resources
Data Source- election_results.csv
Software- Python 3.9.12 Visual Studio Code 1.71.1 (Universal).

# Election-Audit Results
The analysis of the election shows the following findings -

1. There were total of 369,711 votes cast in the election.
2. The counties counted in the election were:
- Jefferson County
- Denver County
- Arapahoe County
3. The county results are as follows-
- Jefferson county received 10.5% of the total votes casted at 38,855 votes cast.
- Denver county received 82.8% of the total votes casted at 306,055 votes cast.
- Arapahoe county received 6.7% of the total votes casted at 24,801 votes cast.
4. The county with the largest voter turnout was -Denver county with 306,055 votes cast, garnering 82.8% of the total votes cast in the whole election.
5. Candidates in this election -Charles Gasper Stockham, Diana DeGette and Raymon Anthony Doane.
6. Candidates results are as follows -
- Charles Gasper Stockham received 23% of the vote and 85,213 number of votes.
- Diana DeGette received 73.8% of the vote and 272,892 number of votes.
- Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
7. Diana DeGette who received 73.8% of the vote and 272,892 number of total votes is the winner of the election.

Screen shot from Terminal-
![Screen Shot 2022-09-18 at 5 15 22 PM](https://user-images.githubusercontent.com/110873947/190933319-43eaff20-6a9c-4575-abdd-82f99d41ba33.png)

Screen shot from output txt file -
![Screen Shot 2022-09-18 at 5 16 17 PM](https://user-images.githubusercontent.com/110873947/190933338-b63a9754-68aa-467d-b4b8-96c6c11a379b.png)


# Election-Audit Summary
The election audit was such a success becuase of Python.
Python is a high-level, general-purpose programming language. Its design philosophy emphasizes code readability with the use of significant indentation. Python is dynamically-typed and garbage-collected. It supports multiple programming paradigms, including structured, object-oriented and functional programming.
In this exercise we first take teh csv file and anakyse it through Python code in visual studio.
The code defines candidate options (Charles, Diana, or Raymon) as a list, and then creates a dictionary where it stores the candidate name as a key and how many votes the candidate receives as a value. It uses this same coding format for counting the votes per county to find the county with the largest voter turnout. Using repeition and decision statements, the script searches for how many candidates received how many votes, percentages, and calculates who won, all while printing out these results to a text file.
This is a very general and useful code that could be used as a template in the future for any future election such as a presidential election/ college elections. If the script was a presidental election instead of a state congressional election, there would need to be a few more datasets analyzed.
ANother use of this code could be in understanding thh demographics of the vote data ( such racial ethincity, age or sex) and/ or extracting performance of parties (democrats, republicans and others).


