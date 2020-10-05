# PythonPortScannerOverview
__________    _____  __    ________ ________   
\______   \  /  |  ||  | __\_____  \\______ \  
 |    |  _/ /   |  ||  |/ /  _(__  < |    |  \ 
 |    |   \/    ^   /    <  /       \|    `   \
 |______  /\____   ||__|_ \/______  /_______  /
        \/      |__|     \/       \/        \/ 
This post will show how you can make a small and easy-to-use port scanner program written in Python. There are many ways of doing this with Python, and I’m going to do it using the built-in module Socket.
Sockets

The socket module in Python provides access to the BSD socket interface. It includes the socket class, for handling the actual data channel, and functions for network-related tasks such as converting a server’s name to an address and formatting data to be sent across the network.

Source Sockets are widely used on the Internet, as they are behind any kind of network communications done by your computer.

The INET sockets, account for at least 99% of the sockets in use. The web browser’s that you use opens a socket and connects to the web server.

Any network communication goes through a socket.



Disclaimer

This program is intended for individuals to test their own equipment for weak security, and the author will take no responsibility if it is put to any other use
__________    _____  __    ________ ________   
\______   \  /  |  ||  | __\_____  \\______ \  
 |    |  _/ /   |  ||  |/ /  _(__  < |    |  \ 
 |    |   \/    ^   /    <  /       \|    `   \
 |______  /\____   ||__|_ \/______  /_______  /
        \/      |__|     \/       \/        \/ 
