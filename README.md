# COMP2001 Artificial Intelligence Methods

<br>Name:YizhengLiu</br>

<br>Student_ID:20291679</br>

<br>Email:psyyl10@nottingham.ac.uk</br>

##To run the application

In order to run this script,
you first need to install a valid Java 17 version,
and set <code>JAVA_HOME</code> after that.
You then need to decompress the zip file,
then open the terminal and go to the directory
where you decompressed it,then go to <code>Coursework\src\com\uon</code>.
then type<code>
javac -d . .\File_reader.java .\Main.java .\Problem.java .\Solution.java</code>
then type<code>java com.uon.Main "Your own arguments"</code>

##Argument setting
You should type the arguments in this order <code>Population size,maximum number of evaluation,innovation rate,number of trials, numberOf and the file name of your problem</code>

<br>Population size should be [0,30] </br>
<br>Maximum number of evaluation should be [0, 5000]</br>
<br>Innovation rate should be [0,1]</br>
<br>number of trials should be [0,25]</br>
<br>numberOf should be bigger than 0</br>

The code will detect if you entered the wrong format of these inputs

