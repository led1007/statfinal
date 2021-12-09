# statfinal
This program will determine the winner of two MLB teams if they were placed in a match against each other.

In order to use this program, you must download the mlbdata.csv and the winner.Rdata. 
These two files should be saved in the same folder on your computer and the R directory changed to 
that folder. After the directory is changed, use 

mlbdata <- read.csv("mlbdata.csv", header=T)

attach(mlbdata)

to import the data into R. Then you can upload the function into R and the program is ready for use.

The final model predicts the winner of an MLB matchup, 88% of the time, and uses the two variables, runs 
and ERA.
