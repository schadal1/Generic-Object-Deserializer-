# Generic-Object-Deserializer-
Implemented reflections for deserializing objects of First and Second classes.

FILES:
Chadalla_Sumanth_assign5
   ---genericDeser
     ----- README.txt
     ----- build.xml
     ----- input.txt 
     ----- src
       ---genericDeser
     	   ----------driver
	        	   ----------Driver
           ----------util
	              ----------First.java
	              ----------Second.java
	              ----------PopulateObjects.java
           ----------fileOperations
	              ----------FileProcessor.java
           ----------logger
		      ----------Logger.java
***************************************************
SAMPLE OUTPUT:

Number of unique First objects: 359994
Total Number of First objects: 498623
Number of unique Second objects: 100643
Total Number of Second objects: 501377

***************************************************
TO COMPILE:

ant

NOTE: Please put the Input file where the source file is there in directory.

TO RUN:
Please go to the directory where build.xml is present and run 

ant -Darg0=input.txt -Darg1=0

-Darg0 : takes any .txt file inside the project folder as input
-Darg1 : takes a value between 0 and 2
	0 - Prints final output
	1 - Prints all object comparisons
        2 - Prints all Duplication detections

To CLEAN:
ant clean

Data Structure Used:
***************************************************
I am using HashMap Data Structure.
I am using this beccause add and retrieve takes only O(1) time to execute. 
And is very easy to handle and use.

Time Complexity is O(n), where n is the total number of lines in the file.			   
			   
***************************************************			  

EXTRA CREDIT:

N/A


