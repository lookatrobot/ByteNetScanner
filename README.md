# ByteNetScanner.

![Alt Text](https://github.com/x4ldr1t89z/ByteNetScanner./blob/main/image.png)

ByteNetScanner is a suite of scripts designed for fast and efficient network discovery, IP address validation, domain lookups, and much more.

## Features:
1. Ping Sweep: Efficiently check the status of multiple IPs using a ping test, with support for CIDR notation, domain validation, and more.
2. Active Host Enumeration: Identify live hosts in a network, including OS detection, MAC address retrieval, and ping-based host checks.
3. DNS Lookup: Perform both forward and reverse DNS lookups for IPv4 and IPv6 addresses. Detect and handle multiple inputs and resolve unknown domains.
4. Subnet Mask Discovery: Discover the subnet mask for a given range of IPs and calculate network masks.
5. Traceout Analysis: Traceroute analysis using ICMP, TCP, or UDP protocols, with geolocation data for each hop and broadcast address detection.
6. Port Scanning: Scan a range of ports on a target system using multi-threaded parallel scanning for speed.

## Required Dependencies:
- Update the linux:
```bash
sudo apt update
```
- For installing Python 3:
```bash
sudo apt install python3
```
- For network scanning and traceroute functionality:
```bash
pipx install scapy
```
- For making HTTP requests to get geolocation data:
```bash
pipx install requests
```
## Installation:
- Clone the repository to your local machine:
```bash
git clone https://github.com/neooverride/ByteNetScanner.git
```
- Navigate into the project directory:
```bash
cd ByteNetScanner
```
## Usage:
Once the setup is complete, you can run the main.py script.
```bash
sudo python main.py
```
## 𓂃🖊 Future Enhancements:
I will update this project `ByteNetScanner` in the future to make it more advanced and capable of bypassing firewalls.
