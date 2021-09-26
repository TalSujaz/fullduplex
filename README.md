# fullduplex
Client and server full duplex communication system.The client and the server can communicate simultaneously. 
The client can send a message to the server at any time and so is the server.

* The project is based on client and a server that are connected with the same socket (port number: 3333 because he is available).
* This project uses UTF to code different length of chars in unicode.  So we could code the strings coming from the server and the client.
* The dout.flush() function takes the information form our output stream and sends it immediately to the destination.
