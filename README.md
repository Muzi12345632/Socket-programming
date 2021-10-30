# Socket-programming
API to establish connection between server and client,

socket.socket() creates a socket object that supports the context manager type, so you can use it in a with statement. There’s no need to call s.close(),

bind() is used to associate the socket with a specific network interface and port number,

listen() enables a server to accept() connections,

the client is pretty simple. It creates a socket object, connects to the server and calls s.sendall() to send its message,

 Lastly, it calls s.recv() to read the server’s reply and then prints it.
