# P2P Chat App
#### A simple to use chat program that uses sockets and multi-threading

EC530 p2p chat in python (also supports client server chat)
## 1. Getting started
Start the server using 
```sh
$ python Server.py
````
The clients can connect to the server through client.py
```sh
$ python Client.py
````
---
The p2p version can be started using the command
```sh
$ python p2p.py
````
----
Alternatively, it can be run from the terminal itself. 
####1. Make the files executable
```sh
$chmod u+x Server.py Client.py p2p.py
````
####2. Run the program
````sh
$ ./Server.py
````
````sh
$ ./Client.py
````
````sh
$ ./p2p.py
````
----
Client will ask for the hostname and the port on which the server is listening, then attepts to connect to the server. If connection is successful, client should prompt you to start typing messages. Else an exception is thrown.
