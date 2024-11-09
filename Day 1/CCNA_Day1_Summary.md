# CCNA Course - Day 1: Network Devices

## Reference
[Free CCNA | Network Devices | Day 1 | CCNA 200-301 Complete Course by Jeremy's IT Lab](https://www.youtube.com/watch?v=H8W9oMNSuwo&list=PLxbwE86jKRgMpuZuLBivzlM8s2Dk5lXBQ)

---

## Basic Information

### 1. Client
- A device that accesses services provided by a server.

### 2. Server
- A device that provides services or functions for clients.

### 3. Switch (SW)
- **Purpose:** Used to connect servers or clients together in one **Local Area Network (LAN)**.
- **Characteristics:**
  - Contains many ports/interfaces to connect end hosts.
  - Provides connectivity within the same LAN.
- **Note:** Switches do **not** provide connectivity between different LANs or to the Internet.

### 4. Router (R)
- **Purpose:** Routes and finds paths to other routers or networks.
- **Characteristics:**
  - Usually has fewer interfaces than switches.
  - Provides connectivity between LANs and allows access to external networks like the Internet.

### 5. Network Firewall (FW)
- **Purpose:** Provides security for the network by monitoring and controlling traffic based on configured rules.
- **Characteristics:**
  - Blocks unauthorized access and potential attackers.
  - Can be placed **inside**, **outside**, or in **both** areas of the network.

### 6. Host Firewall
- **Purpose:** A software-based firewall within a client or server to enhance security.
- **Characteristics:**
  - Operates at the application level and helps to filter incoming and outgoing traffic for that specific device.

---

## Additional Notes
- **Switches and Routers:** It's essential to understand that switches operate at Layer 2 of the OSI model (Data Link Layer) while routers operate at Layer 3 (Network Layer). This distinction affects their primary functions and usage.
- **Firewalls:** Firewalls can be stateful or stateless. A stateful firewall keeps track of the state of active connections and uses this information to make decisions about which packets to allow through.
- **Best Practices:** Always have a layered security approach by using network and host firewalls together to minimize risks.
