# task5-wireshark
# Task 5: Network Traffic Capture & Analysis using Wireshark

## 🎯 Objective:
Capture live packets on my local network and analyse traffic using Wireshark filters and protocol inspection.

---

## 🛠 Tool Used:
- Wireshark (Free network protocol analyzer)

---

## 🔄 Steps Performed:

1. Installed Wireshark and selected the active network interface
2. Captured live packets while browsing websites and pinging servers
3. Stopped the capture after one minute
4. Applied filters to view specific protocols (HTTP, DNS, TCP)
5. Exported the capture as a `.pcap` file for documentation

---

## 🔍 Protocols Identified:

### 1. HTTP (HyperText Transfer Protocol)
- Used for communication between web browsers and websites
- Found during browsing sessions

### 2. DNS (Domain Name System)
- Resolves human-readable domains (e.g., google.com) to IP addresses
- Captured when loading websites

### 3. TCP (Transmission Control Protocol)
- Reliable, connection-oriented transport protocol
- Seen across most application traffic like HTTP, HTTPS

---

## 📸 Screenshots:

- Packet capture start and stop
- Filters applied (icmp, DNS, TCP)

---

## 📁 PCAP File:
- Saved as `task5-network-capture.pcap` and uploaded to the root of this repo

---

## 📚 Learning Outcome:
- Understood how to capture live traffic
- Learned to analyze different protocol layers
- Practiced using filters and exporting data in Wireshark
