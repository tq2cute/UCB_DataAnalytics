# Module 3

# 1.

###a.
##### Candidate Results:

Charles Casper Stockham: 23.0% (85,213)

Diana DeGette: 73.8% (272,892)

Raymon Anthony Doane: 3.1% (11,606)

###b.
##### County Votes:

Jefferson: 10.5% (38,855)

Denver: 82.8% (306,055)

Arapahoe: 6.7% (24,801)

# 2.
See the text file election_analysis.txt in the folder "analysis"

# 3.

###a.  The purpose 
The purpose of this election audit is the making sure the number of votes are accounted in both the counties and candidates.  The sum of votes in the counties should be equal to the sum of votes each candidate receives.

###b.  Election Audit Results:

** County Votes:

* Jefferson: 10.5% (38,855)
* Denver: 82.8% (306,055)
* Arapahoe: 6.7% (24,801)


** County Summary

* Largest County: Denver
* Largest County Vote: 306,055
* Largest County Percentage: 82.8%


** Candidate Results

* Charles Casper Stockham: 23.0% (85,213)
* Diana DeGette: 73.8% (272,892)
* Raymon Anthony Doane: 3.1% (11,606)


** WINNER

* Winner: Diana DeGette
* Winning Vote Count: 272,892
* Winning Percentage: 73.8%


###c.  Summary
This particular script is useful to check the sum votes between the counties and candidates. If all the numbers are matched with each other, then it readily show who is the winner at ease.

This script and be used for other election as well.  There are a few modification one needs to do: first define the right path for file_to_load and file_to_save, second specify the proper column for the list candidate_name = row[2], and third to provide the correct column for the list county_name = row[1]
