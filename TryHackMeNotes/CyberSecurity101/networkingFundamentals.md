## What I learned:
 - IP Address
 - MAC Address - can spoof mac address to pretend to be other devices on the network
 - LAN Topologies
 - Ping - time taken for ICMP (internet control protocol) packets to travel between devices
 - Default gateway address - Assigned to a device on the network that is capable of sending information to another network
 - Network address - Used to identify the start of a network
 - Host address - Used to identify devices in the network
 - Sub-netting - Dividing a large network into a smaller network
 - ARP (Address Resolution Protocol) - used to allow devices to identify themselves on networks
 - DHCP (Dynamic Host Configuration Protocol) server - used to assign IP address to devices on the network
 - OSI (Open Systems Interconnection) model - provides a framework for how all network devices will send, recieve and read data
   - Layers:
   - Physical - hardware used in the network
   - Data Link - assigns and utilises the mac address to data packets
   - Network - used in the re-assembly of data and finding the most optimal routes to send packets
   - Transport - used in transmitting data across networks using:
     - TCP (Transmission Control Protocol) - reliable but slow data transfer (better for emails where data cannot be missing)
     - UDP (User Datagram Protocol) - fast but unreliable data transfer (better for video streaming where pixelation is acceptable)
   - Session - once data is formatted a session will be created with the recieving computer it is also maintained, and closed if inactive or disrupted
   - Presentation - acts as a translator for data to and from the application layer, security features such as encryption occur at this layer
   - Application - software layer which sits between the user and the underlying abstracted network
  - Port - virtual communication endpoint used by the OS to direct network traffic

## Commands
- `ping 123.456.7.8`
