# <p align="center"> Tools in Kali </p>
<p align="center">
          <img src="https://i.stack.imgur.com/Gns38.png" width="400" alt="kali linux"/> <br/>
</p>

#### Kali linux is a Debian-based Linux distribution that is maintained by offensice Security. It was developed by Mati Aharoni and Devon kearns. Its a sepecially built operating system for network analysts, penetration tester and other fields of Cyber Security and analysis.

#### When performing penetration testing or hacking, we may need to automate our operations because there may be hundreds of conditions and payloads to test, and testing them manually is tedious. To save time, we use tools that come pre-installed with Kali Linux, they not only save our time but also capture reliable data and output precise results. Kali Linux comes packed with more than 350 tools which is useful for hacking or penetration testing.

# 1.Information Gathering 
## DNS Analysis

<p align="center">
  <img src="https://www.kali.org/tools/dnsenum/images/dnsenum-logo.svg" width="250" alt="dnsenum"/> <br/>
</p>

### dnsenum
- DNSenum stands for "Domain name server enumeration".
- Dnsenum is multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks.
- This tool is used to scan and gather all the information related to the target.
- The alternative for this tool is Dmitry.

<p align="center">
  <img src="https://www.kali.org/tools/dnsrecon/images/dnsrecon-logo.svg" width="250" alt="dnsrecon" <br/>
</p>

### dnsrecon
- DNSRecon is used to gather DNS information gahtering part for a penetration testing and was developed by a python script.
- Gathers all information on the records and target server by not effecting any IP addresses which in results in best to use for chechking on or disclose the information of any network.
- It checks for wildcard resolution.
- Performs a PTR Record lookup for a given IP range or CIDR.

<p align="center">
  <img src="https://www.kali.org/tools/fierce/images/fierce-logo.svg" width="250" alt="fierce"/> <br/>
</p>

### fierce
- Fierce is a semi-lightweight scanner that helps locate non-contiguous IP space and hostnames against specified domains.
- Used to locate non-contiguous IP space and hostnames across networks.
- Fierce is far more than just a simple IP scanner or a DDoS tool. It is a great reconnaissance tool.
- Capable of scanning for domains within minutes, Fierce is becoming the preferred tool for performing vulnerability checks in large networks.


## IDS/IPS identification

<p align="center">
  <img src="https://www.kali.org/tools/lbd/images/lbd-logo.svg" width="250" alt="lbd"/> <br/>
</p>

### lbd
- Used to test if the target domain is using a load balancer. 
- Load balancing can be done to evenly distribute workload through a series of Computer clusters or it can be used within a single system to balance connections across a set of network interface cards or disks.
- HTTP & DNS load balancing is done when a website has got a lot of incoming traffic like an e-Commerce website example would be Facebook or Google itself.
- Eliminates inconsistency results.

<p align="center">
  <img src="https://www.kali.org/tools/wafw00f/images/wafw00f-logo.svg" width="250" alt="wafw00f"/> <br/>
</p>

### wafw00f
- A python script, which is capable of detecting the web application firewall (WAF).
- Useful when the penetration tester wants to inspect the target web application server and might get a fallback with certain vulnerability assessment techniques, for which the web application is actively protected by a firewall.
- This detects the firewall sitting in between application server and internet traffic improving the testing strategy.
- Using this we could further investigate the possible ways ti bypass WAF.

## Live Host Identification

<p align="center">
  <img src="https://www.kali.org/tools/arping/images/arping-logo.svg" width="250" 
  alt="arping"/> <br/>
</p>

### arping
- Image result for arping kali linux.
- The arping utility sends ARP and/or ICMP requests to the specified host and displays the replies. 
- The host may be specified by its hostname, its IP address, or its MAC address.
- Use to send ARP pings from source MAC.

<p align="center">
  <img src="https://www.kali.org/tools/fping/images/fping-logo.svg" width="250" 
  alt="fping"/> <br/>
</p>

### fping
- fping stands for fast ping.
- Its a ping like program which uses Internet Control Message Protocol (ICMP) echo request to determine if a target host is responding.
- Differentiation with the regular ping is that it gives us the ability to scan a list of hosts (either coming from a file, an IP range, or a subnet) and tells you which ones are alive.
-  differentiation with the regular ping is that it gives you the ability to scan a list of hosts (either coming from a file, an IP range, or a subnet) and tells you which ones are alive.

<p align="center">
  <img src="https://www.kali.org/tools/hping3/images/hping3-logo.svg" width="250"
  alt="hping"/> <br/>
</p>

### hping3
- hping is an open-source packet generator and analyzer for the TCP/IP protocol
- hping3 is a network tool able to send custom ICMP/UDP/TCP packets and to display target replies like ping does with ICMP replies.
- Handles fragmentation and arbitrary packet body and size, and can be used to transfer files under supported protocols.
- Different usage of hping3 : Send TCP packets to a host, Send SYN packets to the target, Send FIN/ACK packets to the target host, Enable raw IP mode, Send ICMP packets to the target.
- It also uses TCP SYN Scan port number 80 on google.
 
## Network & Port Scanners

