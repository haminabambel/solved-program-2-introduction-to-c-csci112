Download Link: https://assignmentchef.com/product/solved-program-2-introduction-to-c-csci112
<br>
<h1>Objectives</h1>

<ul>

 <li>Practice reading from and writing to files.</li>

 <li>Practice using data structures.</li>

 <li>Learn to work in a team</li>

</ul>




Description:




Using the same team you had for program 1, create a program that reads in a list of CSCI classes from a file (must use file pointers).  Store the list in a data structure.  Allow the user (a student) to have the following options:




<ul>

 <li>Print all classes by CSCI number (include all information) in order of CSCI number.</li>

 <li>Print all classes available on MWF or available on TR in order of times.</li>

 <li>Print the class available at a specific time (test this with MWF 0900 and TR 1100)</li>

 <li>Print classes available to freshman, sophomore, junior or senior (corresponds to last number on each line in the input file) in order of CSCI number. This means you have to convert back and forth between the strings (freshman, …) and the numbers (1,2, …).</li>

 <li>Quit</li>

</ul>




All output will be written to a file (must use file pointers).




Requirements:




You must use the input file in /home/csci112 called classes.txt to input the data.




You must provide the options to the user on the screen as shown above in description.




You must write all information asked for by the user to an output file.  This means that you will need to interact with the user (asking for options) by printing to STDOUT but print all the responses to the queries to a file.




To print class information, print in the following order:

Title, Class number (ex: CSCI112), available for (freshman, soph…), day, time.




You must loop on user queries until the user selects the quit option.

You must exit with a failure if any error is found in user input.




Place each function or group of functions in a separate file (.c) and have a Makefile that compiles all your code together to make the executable.  A group of functions means that you might have all your print functions in one file, but you would not have the query function in the same file as the print functions.





