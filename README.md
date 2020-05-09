# RockPaperScissors
*Rock / paper / scissors game that works with Client-Server logic in Java language.*

ANKARA UNIVERSITY - COMPUTER ENGINEERING DEPARTMENT<br>
BLM/COM334 - OPERATING SYSTEM - ASSIGNMENT 2

### Description of Homework

I write a rock / paper / scissors game that works with Client-Server logic in Java language.<br>
My client program sends the rock / paper / scissors value from the user to the server. <br>
The statement of won / lost / draw will be sent to the Client by comparing the data received with the randomly generated value on the server.<br>
The server program waits for any client connection to be established with the accept () method. When client connection is established:

### Working Principle

1. CLIENT Gets the statement of rock / paper / scissors from the user
2. CLIENT Sends the data to SERVER using socket.
3. SERVER Reads the data from the socket and prints its contents on the screen.
4. SERVER Generates a Random variable and prints it on the screen.
5. SERVER Compare the values (SERVER -> random vs Client -> user input).
6. SERVER Prints the result statement (win / lost / draw) on the screen.
7. SERVER Sends the result statement to the Client.
8. CLIENT Prints the result statement on the screen.

### Requirements

> Ubuntu OS <br>
> java

### Build & Run

You should use two terminal,one is for server the other one for client.<br><br>

![OS](https://user-images.githubusercontent.com/50207648/81470931-5dce3980-91f6-11ea-9c6e-47627aaf8c77.png)
    
