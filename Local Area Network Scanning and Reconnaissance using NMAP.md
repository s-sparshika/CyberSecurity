# Use the tool NMAP [Command line only]to perform the below task. Run Wireshark in the background and capture only the necessary packets to showcase for the corresponding question.

### NMAP is an open-source monitoring tool that can help scan and discover networks and network problems respectively. Nmap is very flexible, portable, well-documented, and easy to use. 

## a) Explain the subnet and use the NMAP Command to scan the services for the whole subnet.
### A subnet, or subnetwork, is a segmented piece of a larger network. More specifically, subnets are a logical partition of an IP network into multiple, smaller network segments. The Internet Protocol (IP) is the method for sending data from one computer to another over the internet. Each computer, or host, on the internet has at least one IP address as a unique identifier.

## b) What is a firewall andmention its types. Use the NMAP command to detect that a firewall protects the host.

<p align="center">
  <img src="https://static.javatpoint.com/tutorial/firewall/images/types-of-firewall.png" width="250" alt="dnsenum"/> <br/>
</p>

### A Firewall is a network security device that monitors and filters incoming and outgoing network traffic based on an organization’s previously established security policies. At its most basic, a firewall is essentially the barrier that sits between a private internal network and the public Internet. A firewall’s main purpose is to allow non-threatening traffic in and to keep dangerous traffic out.
### The following are types of firewall techniques that can be implemented as software or hardware:
- Packet-filtering Firewalls
- Circuit-level Gateways
- Application-level Gateways (Proxy Firewalls)
- Stateful Multi-layer Inspection (SMLI) Firewalls
- Next-generation Firewalls (NGFW)
- Threat-focused NGFW
- Network Address Translation (NAT) Firewalls
- Cloud Firewalls
- Unified Threat Management (UTM) Firewalls


## c) Use the NMAP command to scan a network and determine which devices are up and running.

## d) What are vertical and horizontal scanning?
### Port scanning is a method of detecting vulnerable nodes in a network by accessing different ports on a host (a device connected to the network) or the same port on different hosts. It can be used by cybercriminals in the preparatory phase of an attack to harvest information about the target host, as well as by information security experts as a tool for locating vulnerable nodes in IT infrastructure.
### Types of port scanning

<p align="center">
  <img src="https://images.slideplayer.com/31/9668175/slides/slide_34.jpg" width="250" alt="dnsenum"/> <br/>
</p>

- Horizontal scanning or network scanning sends requests to the same port on different hosts. Attackers use horizontal scanning to prepare for a mass attack.

<p align="center">
  <img src="https://images.slideplayer.com/31/9668175/slides/slide_36.jpg" width="250" alt="dnsenum"/> <br/>
</p>

- Vertical scanning sends requests to different ports on the same host. Attackers typically use vertical scanning to look for vulnerabilities in a preselected target.

## e) Use the NMAP command to scan multiple hosts. [HINT: Add hosts into a file and scan it].

## f) Use NMAP commands to export the output inXML format.
## g) Use the NMAP command to getOS information about a host. 
## h) Explain ping sweeping and Perform ping sweeping using Nmap.

# Try these below questions after completing the above commands.
## 1.What is a web application firewall? How do you use Nmap to detect a WAF? Perform WAF fingerprint detection using NMAP.
## 2.What is EXIF data? Tryto find EXIF data of images on a website using NMAP NSE. 
## 3.Use NMAP NSE to find all subdomains of the website. 
## 4.Perform a vulnerability scan on the target host using NMAP NSE.
