# -Socket_Programming
This C++ program demonstrates a basic client-server communication model using TCP sockets. The server initializes a socket, binds it to a specific port, listens for incoming connections, and accepts a client. The client connects using the server’s IP and port. Both exchange serialized string data bidirectionally in a continuous message loop.

###### Compilation

For compilation, run:

```bash
g++ server.cpp -o server
g++ client.cpp -o client
```


###### Execution

For Execution, run:

```
On Server side:
./server

On client side:
./client
```