<p align="center">
  <img src="https://www.kali.org/tools/masscan/images/masscan-logo.svg" width="250" alt="masscan"/> <br/>
</p>

### masscan
- MASSCAN is TCP port scanner which transmits SYN packets asynchronously and produces results similar to nmap.
- Internally, it operates more like scanrand, unicornscan, and ZMap, using asynchronous transmission. It's a flexible utility that allows arbitrary address and port ranges.
- Masscan is a tool basically used for fast scans of large no of targets i.e Masscan -- 1000 Times Faster.
- It scan the entire internet when it transmits at a speed of 10 million packets per second.

<p align="center">
  <img src="https://www.kali.org/tools/nmap/images/nmap-logo.svg" width="250" 
  alt="nmap"/> <br/>
</p>

### nmap
- Nmap means a utility that is widely used by penetration testers for network discovery and system security audits.
- It supports ping scanning , many port scanning techniques, version detection , and TCP/IP fingerprinting.
- Users find Nmap useful for various activities, including network inventory, service uptime tracking, managing schedules, host monitoring, etc.
- Hackers uses Nmap because it can be used to gain access to uncontrolled ports on the network that may lead to providing access to the system. The hackers run the commands to get into the targeted system and can exploit the vulnerabilities of that system.

## OSINT Analysis

<p align="center">
  <img src="https://www.kali.org/tools/spiderfoot/images/spiderfoot-logo.svg" width="250" alt="spiderfoot"/> <br/>
</p>

### spiderfoot
- SpiderFoot is a reconnaissance tool that automatically queries over 100 public data sources (OSINT) to gather intelligence on IP addresses, domain names, e-mail addresses, names and more.
- It identifies low hanging fuit and reveals long-forgotten or unmanaged IT assets. - --- SpiderFoot can be used to continuously monitor OSINT data sources, and detect new intelligence about our organization.
- Spiderfoot HX allows scans to be conducted either passively or by targeting the domain directly. A passive search collects data from third party sources but never touches the target directly. This can be useful if you don't want the target to have any indication of your scan in their logs.

<p align="center">
  <img src="https://www.kali.org/tools/theharvester/images/theharvester-logo.svg" width="250" alt="theharvester"/> <br/>
</p>

### theharvester
- theHarvester is a command-line tool included in Kali Linux that acts as a wrapper for a variety of search engines and is used to find email accounts, subdomain names, virtual hosts, open ports / banners, and employee names related to a domain from different public sources (such as search engines and PGP key servers)
- Has the capability of doing DNS brute force, reverse IP resolution, and Top-Level Domain (TLD) expansion.

## Route Analysis

<p align="center">
  <img src="https://d4.alternativeto.net/-1FoJMwxFp2FsUW2TKOMnIl0kpRCMsf6g7R1Mf8fV-E/rs:fill:280:280:0/g:ce:0:0/YWJzOi8vZGlzdC9pY29ucy9uZXRkaXNjb3Zlcl8yMDQxMTkucG5n.png" width="250" alt="netdiscover"/> <br/>
</p>

### netdiscover
- Used to gather all the important information about the network. It gathers information about the connected clients and the router.
- Uses ARP protocol
- The netdiscover is a quicker and simplest program to use, but it doesn't show very detailed information about the target clients. It'll only show us their IP address, their MAC address, and sometimes the hardware manufacturer.
- The ranges of Netdiscover allowed range: 2 to 253, default 66 -S Enable sleep time suppression between each request. If set, netdiscover will sleep after having scanned 255 hosts instead of sleeping after each one.

<p align="center">
  <img src="https://www.kali.org/tools/netmask/images/netmask-logo.svg" width="250" alt="netmask"/> <br/>
</p>

### netmask
- This is a tiny program handy if you work with firewalls or routers occasionally.
- It can determine the smallest set of network masks to specify a range of hosts. It can also convert between common IP netmask and address formats.
- netmask 255.255 255.0 means that A class C network would have a subnet mask of 255.255. 255.0 which means that 24 bits are used for the network. In CIDR notation this is designated by a /24 following the IP address.
- To change netmask in Linux: To specify a subnet mask for an interface, enter the following command: ifconfig interface_name netmask mask. To change the subnet mask for an interface that has been configured with a primary and an alias address, enter the following command for each IP address: ifconfig interface_name IP address netmask mask

## SMB Analysis
- **enum4linux**
- **nbtscan**
- **smbmap**
## SMTP Analysis
- **swaks**
## SNMP Analysis
- **61 onesixtyone**
- **snamp-check**
## SSL Analysis
- **dmitry**
- **netdiscover**
- **spiderfoot**

# 2. Vulnerability Analysis
## Fuzzing Tools
- **SPIKE**
## VoIP Tools
- **voiphopper**
## legion
## nikto
## nmap
## unix-prives-check

# 3.Web Application Analysis
## CMS & Framework Identification
- **wpscan**
## Web Application Proxies
- **burpsuite**
- **cutycapt**
- **dirb**
## Web Vulnerability Scanners
- **commix**
- **skipfish**
- **sqlmap**

# 4.Database Assessment

