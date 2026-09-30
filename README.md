# CCNA-Prep
Following Jeremy's IT Lab Course to prepare for CCNA
---
Day 1:

<img width="694" height="290" alt="day1" src="https://github.com/user-attachments/assets/41b98e0a-f9d9-4714-b2f3-cfc2b1bada14" />

Very Basic, Switches connect end-hosts to make a LAN but cant connect two LANS together and can not connect to the internet so a router is needed in both the LANS, attacker might try to attack so firewalls are needed they allow data or traffic to flow if it meets the configured firewall rules
The internet is represented using the router symbol at the center

---
Day 2:
Interfaces and Cables

<img width="551" height="305" alt="day2" src="https://github.com/user-attachments/assets/31a15170-1ac7-4b10-896d-04713f54d856" />

Assuming there is no Auto MDI-X connecting PCs,Server and Routers to Switches using straight through cables.
for Switch-Switch connection and Router-Router connection we use crossover cables.
for R1 and R3 we have to use single mode fiber optic cable because distance=3km to do that click on the router and add the module PT-ROUTER-NM-1FFE-SM.
for R3 and R4 we can use multimode fiber optic cable because the distance is 250m so no need to use single mode cable.

---
Day 3:
TCP/IP Model and OSI Model

<img width="700" height="314" alt="day3" src="https://github.com/user-attachments/assets/05394fc6-96a6-41d4-b020-2bb6fda79435" />

<img width="333" height="339" alt="day3b" src="https://github.com/user-attachments/assets/b6ecf6a4-8784-4440-9a7a-683ec51e6f74" />


Just using the simulation tool in packet tracer to observe the OSI model and how the stacked layers work.

From my understanding at this point in time:

layer 7 contains protocols regarding the communication between the apps for example HTTP/HTTPS

Layer 5 and 6 are not really used and can be considered a part of the layer 7.

Layer 4 is the transport layer and it encapsulates the port number onto the data from layer 7 to help it reach the end host.(segment for TCP/IP and datagram for UDP)

layer 3 uses ip addresses and routers for end to end communication between the hosts.(packet or L3PDU)

Layer 2 uses MAC addresses for hop-hop communication, switches do not count as hops.(frame or L2PDU)

Layer 1 is the physical layer.(bits)
---
Day 4:

CLI Intro

<img width="312" height="221" alt="day4b" src="https://github.com/user-attachments/assets/4dc740fb-60b5-4e50-8c8d-c247ce046d3c" />

<img width="360" height="294" alt="day4a" src="https://github.com/user-attachments/assets/565e5aaf-6041-4eb9-b60b-910d5ac0ee2f" />

use Router>enable, then Router# config t to enter Router(config)# mode

use Router(config)# hostname R1 to change hostname.

then Router(config)#enable password CCNA to enable password and you can exit and enter the modes again to confirm

Router(config)# service password-encryption to encrypt the password

Router(config)# do show running-config to view the encypted password

Router(config)# enable secret Cisco to make an even more secure password

Router(config)# do write to copy running config to startup config

Router (config)# do show startup-config to view the startup config

Here is the result:
---
<img width="270" height="242" alt="day4c" src="https://github.com/user-attachments/assets/af192ea5-1ee4-4812-84a5-32ce7286de93" />
