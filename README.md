# Module-4-Challenge School District Analysis
# Overview of Project #
The purpose of this Project is to analyze the School district's report to determine the academic dishonesty of grades for 9th Grade Students of Thomas High School, for Maths and Reading Scores. We are going to determine this by replacing the Maths and Reading Score for the above with averages from Grade 10-12. We will then compare this with the initial unmodified results. 

The analysis required the following data to be presented:
1. To replace the math scores and reading scores with NaN of Ninth grade for Thomas High School.
2. Recreate the following metrics:
  - The district summary.
  - The school summary.
  - The top 5 and bottom 5 performing schools, based on the overall passing rate.
  - The average math score for each grade level from each school.
  - The average reading score for each grade level from each school.
  - The average reading score for each grade level from each school.

# Resources #
Data Source: students_complete.csv, schools_complete.csv  <br>
Software: Python, Anaconda, Jupyter Notebook <br>
Library Modules: Pandas, Numpy

# Results #
The analysis of the School_District_Analysis shows that:
1. Replace the 9th grade reading and math scores at Thomas High School with NaN
  - The data is replace by NaN's for only 9th grade and the entire data is intact.
![PythonCode](/Screenshots/StudentData.png)
<br><br>

1. District Summary
- The county results were:
  - Jefferson County received a total of 38,855 votes, which accounts for 10.5% of the total votes. 
  - Denver county received a total of 306,055 votes, which accounts for 82.8% of the total votes. 
  - Arapahoe county received a total of 24,801 votes, which accounts for 6.7% of the total votes.

- The county with the largest voter turnout was: Denver 

- The candidates results were:
  - Charles Casper Stockham received a total of 85,213 votes, which accunts for 23% of the total votes.
  - Diana DeGette received a total of 272,892 votes, which accounts for 73.8% of the total votes.
  - Raymon Anthony Doane received a total of 11,606 votes, which accounts for 3.1% of the total votes.

- The winner of the election was:
  - Diana DeGette, who received a total of 272,892 votes, which is 73.8% of the total votes.

- The Screenshots for the console and text file are given below:<br>
![PythonCode](/Screenshots/ElectionResultsConsole.png)
![PythonCode](/Screenshots/ElectionResultsText.png)
<br>

# Election Audit Summary #
## Script Usage ##
The script uses the data from the file "election_results.csv". The script can be reused for any other elections, provided the following is changed:
1. The Data File: The "file_to_load" variable stores the path and filename of the data file. This must be changed in order to reuse the script.
2. The Output File: The "file_to_save" variable stores the path and filename of the output/result file. This can be changed to store the output elsewhere. 

![PythonCode](/Screenshots/PythonCode.png)
<br>

## Script for Other Scenarious ##
THe script can also be reused for other types of elections, such as
1. Provincial and Territorial Elections: The script can be reused for such elections, but along with the changes mentioned above, the text fields will also need to be updated (i.e. Country text must be replaced by Provincial).
2. Process of Bill Passing: The script can also be used for voting on certain Bills in the parliment. Again the text fields will need to be modified to accomodate this. 

# Further Analysis #
## Code Enhancement ##
1. The code can be enhanced so that the Data Source File (i.e. "file_to_load") and the Output File Location (i.e. "file_to_save") are read from the user on execution (i.e. by using the "input()" python function).
2. Error handling can be introduced so that the code checks for a valid Data Source File (i.e. "file_to_load") and for a valid Output File Location (i.e. "file_to_save").

## Additional Analyzation ##
1. Graphs can be created to analyze the relation between the total number of voters and the outcome.
2. The script does not detect duplicate votes (i.e. duplicate voting ID, which should not be allowed).
3. It appears that the Denver Country had an impact on the overall votes, and thereby contributing to Diana's Win.

![CountryVOtes](/Screenshots/TotalVotesByCountry.png)
![CandidateVotes](/Screenshots/TotalVotesByCandidate.png)
<br>
