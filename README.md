# TCPIP-2020
Assignments &amp; courseworks in 2020 Spring TCPIP

# Week one 
Review the basic knowledges in TCPIP, including a demo for communcating between server and client.

To compile the code using WinSokect APIs, the command is:
```g++ ./file.cpp -o file -l ws2_32 ```
which tells g++ to use the lib naming ws2_32.lib

[Code](https://github.com/Carlwasinfected/TCPIP-2020/tree/master/Review-Assignments)
```cpp
  // server.exe output:
  -------------------------------
Server waiting
-------------------------------
Accepted client IP:[192.168.0.104],port:[49933]
send( ) byte:15
-------------------------------
Accepted client IP:[192.168.0.104],port:[49936]
send( ) byte:15
-------------------------------
Accepted client IP:[192.168.0.104],port:[49938]
send( ) byte:15
-------------------------------
Accepted client IP:[192.168.0.104],port:[49940]
send( ) byte:15
-------------------------------

// client.exe output
$ ./client.exe 192.168.0.104
recv( ) data from server:I am a server.


```
