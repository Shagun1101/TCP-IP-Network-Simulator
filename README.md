# TCP-IP-Network-Simulator
The Network Protocol Stacks Simulation is a C++ model that aims to simulate the functionality of
various network layers in the network protocol stacks. The model includes the following layers:
Physical Layer, Data Link Layer, Network Layer, Transport Layer, and Application Layer. This
documentation provides a comprehensive overview of each layer's implementation and the
protocols and functionalities incorporated within them.

## Physical Layer
The Physical Layer is responsible for the creation of end devices and facilitating communication
between them and the hub network. In this simulation, the following features were implemented:</br>

1. End device creation and management
2. Hub network communication mechanisms
## Data Link Layer
The Data Link Layer in the simulation encompasses the implementation of bridges, switches, and
various access control protocols. It also includes flow control (Go-Back-N, Stop and Wait) and error
control (CRC and n-bit Hamming Code) protocols. The key features of the Data Link Layer
implementation are as follows: </br>
1. Bridge and switch functionality
2. Access control mechanisms
3. Go-Back-N and Stop and Wait flow control protocols
4. CRC and n-bit Hamming Code error control protocols
## Network Layer
The Network Layer implementation focuses on routers, routing protocols (OSPF and RIP), routing
tables, and general network topologies. The key features of the Network Layer simulation include:
1. Router creation and management
2. OSPF and RIP routing protocol implementation
3. Routing table management
4. Network topology representation using graphs
5. Shortest path algorithm for route determination
6. Longest mask matching for IP address routing
## Transport Layer
The Transport Layer simulation assigns ephemeral ports and well-known ports to various processes
and incorporates UDP datagrams. It also includes flow control protocols from the Data Link Layer. The
main features of the Transport Layer implementation are:
1. Ephemeral port and well-known port assignment
2. UDP datagram handling 
3. Integration of Data Link Layer flow control protocols
### Note
I have written and compiled this code on sublime text and there are many features that we
have used may not be supported by any other compiler so it is good to run this program on
command prompt.
### Language Used 
C++
### Libraries Used
1. bits/stdc++.h
2. windows.h
### Instructions to proceed
1. First of all compile the code and run it
2. There will be 13 options available for different fuctionalities.
3. Choose the 1 which you want to use and proceed further according to the Instructions
displayed on the Command Prompt or Output Screen.
