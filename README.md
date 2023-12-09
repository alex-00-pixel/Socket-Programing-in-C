# Introduction
This repository contains a simple implementation of client-server socket programming in C using both TCP and UDP protocols. The code is divided into four main files: `TCP-client.c`, `TCP-server.c`, `UDP-client.c`, and `UDP-server.c`. These programs demonstrate basic communication between a client and a server using the Transmission Control Protocol (TCP) and User Datagram Protocol (UDP).

# Usage
The provided code serves as a starting point for understanding socket programming in C. You can use these programs as a foundation for developing more complex network applications or as a learning resource for understanding the fundamentals of client-server communication.

# Files
1. **TCP-client.c**: This file contains the source code for the TCP client. It establishes a connection with the TCP server, sends data, and receives responses.

2. **TCP-server.c**: This file contains the source code for the TCP server. It listens for incoming connections, receives data from clients, processes requests, and sends back responses.

3. **UDP-client.c**: This file contains the source code for the UDP client. It sends datagrams to the UDP server and receives responses.

4. **UDP-server.c**: This file contains the source code for the UDP server. It listens for incoming datagrams, processes requests, and sends back responses.

# Compile and Run
To compile the programs, use the following commands:

For TCP programs:
`
gcc TCP-client.c -o TCP-client

gcc TCP-server.c -o TCP-server
`

For UDP programs:
`
gcc UDP-client.c -o UDP-client

gcc UDP-server.c -o UDP-server
`
To run the compiled programs, execute the following commands:

For TCP programs:
 `./TCP-server
 
./TCP-client`

For UDP programs:
`
./UDP-server

./UDP-client
`
Make sure to run the server before the client for proper communication.

Note: Replace gcc with your preferred C compiler if you are not using GCC.
