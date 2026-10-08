Today is I'm sharing the learning I completed yesterday.

# Topic 1: Layer2 vs Layer3 Switch
Layer2: It works on 2nd layer (Data Link Layer) of OSI model which uses MAC address to send or receive data packets.
Layer3: It works on 2nd and 3rd layer (Network layer) of OSI model. It uses IP address for communication between two devices.

# Notes:
- VLAN - It divides a network into separate broadcast domains. E.g. VLAN 10 [having IP range of xx.xx.xx.xx/xx] and VLAN 20 [IP range YY.YY.YY.YY/YY]
these VLANs can't communicate to each other. To make it communicate we will use Layer3 switch.
- SVI - Switch Virtual Interface - These virtual interfaces allow data to be routed between VLANs by creating default gateways.

- Router and Layer3 Switch are also different.
  
# Topic 2: Router vs Wireless Access Point

A wireless AP relays data between a wired network and wireless devices. Basically it works like a bridge between route and wireless devices.
 # Router vs WAP
 - Routers have DHCP system which allocates IP address to network devices. WAP doesn't have any DHCP system.
 - Routers have Firewall but WAP doesn't.
 - Wifi Routers have WAN (internet) port in them thru which it can directly access internet but WAP doesn't have this port they access internet from routers only.
 - WAP are strictly wireless but routers have ports for ethernet connections.
 - 
