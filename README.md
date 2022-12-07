# Assignment
Create a random integer generator.  The method takes two ints: the low value for the random number and the high value for the random number

Create a method that does a rudmentary statistical analysis of the random number generator.  It should make a count of how many times each number comes up (using an array) and calculate the average of all the values generated.  If a number outside of the desired range is generated, it should print something that describes the failure instead of the stats.

While you're welcome to ask questions and discuss how to do this, you should be working towards independence.  Think about each part on your own first, try to write code yourself, try to debug on your own.  
There is no requirement for main().  That stub was created for your convenience.  

This tool will allow us to get a sense for if the numbers being generated are evenly distributed.  However, we know that the numbers generated aren't truely random (only psuedorandom), and it would probably take a deeper statistical analysis to decide if the random number generate works 'well'.  

# Grading - 9 points total
randomInt works properly (1 pt)  
randomIntAnalyzer counts values properly (2 pts)  
randomIntAnalyzer averages values properly (1 pt)  
randomIntAnalyzer output shows more thought than the example below (1 pt)  
Commits (4 pts)  
* There should be at least 2 commits per day (probably more)
* Commit messages should appropriately describe the changes that were made since the last commit.
* If the commit message gets too long, you probably should have made another commit earlier
* Each time you run the program, you should commit first, with a message that reflects what you're looking for. 
* All commits should be pushed to Github at the end of each class

# Example
Call: randomIntAnalyzer(3,4,1000)  
Output:  
The number 4 showed up 455 times and the number 3 showed up 545 times for an average of 3.455.
