Shanty Kamal	30032616

Unzip hw4.zip 
Navigate to HW4Init/src
Compile the following classes using the following command:
javac Edge.java EdgeComparator.java HW4.java
Then, run the class HW4:
java HW4 <option> <path to maze.txt> <path to query.txt>

1st command line argument: option can either be:
	weighted          (calls Dijkstra's)
	unweighted        (calls BFS)

The second and third command line arguments must correspond to maze and query text files, in that order. (Format of these files are assumed to be in agreement with what was specified in the assignment.)

