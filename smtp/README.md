An Application of Threads and Sockets
--------------------------------------

This is a basic application of sockets and threads.  There is two kind of servers:  1. Single Thread: This server handles all connection in main thread,   therefore all clients need to wait previous clients get job done. 2. MultiThread: This server handles each client with different connection on different threads.  Therefore,all clients do not wait each other.