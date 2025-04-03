# Network Design

## Project description
In this project, I collaborated with a team of 4 and developed a network topology in Cisco Packet Tracer. The main goal was to create a working topology with a **80 to 100 PC with the implementation of DHCP, EtherChannel, VLSM, VLAN, WLAN, Network Security & Port Security.**

## Topology
The topology that we came up with was a hybrid topology. It is a network structure that combines two or more different types of topology. In our case, it is a combination of a series of star topologies with an incorporation of a bus topology. 

![image](https://github.com/user-attachments/assets/16799efc-2359-4ed0-a3d7-c02311bc02f8)

**Addressing Table:**

![image](https://github.com/user-attachments/assets/abff944e-7b9e-4941-9b1a-f8ad249dbe4b)
![image](https://github.com/user-attachments/assets/d4a15ea0-0fdf-4eb9-ae83-0d8b4d89d7a3)

The rest of the PC devices are DHCP-enabled. 

For this project, I was responsible for implementing network security, such as firewalls, ACL, & network segmentation. 

Separating networks of the different networks of the organization is crucial as it enhances security, improves performance, and isolates sensitive data.

Configuring the firewall acts as a barrier and filters network traffic to prevent unauthorized access and block malicious content. I made an ACL that denies port 22, 23, and 80. In line 6 I also permitted port 22 in order to selectively allow some SSH traffic. The rest of the permit list permits traffic from the IP network to any detection, and the last line permits traffic whose source address is exactly 0.0.0.0 and whose destination address is exactly 255.255.255.255, which can be seen in the configuration below.

![image](https://github.com/user-attachments/assets/ca2fe15c-3478-4a40-bffb-28c8a8530f50)

I also configured the AAA/RADIUS authentication server via Port 1645. The RADIUS protocol provides centralized authentication, authorization, and accounting (AAA) services for users who connect and use network services. All the usernames and passwords are stored in this server, which can be seen in the configuration below.

![image](https://github.com/user-attachments/assets/5d38b382-f7a9-49e1-a75e-a07762a3a76c)

Lastly, in testing the network connectivity of each device, we used troubleshooting commands such as ipconfig, netstat, ping, tracert, nslookup, & etc.
