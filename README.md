# Networks-Scapy-TCP-Client
In this assignment, you will simulate a TCP client using scapy instead of the socket library. Scapy is a python library that can be used for creating network packets.

Question 1: Simulating a TCP client
You will create a TCP client using scapy that performs the following steps:
1. Initiate a connection to the TCP server using TCP 3 way connection establishment hand-
shake.
2. Read 1 line of data from server.
3. Send the SHA256 hash of the server data(in hexadecimal format) terminated by a newline.
4. Complete the 4 way TCP connection termination handshake initiated by the server.
