Project Description:
TCP (Transmission Control Protocol) is a standard that defines how to establish and maintain a network conversation through which application programs can exchange data. TCP works with the Internet Protocol (IP), which defines how computers send packets of data to each other.This project implements the TCP Protocol using Dijkstra's algorithm to determine the shortest path betweent the clients.


Instructions to run:
1.	Open the folder containing the code in a Linux environment, if preferable.
2.	Open terminal pointing to the said folder. 
3.	Run the "missiontcp.server.py" file on the terminal.
4.	Repeat step 2 and run the "ann.py", "jan.py" & "chan.py" files from different terminals.
5.	Allow the three-way handshake to happen for all clients.
6.	By default, port numbers for Ann, Jan and Chan are 2001, 2002, 2003 respectively.
7.	Pick a client, say Ann, and provide the file you want to send by specifying the path to file and provide the destination client port number, say Jan, and press enter.
8.	The Dijkstra's algorithm determines the shortest path between the clients over the network and sends the file.
9.	File is received by the client, in this case Jan.
10.	Connection is terminated.
