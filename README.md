# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
![image](https://github.com/user-attachments/assets/29d75658-9a67-499a-b58d-4da71006aedf)

## OUPUT - ARP
![image](https://github.com/user-attachments/assets/37b00d25-3c64-45cf-80df-d52adaa602bb)

## PROGRAM - RARP
![image](https://github.com/user-attachments/assets/03a5cec1-c827-4559-82d9-16e88a6e0b4f)

## OUPUT -RARP
![image](https://github.com/user-attachments/assets/429969a4-67d2-46d0-84bc-a0dc6c9d1a9d)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
