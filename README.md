# Network-Design


## Project Overview
In this project, I collaborated with a team of 4 and developed a network topology in Cisco Packet Tracer. The main goal was to create a working topology with a **80 to 100 PC with the implementation of DHCP, EtherChannel, VLSM, VLAN, WLAN, Network Security & Port Security.**

## Topology
The topology that we came up with was a hybrid topology. It is a network structure that combines two or more different types of topology. In our case, it is a combination of a series of star topologies with an incorporation of a bus topology. 

![image](https://github.com/user-attachments/assets/16799efc-2359-4ed0-a3d7-c02311bc02f8)

**Addressing Table:**

![image](https://github.com/user-attachments/assets/abff944e-7b9e-4941-9b1a-f8ad249dbe4b)
![image](https://github.com/user-attachments/assets/d4a15ea0-0fdf-4eb9-ae83-0d8b4d89d7a3)

The rest of the PC devices are DHCP-enabled. 

For this project, I was responsible for implementing network security, such as firewalls, ACLs, & network segmentation. Configuring the firewall and ACLs acts as a barrier and filters network traffic to prevent unauthorized access and block malicious content. Separating networks of the different networks of the organization is crucial for enhancing security and reducing networking congestion. 



to all routers in the network. The goal was for the IT Department's router to ping all the different department routers in the organization, and the department routers could only ping the IT Room router. Here is a snippet of the commands I used.

![image](https://github.com/user-attachments/assets/ca2fe15c-3478-4a40-bffb-28c8a8530f50)

I also configured and encrypted the AAA/RADIUS authentication server. All the usernames and passwords are stored in this server so that is why encrypted the server and only authorized personnel can access the server for configuration.

![image](https://github.com/user-attachments/assets/5d38b382-f7a9-49e1-a75e-a07762a3a76c)

In testing the network connectivity of each device we used troubleshooting commands such as ipconfig, netstat, ping, tracert, nslookup, & etc.
