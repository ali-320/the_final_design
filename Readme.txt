We have used the cisco packet tracer to create the whole project, its design and show the simulation.
The cisco packet tracer is a free software, offered by the cisco organization.
You can download this from the cisco website. You will have to register yourself, on the cisco learning website first and in a course.
Then you can just open uploaded .pkt file, and see the design.

The project has the following components:
1. Switches: They are the core components, connecting the end devices with each other creating a network, allowing communication.
They are also used for encryption or privacy of departments. This can be done by creating VLANs using switches. VLANs are virtual local area networks,
it just as it sounds, we separate one VLAN into virtually many local area networks. They are still one physically but operate as they're not. Good to keep the departments
communication separate in a single organization, and also for data integrity and security.
2. Routers: Now, the VLANs might need to communicate with each other at some time, for this we will use routers, as they are considered as separate networks.
We will create subinterfaces in the router for the VLANS assign the default gateway address to each subinterface, and also the address of the DHCP server.
We will use two routers, the standby protocol for router failover, and assign the externally connected interfaces of the router the public IP addresses.
3. Servers: I have used four servers: DHCP, Web, DNS, and Email server. DHCP will assign IP addresses to the end devices, Web server will host the website of the organization,
the DNS server will give a domain name to the website, and the Email server will allow text communication and email communication between end devices, by storing and forwarding
emails.
4. End devices: The end devices are the users of the network, the employees and the clients.
