## Welcome to my TCP/IP Networking Project

In this project, I built basic TCP Server and TCP Client applications.  I based these applications on some examples in an old Computer Communication Networking textbook (see reference below).  These applications are written in C and compiled using gcc on a moden Linux system.  The applications each run in different terminals on the same computer.  After I built this project, I ran it a few times, tested it, and tried to break it.  I developed a list of questions to follow-up on in order to learn more about TCP/IP networking and this code.   

### System Prerequisities
These systems were built on an Ubuntu 18.04 system, and were compiled with gcc version 7.5.0.  

### Compiling the code

Add instructions here

### Running the code
In terminal #1, run the TCP Server with the following:
```markdown
$ ./TCPServerExample 3000
```
In a second terminal, run a TCP Client with the following:
```
$ ./TCPClientExample 127.0.0.1
```
You will get some feedback indicating that the Client has connected to the TCP Server:
```
$ ./TCPClientExample 127.0.0.1
Connected: server address is 127.0.0.1
Transmit:
```
At this point, enter text following the "Transmit:" prompt in order to have the text echoed by the TCP Server:
```
$ ./TCPClientExample 127.0.0.1
Connected: server address is 127.0.0.1
Transmit:
Hello!
Receive:
Hello!
```
This demonstrations has shown how the TCP server is echoing the information sent from teh TCP Client application.

### Follow-on questions
1- This is running on a single computer, localhost, 127.0.0.1.  If I change the IP address to 127.0.0.3, the application still works!  Why is that?
2- Can I run this across two different computers?
3- Can I get this to run on a different Port# other then TCP Port 3000?

### Reference
Computer Communication Networks