<p align="center">
  <img src="https://www.kali.org/tools/sqlitebrowser/images/sqlitebrowser-logo.svg" width="250" alt="SQLitedatabasebrowser"/> <br/>
</p>

## SQLite database browser
- SQLite Database Browser is a visual tool used to create, design and edit database files compatible with SQLite.
- Its interface is based on QT, and is meant to be used for users and developers that want to create databases, edit and search data using a familiar spreadsheet-like interface, without the need to learn complicated SQL commands.
- Its interface is based on QT, and is meant to be used for users and developers that want to create databases, edit and search data using a familiar spreadsheet-like interface, without the need to learn complicated SQL commands.

# 5.Password Attacks
## offline Attacks
- **hashcat**
- **hashid**
- **ophcrack-cli**
## Online Attack
- **hydra**
- **patator**
- **thc-pptp-bruter**
## Passinth the Hash Tools
- **mimikatz**
- **smbmap**
## Password Profiling & Wordlists
- **cewl**
- **john**
- **ophcrack**


# 6.Wireless Attacks
## 802.11 Wireless Tools
- **bully**
- **fern wifi cracker (root)**
## Bluetooth Tools
- **aircrack-ng**
- **kismet**
- **reaver**

# 7.Reverse Engineering
- **clang**
- **NASM shell**
- **radare2**

# 8.Exploitation Tools
- **crackemapexec**
- **metasploit framework**
- **msf payload creator**

# 9.Sniffing & Spoofing
## ettercap-graphical
## minicom
## macchanger
## mitmproxy
## responder
## Network Sniffers
- **dnschef**
- **netsniff-ng**
## Spoofing & MITM
- **rebind**
- **sslsplit**
- **tcpreplay**

# 10.Post Exploitation
## mimikatz
## evil-winrm
## exe2hex
## OS Backdoor
- **dbd**
- **powersploit**
- **sbd**
## Tunneling & Exfiltration
- **proxychains4**
- **miredo**
- **stunnel4**
## Web Backdoors
- **laudanum**
- **weevely**

# 11.Forensics
## binwalk
## bulk_extractor
## hashdeep

## Forensic Carving Tools
### magicresue
### scalpel
### scrounge-ntfs

## Forensic Imaging Tools
### guymanager(root)
## PDF Forensics Tools
### pdfid
### pdf-parser

## Sleuth Kit Suite
### autopsy(root)
### hfind
### img_Cat

# 12.Reporting Tools

<p align="center">
  <img src="https://www.kali.org/tools/cutycapt/images/cutycapt-logo.svg" width="250" alt="cutycapt"/> <br/>
</p>

## cutycapt
- CutyCapt is a small cross-platform command-line utility to capture WebKit's rendering of a web page into a variety of vector and bitmap formats, including SVG, PDF, PS, PNG, JPEG, TIFF, GIF, and BMP.
- cannot use CutyCapt without an X server, but you can use e.g. Xvfb as light-weight server if you are not running an interactive graphical desktop environment.

<p align="center">
  <img src="https://www.kali.org/tools/python-faraday/images/python-faraday-logo.svg" width="250" alt="faraday start"/> <br/>
</p>

## faraday start
- Faraday IDE is another tool built to support collaboration while utilizing approximately 40 built-in tools for generating reports.
- Faraday is a GUI application that consists of a ZSH terminal and a sidebar with details about our workspaces and hosts.
- When Faraday supports the command you are running, it will automatically detect it and import the results.

<p align="center">
  <img src="https://www.kali.org/tools/pipal/images/pipal-logo.svg" width="250" 
       alt="pipal"/> <br/>
</p>

## pipal
- This tool does is to give you the stats and the information to help you analyse the passwords.
-  The real work is done by you in interpreting the results.

<p align="center">
  <img src="https://www.kali.org/tools/recordmydesktop/images/recordmydesktop-logo.svg" width="250" alt="recordmydesktop"/> <br/>
</p>

## recordmydesktop
- The application produces an ogg-encapsulated theora-vorbis file.
-  recordMyDesktop tries to be as unobstrusive as possible by proccessing only regions of the screen that have changed.


# 13.Social Engineering Tools

<p align="center">
  <img src="https://www.kali.org/tools/msfpc/images/msfpc-logo.svg" width="250" 
       alt="MPC"/> <br/>
</p>

## msf payload creator
- MSFvenom Payload Creator (MSFPC) is a wrapper to generate multiple types of payloads, based on the user's choice. The idea is to be as simple as possible (only requiring one input) to produce their payload. 
- list payloads with the loadpath command
- The only necessary input from the user should be defining the payload they want by either the platform (e.g. windows), or the file extension they wish the payload to have (e.g. exe).

<p align="center">
  <img src="https://www.kali.org/tools/set/images/set-logo.svg" width="250" 
       alt="SET"/> <br/>
</p>

## social engineering toolkit (root)
- The Social-Engineer Toolkit (SET) is an open-source penetration testing framework designed for social engineering. 
- SET has a number of custom attack vectors that allow you to make a believable attack in a fraction of time. These kind of tools use human behaviors to trick them to the attack vectors.












