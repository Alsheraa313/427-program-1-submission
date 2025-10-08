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
<img width="1920" height="1140" alt="image" src="https://github.com/user-attachments/assets/731dcb3a-1705-4dac-9776-2b6d1a1402c7" />
<img width="1920" height="1140" alt="image" src="https://github.com/user-attachments/assets/16615328-3c8e-4afa-9026-13cab587236d" />

Each Student’s role:
Mohammed Alsheraa - Implemented the following features: 
handled the socket programming for both the server and client
Implemented the getbalance function
Ellette Foucher - Implemented the following features:
Implemented functions for sell, buy, and list


Bugs in the code:
No known bugs in the code. 
