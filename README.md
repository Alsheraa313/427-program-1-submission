Student Names and emails:
Mohammed Alsheraa, shewa@umich.edu
Ellette Foucher, efoucher@umich.edu

Introduction:
This project is implemented in C, designed to be cross-platform. The code was developed and tested on both Windows (using Visual Studio) and Linux (using Visual Studio Code), ensuring compatibility across the different operating systems.

Running Instructions or using the Makefile:
gcc chewaTestServer.c -o chewaTestServer -lsqlite3 (for server)
gcc chewaTestClient.c -o chewaTestClient (for client)
./chewaTestServer ./chewaTestClient
For linux ssh terminal as shown in the video: gcc chewaTestServer.c sqlite3.c -o chewaTestServer -lpthread -ldl (the rest is the same)

<img width="870" height="277" alt="Screenshot 2025-10-07 8 07 26 PM" src="https://github.com/user-attachments/assets/85535029-eeb2-409b-8aca-1531b288079f" />
<img width="696" height="325" alt="Screenshot 2025-10-07 8 07 32 PM" src="https://github.com/user-attachments/assets/9bfe92a4-729d-477d-b71b-4c654f70d4be" />

Each Student’s role:
Mohammed Alsheraa - Implemented the following features: 
handled the socket programming for both the server and client
Implemented the getbalance function
Ellette Foucher - Implemented the following features:
Implemented functions for sell, buy, and list


Bugs in the code:
No known bugs in the code. 

Youtube Link: 
https://youtu.be/yDxu7kkkCPQ
