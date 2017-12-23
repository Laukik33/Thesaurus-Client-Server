# Thesaurus-Client-Server

***DEVELOPMENT TOOLS:

1) Programming Language: Java (jdk 1.5 and above)
2) IDE: Netbeans 7.4
3) MS Access Database
4) OS: Windows 7.

***DEVELOPMENT OF THESAURUS:

1) Socket programming is used for client server programming.
2) Server runs at port number 18888.
3) MS Access database has been developed and connected to it using JDBC.

***IMPLEMENTATIONS:

1) Client and server processes successfully connect.
2) Client Process and its GUI work as specified.
3) Server Process works correctly.
4) Server GUI shows incoming client messages.
5) Server works correctly with messages from multiple clients.
6) Availability of test data
6) Server maintains connections after each response.
7) Comments and headers for all functions/methods in code.

***DIRECTORY STRUCTURE

1) src folder contains files for thesaurus client server implementation
  a) Client source file for client's implementation
  
  b) Server source file for server's implementation

2) MS Access database file that contains the database of words and their synonyms


***STEPS TO COMPILE AND RUN THE PROGRAM

In the Zip folder Thesaurus is the project folder to be imported into Netbeans to
test the application. 

1) Clean and Build Server.java file. Run the Server.java to run the server.
2) Clean and Build Client.java file. Run the Client.java to run the client.
3) Clean and Build Client2.java file. Run the Client2.java to run the second client.
Note: Running the client without running the server results into error that is displayed to the Client.

***TESTING THE PROGRAM

1) Enter the text in client GUI.
2) Selecting a word in the text block and clicking on 'Get Synonyms' button would result in synonyms of 
   the word in the text area below the 'Get Synonyms' button if the word has an entry in database otherwise
   error pops up saying 'Word not found'
3) Entering nothing in Client GUI and clicking Get Synonyms would result in the same error that is displayed 
   to the client below the exit button.
4) Once the get synonyms button is clicked the area where the word is entered gets reset for the client 
   to enter a new word. 
5) The word that is entered in the Client is displayed in the server. 
6) Clicking on the Exit button would result in the frame being closed.

***TEST DATA

The application displays synonms for the below set of words

abate             decrease, diminish, dull, swindle, ebb, recede, slacken
perigee           path, pattern, trajectory, course, ellipse, round,path, pattern, trajectory, course, ellipse, round
charming          delightful, pleasing, pleasant, appealing, attractive, alluring, endearing, fascinating, likable
ambivalent        equivocal, uncertain, unsure, doubtful, indecisive, irresolute, undecided, inconclusive
cogent            compelling, convincing, apt, fitting, inducing, persuasive, weighty, consequential, justified
diverge           veer, stray, radiate, deviate, bifurcate, branch, divide, part, separate, split, divagate
luminous          radiant, lustrous, shining, vivid, beaming, lambent, effulgent, lucid, crystal, lit, lucent
homogenous        akin, alike, analogous, cognate, identical, kindred, uniform, unvarying, consistent, like

***RESTICTIONS

The application contains only eight words which are inserted in the database. The server is not multithreaded 
and can serve one client at one time.

***REFERENCES

1)Lab document available on Course Materials section of 2178-CSE-5306-003-DISTRIBUTED SYSTEMS--2017-FALL class on the UTA.
2)Lesson 1: Socket Communications, www.oracle.com/technetwork/java/socket-140484.html.
3)Dubey, Abhishek. “JDBC Connection to MS-Access in Windows 7.” C# Corner, www.c-sharpcorner.com/UploadFile/433c33/jdbc-connection-to-ms-access/.
4)Book: Computer Networking. A Top Down Approach. Fifth Edition by James F. Kurose, Keith W. Ross. Chapter 2.
5)“Socket Programming in Java.” GeeksforGeeks, 16 May 2017, www.geeksforgeeks.org/socket-programming-in-java/.
6)JDBC - Example with Access.” Tutorials, www.java-tutorial.com/java-tutorial/jdbc-tutorial/jdbc-example-access/.
