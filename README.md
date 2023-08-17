# University Networking using CISCO packet tracer
Campus Network (CN) is a set of Virtual Local Area network (VLAN), which covers the entire university. It provides difference service such as connect user to internet, data sharing among user, accessing different web service for different functionalities.
As Campus Network (CN) provides students, teachers, and different university member for different application, to sustain different activities in the university, so it need to design in advance.
To design the proposed campus network design, I used cisco
packet tracer simulator software.
# INTRODUCTION
Local area network (LAN) is a network that is controlled by single authority. Campus network (CN) is set of virtual local area networks (VLAN), which are virtual divided for increasing the performance of network and increases campus network management with security.

Virtual local area networks have become crucial for organizations with complex networking systems. Organizations require solutions that allow them to scale their networks, segment them to increase security measures, and decrease network latency.

While LAN is used to connect a group of devices such as computers and printers to a server via cables, VLANs allow multiple LANs and associated devices to communicate via wireless internet.

The main objective of this project is to build a better network for the campus by reducing load and traffic while sending multiple data from multiple hosts.
# METHODOLOGY
In order to design campus network we used cisco packet tracer . Cisco Packet Tracer is a networking simulator used for teaching and learning program.

Benefits of Packet Tracer are:
- Offers a realistic simulation and visualization
- Permits users to design, build, configure, and troubleshoot complex networks
- Allows students to explore concepts, conduct experiments

This environment provides a wide range of layer 2 and layer 3 devices in order to build a network. The connections to be made between the devices are also compactible. It gives users the option auto routing which automatically makes a connection between two devices based on the required type of connection.

Concepts used in our project are
- VLAN- A virtual LAN is a logical overlay network that groups together a subset of devices that share a physical LAN, isolating the traffic for each group.
- DHCP- DHCP (Dynamic Host Configuration Protocol) is a network management protocol used to dynamically assign an Internet Protocol (IP) address to any device, or node, on a network so they can communicate using IP. DHCP automates and centrally manages these configurations rather than requiring network administrators to manually assign IP addresses to all network devices. DHCP can be implemented on small local networks, as well as large enterprise networks.
# IMPLEMENTATION
At first, we build a separate vlan for all buildings located in the campus. Based on the requirement number of routers in each department can be used. Our next task is to configure our devices by assigning a unique IP address to each. We use dhcp in our project which manages all the configuration automatically. Now we can send and receive data from one host to each other servers by pinging respective IP. There is no traffic while sending data as we have created different VLAN. Thus this implementation can used in universities or companies where multiple hosts are sending multiple data.
