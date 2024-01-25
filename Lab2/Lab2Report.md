# Lab Report 2  
## Part 1
  ChatServer code  
  ![chatservercode](chatservercode.png)  
  1. First add-message
     ![add-message](add-message1.png)
     * The methods in my code that are called are the handleRequest method in the Handler class and the main method in the ChatServer class
     * The relevant arguments to these methods are the URL for the handleRequest method and the main method is the port number; values of relevant fields is "" for message,
       "" for query, and 4000 for port
     * values that got changed from the request is that message is now "jpolitz: Hello\n" and "/add-message?s=<string>&user=<string>" for query
  2. Second add-message
     ![add-message](add-message2.png)
     * The methods in my code that are called are the handleRequest method in the Handler class and the main method in the ChatServer class
     * The relevant arguments to these methods are the URL for the handleRequest method and the main method is the port number; values of relevant fields is "" for message,
       "" for query, and 4000 for port
     * values that got changed from the request is that message is now "jpolitz: Hello\n yash: How are you\n" and "/add-message?s=How are you&user=yash" for query

## Part 2
  1. private key
     ![privatekey](privatekey.png)
  2. public key
     ![publickey](publickey.png)
  3. interaction with ieng6 without password
    ![w/opassword](wopassword.png)

## Part 3
I learned the idea of remote servers from lab in week 2/3. I never thought about how people would remotely access files meant to be kept securely. So this idea of the remote server, with specific people who can access what is within that server is interesting. 
