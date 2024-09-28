# Introduction to Networking

## 1. What is a Network?

A network connects computers so they can communicate, exchange information, and share resources.

### Main Benefits of Using a Network:

1. Simultaneous Access
2. Shared Peripheral Devices
3. Personal Communication
4. Easier Backup

### Data Transmission in Networks:

- Data is broken into small pieces called **packets**
- A packet consists of:
  - Header (contains sending/receiving address and data type)
  - Payload (actual data)

## 2. Classification of Networks

### 2.1 Based on Geography

1. **Local Area Network (LAN)**
   - Operates over a small physical area (e.g., office, factory)
   - Easy to design and troubleshoot
   - Typically owned and managed by a single organization

2. **Wide Area Network (WAN)**
   - Spans large distances or widely separated locations
   - Uses leased telephone lines, satellite links, optical fiber
   - Efficient for transferring large blocks of data

3. **Personal Area Network (PAN)**
   - Organized around an individual person
   - Consists of mobile devices (computer, phone, PDA)
   - Can be wireless or wired

4. **Campus Area Network (CAN)**
   - Interconnection of LANs within a limited geographical area
   - Usually owned by the campus

5. **Metropolitan Area Network (MAN)**
   - Covers an entire city
   - Can be a single network (e.g., cable TV) or interconnected LANs

### 2.2 Based on Component Role

1. **Client/Server Networks**
   - Certain computers act as servers, others as clients
   - Centrally managed resources
   - Advantages: Very secure, better performance, centralized backup
   - Disadvantages: Requires professional administration, more expensive

2. **Peer-to-Peer (P2P) Networks**
   - Each computer is responsible for its own resources
   - No central control system
   - Suitable for small networks (less than 10 computers)
   - Advantages: Less expensive, easy to administer, no NOS required
   - Disadvantages: Less secure, no central storage, hard to maintain versions

## 3. Network Topologies

The layout of cables and devices connecting nodes in a network.

1. **Linear Bus**
   ```
   [Device]---[Device]---[Device]---[Device]
   ```
   - Advantages: Easy to connect, less cable than star
   - Disadvantages: Slow, entire network affected by breaks

2. **Star**
   ```
         [Device]
            |
   [Device]-+--[Central Hub]--[Device]
            |
         [Device]
   ```
   - Advantages: Easy to connect/remove nodes, easy error detection
   - Disadvantages: More cable, dependent on central hub

3. **Ring**
   ```
      [Device]
     /        \
   [Device]  [Device]
     \        /
      [Device]
   ```
   - Advantages: Predictable data transmission time, no collisions
   - Disadvantages: Slow, lots of cable

4. **Mesh**
   - All computers connected to each other
   - Advantages: Reliable data delivery
   - Disadvantages: Lots of cable, hard to set up

5. **Tree**
   - Combination of bus and star topologies
   - Advantages: Point-to-point wiring, fault-tolerant
   - Disadvantages: Complex configuration, limited cable lengths

## 4. Transmission Media

### 4.1 Guided Media (Wired)

1. **Twisted-Pair Cables**
   - Unshielded Twisted-Pair (UTP)
   - Shielded Twisted-Pair (STP)

2. **Coaxial Cables**
   - Higher frequency than UTP (100KHz–500MHz)
   - Better shielding against noise

3. **Fiber-optic Cables**
   - Data transmitted with light pulses
   - Immune to interference, very secure
   - Difficult to work with

### 4.2 Unguided Media (Wireless)

- Radio waves (for LANs)
- Microwave signals (for WANs)
- Easy to set up, but more difficult to secure

## 5. Network Hardware

1. **Network Interface Card (NIC)**
   - Enables computer connection to network
   - Prepares, sends, and controls data flow
   - Each NIC has a unique serial number for identification

2. **Hubs**
   - Link several computers together
   - Repeats all information to all connected devices
   - Slow and insecure

3. **Switches**
   - More intelligent than hubs
   - Inspects data packets and forwards to correct destination
   - Fast and secure

4. **Bridge**
   - Segments large networks into smaller, efficient networks
   - Connects different types of cabling (same protocol)
   - Filters traffic based on MAC address

5. **Router**
   - Connects different networks (e.g., LAN to WAN)
   - Forwards packets based on IP address
   - Can determine best path for data

6. **Gateway**
   - Joins networks with different base protocols
   - Can be implemented in software, hardware, or both

7. **Modem**
   - Enables data transfer between telephone lines and computers
   - Performs modulation (digital to analog) and demodulation (analog to digital)

## 6. Network Protocols

A set of rules governing communications between computers on a network.

### TCP/IP (Transmission Control Protocol/Internet Protocol)

- Most popular protocol
- Uses IP addresses (e.g., 209.8.166.179)
- Includes Dynamic Host Configuration Protocol (DHCP) for simplified IP assignment

## 7. Practice Questions

1. What are the four main benefits of using a network?
2. Compare and contrast LAN and WAN.
3. Explain the differences between client/server and peer-to-peer networks.
4. Draw and describe the star network topology.
5. What are the advantages and disadvantages of fiber-optic cables?
6. How does a switch differ from a hub in terms of data transmission?
7. Why is TCP/IP considered the most popular network protocol?

Remember to review these notes regularly and try to visualize or draw out the network topologies and hardware connections to reinforce your understanding.
