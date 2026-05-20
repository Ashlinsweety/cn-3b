# 3b.CREATION FOR CHAT USING TCP SOCKETS
## AIM
To write a python program for creating Chat using TCP Sockets Links.
## ALGORITHM:
1. Import the necessary modules in python
2. Create a socket connection to using the socket module.
3. Send message to the client and receive the message from the client using the Socket module in
 server
4. Send and receive the message using the send function in socket.
## PROGRAM
```
import socket 
s=socket.socket() 
s.connect(('localhost',50000)) 
while True: msg=input("Client > ") 
s.send(msg.encode()) 
print("Server > ",s.recv(1024).decode())
```
```
import socket 
s=socket.socket() 
s.bind(('localhost',50000)) 
s.listen(5) 
c,addr=s.accept() 
while True: 
    ClientMessage=c.recv(1024).decode() 
    print("Client > ",ClientMessage) 
    msg=input("Server > ") 
    c.send(msg.encode())
```
## OUPUT
<img width="1344" height="781" alt="Screenshot 2026-05-20 083459" src="https://github.com/user-attachments/assets/f22c1785-2715-4721-876b-47db930b868c" />
<img width="1345" height="720" alt="Screenshot 2026-05-20 083513" src="https://github.com/user-attachments/assets/d63b2f6b-ab49-4b4a-baa8-6eaf6a41c1ab" />

## RESULT
Thus, the python program for creating Chat using TCP Sockets Links was successfully 
created and executed.
.
.
.
.
.
..
..

..
.

.
.
.
...
.
.
.
.
.
..
.
.
.
.
.


.

..
.
.


.
.
.
..
.

.
.
.
.

.
.
.


.


..
.
.
..
.
.
.
.
..

......
.
.
.

..
.

.


.
.
.

.
.
.

..


.
.


..................
.
.


.

.
.

.
.

..
.

..

.

..
.

.
..



.
..

.
.

.
.
..

.
. ..
.
..
.
