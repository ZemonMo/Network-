# Network+ Learning Notes — Networking Fundamentals

## Topics Learned

### IP Addressing

* Understood the purpose of IP addresses in identifying devices and networks.
* Learned how devices use IP addresses to communicate across networks.
* Connected IP addressing with routing and default gateways.

### Common Network Ports

* Learned common TCP/UDP ports and the services associated with them.
* Understood why ports help identify which network service is being accessed.

### OSI Model

* Reviewed the seven OSI layers and their roles in network communication.
* Focused on understanding where protocols and networking devices operate rather than memorizing the layer names.

### Ethernet

* Learned that Ethernet covers both the physical transmission and data-link aspects of wired networking.
* Understood the relationship between Ethernet frames, MAC addresses, and physical signals.
* Compared Ethernet with wireless networking such as Wi-Fi.

### Network Switches

* Learned how switches operate primarily at Layer 2.
* Understood how switches use destination MAC addresses to forward Ethernet frames.
* Learned that switch ports normally create separate collision domains.

### Hubs

* Learned that traditional hubs operate at Layer 1.
* Understood that hubs repeat physical signals rather than intelligently forwarding frames.
* Learned why multiple simultaneous transmissions on a shared hub can cause collisions.

### Broadcast Domains

* Learned what a broadcast domain is and how Layer-2 broadcasts behave within it.
* Connected ARP broadcasts with local network communication.
* Understood that routers separate broadcast domains.

### Collision Domains

* Learned the difference between collision domains and broadcast domains.
* Understood why classic hub-based Ethernet could experience collisions.
* Learned how modern switched full-duplex Ethernet largely eliminates classic shared-medium collisions.

## Practical Understanding

I connected the concepts together instead of treating them as isolated definitions:

```text
Device
  ↓
Wi-Fi / Ethernet
  ↓
Switch
  ↓
Router
  ↓
ISP
  ↓
Internet
```

I also explored how ARP broadcasts work on a local network:

```text
ARP Broadcast
      ↓
Devices in the broadcast domain receive it
      ↓
Device owning the requested IP responds
      ↓
Other devices ignore the request
```

## Key Takeaway

The main goal of this study session was **understanding how networking works as a system**, not simply memorizing Network+ terminology.

I focused on understanding the relationship between:

**IP addresses → Ethernet → MAC addresses → switches → broadcasts → collision domains → routers → different networks.**
