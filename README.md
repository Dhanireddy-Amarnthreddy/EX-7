# EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND

## DATE :20-04-2023

# AIM :To write the python program for simulating Traceroute command

# ALGORITHM :
1.Start the program.

2.Get the frame size from the user.

3.To create the frame based on the user request.

4.To send frames to server from the client side.

5.If your frames reach the server, it will send ACK signal to client otherwise it will sendNACK signal to client.

6.Stop the program

# PROGRAM :
```
Developed by :D.Amarnath Reddy
Register Number : 212221240012
```
~~~
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
~~~
# OUTPUT :
![image](https://github.com/NAGINENIROHITH/EX-7/assets/118344049/7185d977-1902-4ac1-bcf7-57138c850bea)


# RESULT :
Thus, the python program for simulating Traceroute command was successfully executed
