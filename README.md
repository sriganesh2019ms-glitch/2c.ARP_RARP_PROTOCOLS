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

server:

<img width="1012" height="537" alt="Screenshot 2026-05-19 134122" src="https://github.com/user-attachments/assets/953aca00-42fe-43a3-a1fa-69e3b39ef814" />

client:

<img width="1012" height="537" alt="Screenshot 2026-05-19 134122" src="https://github.com/user-attachments/assets/d38887e7-d445-42c0-93d4-3f7fec93bd1e" />


## OUTPUT - ARP

<img width="784" height="180" alt="Screenshot 2026-05-19 134147" src="https://github.com/user-attachments/assets/8cde0c5d-afd7-49c9-972e-e24230907be8" />


## PROGRAM - RARP

server:

<img width="1035" height="454" alt="image" src="https://github.com/user-attachments/assets/9d1fb38e-51c7-4cb4-a71c-3d2360212337" />

client:

<img width="903" height="347" alt="image" src="https://github.com/user-attachments/assets/16f17db3-a73c-420b-bb79-3a310fdf9aae" />


## OUTPUT -RARP

<img width="798" height="216" alt="image" src="https://github.com/user-attachments/assets/d2a51e9c-066f-48fd-8276-dc36386ee6e8" />

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
