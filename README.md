<p align=center>
  <ins>Overview of Concepts</ins>
</p>

Virtual Private Network
   * an overlay network that virtualizes a network connection to encrypt communications between two points over a public network, such as the Internet, via tunneling protocols
     * IPSec is a suite of network security protocols used by VPNs to authenticate, verify, and encrypt data packets between two endpoints
     * mutual authentication and negotiation of encryption protocols between devices to establish a VPN tunnel
    
Default Routes
  * a forwarding rule for data packets when a specified address of a next-hop host is not determined in a routing table or other routing avenue
     * a default route is a backup route to another router in case a packet's route is indeterminate to its destination

Route Summarization
  * reduces the number of entries in a routing table to advertise to another router, eases load on computing
  * combines subnets into a larger network address, diminishing routing tables for optimization with OSPF, EIGRP, and BGP
      * e.g. 192.168.100.0/26, 192.168.100.64/26, 192.168.100.128/26, and 192.168.100.192/26 can be summarized to 192.168.100.0/24
      * or: 192.168.100.0/26 and 192.168.100.64/26 can be summarized to 192.168.100.0/25
      * and: 192.168.100.128/26 and 192.168.100.192/26 can be summarized to 192.168.100.128/25


<p align=center>
  <img src="https://github.com/Fehral/networkprojectv7/blob/main/networkprojectv7topology.png?raw=true">
</p>

###### Configuration files and address mapping for each device will be uploaded within the repository.
