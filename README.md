# Web Sockets
Socket programming, way of connecting two nodes on a network to communicate with each other. One socket(node) listens on a particular port at an IP, while other socket reaches out to the other to form a connection. Server forms the listener socket while client reaches out to the server.
# Get Started
## Requirements
No external libraries are needed to build this extension.

## Installation
The socket functions described here are part of an extension to PHP which must be enabled at compile time by giving the --enable-sockets option to configure.

## Runtime Configuration
This extension has no configuration directives defined in php.ini.

## Resource Types
    1) socket_accept(), 
    2) socket_create_listen() and 
    3) socket_create() 

    -all the above inbuilt methods types return socket resources.
