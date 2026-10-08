# CCNA-Prep
Following Jeremy's IT Lab Course to prepare for CCNA
---
Day 1:

<img width="400" height="400" alt="day1" src="https://github.com/user-attachments/assets/41b98e0a-f9d9-4714-b2f3-cfc2b1bada14" />

Very Basic, Switches connect end-hosts to make a LAN but cant connect two LANS together and can not connect to the internet so a router is needed in both the LANS, attacker might try to attack so firewalls are needed they allow data or traffic to flow if it meets the configured firewall rules
The internet is represented using the router symbol at the center

---
Day 2:
Interfaces and Cables

<img width="400" height="400" alt="day2" src="https://github.com/user-attachments/assets/31a15170-1ac7-4b10-896d-04713f54d856" />

Assuming there is no Auto MDI-X connecting PCs,Server and Routers to Switches using straight through cables.
for Switch-Switch connection and Router-Router connection we use crossover cables.
for R1 and R3 we have to use single mode fiber optic cable because distance=3km to do that click on the router and add the module PT-ROUTER-NM-1FFE-SM.
for R3 and R4 we can use multimode fiber optic cable because the distance is 250m so no need to use single mode cable.

---
Day 3:
TCP/IP Model and OSI Model

<img width="400" height="400" alt="day3" src="https://github.com/user-attachments/assets/05394fc6-96a6-41d4-b020-2bb6fda79435" />

<img width="400" height="400" alt="day3b" src="https://github.com/user-attachments/assets/b6ecf6a4-8784-4440-9a7a-683ec51e6f74" />


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

<img width="400" height="400" alt="day4b" src="https://github.com/user-attachments/assets/4dc740fb-60b5-4e50-8c8d-c247ce046d3c" />

<img width="400" height="400" alt="day4a" src="https://github.com/user-attachments/assets/565e5aaf-6041-4eb9-b60b-910d5ac0ee2f" />

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
<img width="400" height="400" alt="day4c" src="https://github.com/user-attachments/assets/af192ea5-1ee4-4812-84a5-32ce7286de93" />

---
Day 6: Ethernet Switching

Question:

<img width="400" height="400" alt="day6a" src="https://github.com/user-attachments/assets/25545c0e-1dd3-4753-94c4-3176091dcb0d" />

Answer 2:

<img width="400" height="400" alt="day6b" src="https://github.com/user-attachments/assets/a5948372-cac0-46a4-90ea-36ba431f4c2c" />

<img width="400" height="446" alt="day6c" src="https://github.com/user-attachments/assets/c3b7f202-a503-4659-87d0-cb5e129b9427" />

Answer 4:

<img width="400" height="400" alt="day6d" src="https://github.com/user-attachments/assets/ca3c0b3b-3729-4172-8872-5f6bd5621110" />

<img width="400" height="250" alt="day6e" src="https://github.com/user-attachments/assets/a9f5cd56-883b-48a1-b1a5-e5b9fb91ec3e" />

Answer 5:

<img width="400" height="400" alt="day6f" src="https://github.com/user-attachments/assets/dcb8b9e2-c7d1-4e2e-8cb4-5036006c5151" />

---

Day 8:

Tasks:

<img width="400" height="400" alt="day8Q" src="https://github.com/user-attachments/assets/1f989ccb-3374-4a94-b861-297d3e972878" />

Solutions:
-----
<img width="400" height="250" alt="day8a" src="https://github.com/user-attachments/assets/941f80c3-2fee-4fb8-a8fc-78c3fc524c14" />

---
<img width="400" height="400" alt="day8c" src="https://github.com/user-attachments/assets/e9692312-00c2-4c9a-9314-b82db2641db8" />

---
<img width="400" height="392" alt="day8b" src="https://github.com/user-attachments/assets/2fceb65e-7eda-4a0d-a0ff-13e745966a02" />

------
Day 11 P1:

Task:

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/fd72440c-10cd-4a86-b674-efd68239ffe9" />

---
After Config and Ping from PC1 to PC2:

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/9d483222-e44b-4ca8-b1c6-abf0f0e558b3" />

---
Day 15: VLSM
-

Task:

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/18d4193c-b3ae-4ba8-beb7-ca3edae77499" />

---
After Configs:

---
PC1-PC4:

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/518ca300-58e6-4cce-990c-eae39da9a580" />

---
PC2-PC3:

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/5fa2e044-86b0-4302-8ada-4794846ae6f5" />

---
PC4-PC3:

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/7d9878c6-3cea-4267-953e-6a3e333198a8" />

---

Day 16 Lab: VLANS

Task:

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/9fdbbb40-04ac-4a30-ac1f-dbe3a2a6c0fe" />

---

After Configs:

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/fca597e6-18de-48f2-8eda-a90c1a7b5a05" />

---

so a ping from PC1 to the broadcast address of the VLAN10 was going to SW1 and SW1 was flooding it only into the VLAN 10 devices which include the PC2 and the Router R1 instead of flooding it everywhere hence the configuring was successful.

Also a ping from PC1 to PC5 went to the SW1 first, SW1 forwarded it to R1, R1 sent it back to SW1 and then SW1 sent it to PC5.

---
