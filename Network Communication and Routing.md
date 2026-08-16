# Network+ — Network Communication and Routing

## Topics Learned

### Unicast, Broadcast, and Multicast

* **Unicast:** One sender communicates with one specific receiver.
* **Broadcast:** One sender communicates with all devices within the relevant broadcast domain.
* **Multicast:** One sender communicates with a specific group of receivers that joined the multicast group.
* Connected multicast concepts with IPTV and understood the difference between IP multicast and terrestrial/satellite broadcasting.

### Network Segmentation

* Learned why networks are divided into smaller segments.
* Understood how segmentation can improve security, performance, and network management.
* Connected segmentation with VLANs, subnets, switches, routers, and broadcast domains.

### Protocol Data Units (PDUs)

Learned how data is represented at different layers:

```text
Application → Data
Transport   → Segment / Datagram
Network     → Packet
Data Link   → Frame
Physical    → Bits
```

Also understood **encapsulation**, where each layer adds its own information, and **decapsulation**, where the receiving device removes the headers as the data moves back up the stack.

### Spanning Tree Protocol (STP)

* Learned why redundant switch connections can create Layer-2 loops.
* Understood how Layer-2 loops can cause broadcast storms, duplicate frames, and MAC-table instability.
* Learned that STP blocks redundant paths while keeping them available as backups.
* Understood that a previously blocked path can become active if the primary path fails.

### Switch Interface Properties

* Learned about switch-port characteristics such as:

  * Speed
  * Duplex
  * Access ports
  * Trunk ports
* Understood the difference between half-duplex and full-duplex communication.
* Learned that access ports normally carry traffic for one VLAN, while trunk ports can carry traffic for multiple VLANs.

### Static Routing

* Learned that static routes are manually configured by an administrator.
* Understood how a router uses a static route to determine where traffic for a remote network should be forwarded.
* Learned that static routing is predictable and useful for smaller or simpler network environments.

### Dynamic Routing

* Learned that dynamic routing protocols allow routers to automatically exchange routing information.
* Understood that routers can update their routing tables when network topology changes.
* Studied the purpose of protocols such as OSPF, RIP, EIGRP, and BGP.
* Compared dynamic routing with manually configured static routes.

## Overall Understanding

These topics helped connect how traffic moves through a network:

```text
Application Data
      ↓
PDU Encapsulation
      ↓
Ethernet Frame
      ↓
Switch
      ↓
VLAN / Network Segmentation
      ↓
STP controls Layer-2 topology
      ↓
Router
      ↓
Static or Dynamic Routing
      ↓
Destination Network
```

The focus of this study session was understanding **how the concepts work together**, rather than memorizing isolated definitions.