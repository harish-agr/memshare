# memshare
A simple Linux IPC library using shared memory | Automatically exported from code.google.com/p/memshare

The communicating processes register to the library with their 'process name'. 
This name is their 'address'. They also registers callback functions for handling 
incoming messages. Now you are set to send messages between any process. 
