# Client-Server-Communication

#About
This is made using socket programming in python. Server and client can send and reveive messages from each other.

#Features
-> Allowing communication with trusted client only, check using first received message from client as key message
-> Multithreading to handle multiple clients
-> Use of pickel to serialize any type of data
-> Handling of variable length data by passing payload size along with payload
-> Passing data identifier with payload as additional information to take specific action accordingly (eg. if data identifier is image then save payload as image)
-> Using keyboard interrupt to close client and server cleanly

#Usage
	#1. Server.py
			(Note the Server IP)
			Enter the Port Number for the communication to Start  
			
			python3 server.py
	
	#2. Client.py
			
			python3 client.py 
			
			(Enter the port as entered in Server and IP of the Server)
