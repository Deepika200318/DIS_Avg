# DIS_Avg
The server calculates the average of the numbers given by 3 different clients and sends their average to the client which gave the lowest number.

Step 1:
Open the terminal of the file's location and create the exeutable files for the server and client files using the below command

#For server file
 gcc -o server3 server3.c

# Using the same client file, we create 3 different outputs and run them in 3 different teerminals.
---> For client1 file, the command would be:
     gcc -o client1 client2.c
---> For client2 file, the command would be:
     gcc -o client2 client2.c
---> For client3 file, the command would be: 
     gcc -o client3 client2.c
     
Now, all as all the files ran without any error, there created the respective server3 and client1,2,3 executable files in the same folder.

Step 2:
Open four terminals, one for server and remaining for the clients.

Step 3: 
Run the following command to activate the server, create the socket and make it ready to accept the client connections in one of the terminals given for server.
  ./server3

Step 4:
Run the following command to create the respective client sockets in respective client terminals.
  ./client1
  ./client2
  ./cclient3
  
Step 5:
Give the respective numbers as input from respective client terminals.

Output: The average of three numbers is given sent to the client terminal which sent the minimum number among the three clients.

====> ctrl+c -> Terminates the program.
