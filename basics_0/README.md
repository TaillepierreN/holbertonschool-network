# Networking basics #0
**Novice**  
**Weight: 1**  


## Resources
Read or watch:

- [OSI model](https://en.wikipedia.org/wiki/OSI_model)
- [Different types of network](https://www.youtube.com/watch?v=ul2GzADyHZM)
- [LAN network](https://www.cisco.com/c/en/us/solutions/small-business/resource-center/networking/lan-network.html)
- [WAN network](https://www.cisco.com/c/en/us/solutions/enterprise-networks/what-is-a-wan.html)
- [Internet](https://en.wikipedia.org/wiki/Internet)
- [MAC address](https://www.lifewire.com/what-is-a-mac-address-817979)
- [What is an IP address](https://www.avast.com/c-what-is-an-ip-address)
- [Private and public address](https://www.iplocation.net/public-vs-private-ip-address)
- [IPv4 and IPv6](https://www.webopedia.com/insights/ipv6-ipv4-difference/)
- [Localhost](https://en.wikipedia.org/wiki/Localhost)
- [TCP and UDP](https://www.howtogeek.com/190148/htg-explains-what-is-the-difference-between-tcp-and-udp/)
- [TCP/UDP ports List](https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers)
- [What is ping /ICMP](https://www.infobyip.com/ping.php)

man or help:
- netstat
- ping

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### OSI Model
- What it is
- How many layers it has
- How it is organized

### What is a LAN
- Typical usage
- Typical geographical size

### What is a WAN
- Typical usage
- Typical geographical size

### What is the Internet

### What is an IP address
- What are the 2 types of IP address

### What is localhost

### What is a subnet

### Why IPv6 was created

### TCP/UDP
- What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)
- What is the main difference between TCP and UDP
- What is a port
  - Memorize SSH, HTTP and HTTPS port numbers
- What tool/protocol is often used to check if a device is connected to a network

## Requirements
General:
- Allowed editors: vi, vim, emacs
- All your Bash script files will be interpreted on Ubuntu 20.04 LTS
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- Your Bash script must pass shellcheck without any error
- The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
- The second line of all your Bash scripts should be a comment explaining what is the script doing

## Tasks
### 0. OSI model
What is the OSI model? How is the OSI model organized?

### 1. Types of network
What type of network a computer in local is connected to? What type of network could connect an office in one building to another office in a building a few streets away?

### 2. MAC and IP address
What is a MAC address? What is an IP address?

### 3. UDP and TCP
Which statement is correct for the TCP box? Which statement is correct for the UDP box? Which statement is correct for the TCP worker?

### 4. TCP and UDP ports
Write a Bash script that displays listening ports.

### 5. Is the host on the network
Write a Bash script that pings an IP address passed as an argument.

