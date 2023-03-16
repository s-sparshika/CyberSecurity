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

<p align="center">
  <img src="https://www.kali.org/tools/enum4linux/images/enum4linux-logo.svg" width="250" alt="enum4"/> <br/>
</p>

### enum4linux
- Enum4linux is a tool for enumerating information from Windows and Samba systems. 
- It attempts to offer similar functionality to enum.exe. It is written in PERL and is basically a wrapper around the Samba tools smbclient, rpclient, net and nmblookup.
- Enum4linux is an enumeration tool capable of detecting and extracting data from Windows and Linux operating systems, including those that are Samba (SMB) hosts on a network. 
- Enum4linux is capable of discovering the following: Password policies on a target. The operating system of a remote target.

<p align="center">
  <img src="https://www.kali.org/tools/nbtscan/images/nbtscan-logo.svg" width="250" alt="nbtscan"/> <br/>
</p>

### nbtscan
- nbtscan - NETBIOS nameserver scanner.
- NetBIOS is a service that allows for communication over a network and is often used to join a domain and legacy applications.
-  It is an older technology but still used in some environments today. Since it is an unsecured protocol, it can often be a good starting point when attacking a network.

<p align="center">
  <img src="https://www.kali.org/tools/smbmap/images/smbmap-logo.svg" width="250" 
       alt="smbmap"/> <br/>
</p>

### smbmap
- Feature description. The Server Message Block (SMB) protocol is a network file sharing protocol that allows applications on a computer to read and write to files and to request services from server programs in a computer network. 
- The SMB protocol can be used on top of its TCP/IP protocol or other network protocols
- SMBMap allows users to enumerate samba share drives across an entire domain.
-  List share drives, drive permissions, share contents, upload/download functionality, file name auto-download pattern matching, and even execute remote commands.

## SMTP Analysis

<p align="center">
  <img src="https://www.kali.org/tools/swaks/images/swaks-logo.svg" width="250" 
       alt="swaks"/> <br/>
</p>

### swaks
- Options can be given to swaks in three ways. They can be specified in a configuration file, in environment variables, and on the command line.
- Use Swaks to send emails through the Email Delivery service.
- Swaks (Swiss Army Knife SMTP) is a transaction-based tool you can use to test SMTP configurations in Email Delivery. Before use Swaks, you must configure Email Delivery and take note of your SMTP sending information and SMTP credentials.

## SNMP Analysis

<p align="center">
  <img src="https://www.kali.org/tools/onesixtyone/images/onesixtyone-logo.svg" width="250" alt="61 onesixtyone"/> <br/>
</p>

### 61 onesixtyone
- onesixtyone is a simple SNMP scanner which sends SNMP requests for the sysDescr value asynchronously with user-adjustable sending times and then logs the responses which gives the description of the software running on the device.
- Running onesixtyone on a class B network with -w 10 gives a performance of 3 seconds per class C, with no dropped packets, and all 65536 IP addresses were scanned in less than 13 minutes.
- Fast and simple SNMP scanner.

## SSL Analysis

<p align="center">
  <img src="https://www.kali.org/tools/dmitry/images/dmitry-logo.svg" width="250" 
       alt="dmitry"/> <br/>
</p>

### dmitry
- Dmitry stands for DeepMagic Information Gathering Tool. Dmitry is a free and open-source tool that is available on GitHub. We used this tool for information gathering. Dmitry is a command-line tool. 
- DMitry is a UNIX/(GNU)Linux command line application written in C.
- DMitry can find possible subdomains, email addresses, uptime information, perform tcp port scan, whois lookups, and more.
- Dmitry stands for DeepMagic Information Gathering Tool. Dmitry is a free and open-source tool that is available on GitHub. We used this tool for information gathering. Dmitry is a command-line tool. 

# 2. Vulnerability Analysis
## Fuzzing Tools

<p align="center">
  <img src="https://www.kali.org/tools/spike/images/spike-logo.svg" width="250"
       alt="SPIKE"/> <br/>
</p>

### SPIKE
- When we need to analyze a new network protocol for buffer overflows or similar weaknesses, the SPIKE is the tool of choice for professionals.
- A spike, a term often used in SAFe, scrum and other agile frameworks, is a task designed to answer a question or gather information, rather than produce a product.
- Their purpose is to gain the knowledge necessary to reduce the risk of a technical approach, better understand a requirement, or increase the reliability of a story estimate. 
- spikes are estimated and then demonstrated at the end of the Iteration.

## VoIP Tools

<p align="center">
  <img src="https://www.kali.org/tools/voiphopper/images/voiphopper-logo.svg" width="250" alt="voiphopper "/> <br/>
</p>

### voiphopper
- VoIP Hopper is a GPLv3 licensed security tool, written in C that rapidly runs a VLAN Hop security test.
-  VoIP Hopper is a VoIP infrastructure security testing tool but also a tool that can be used to test the (in)security of VLANs. 
-  VoIP Hopper is a network infrastructure penetration testing tool to test the (in)security of VLANS as well as mimic the behavior of IP Phones to automatically VLAN Hop and demonstrate risks within IP Telephony network infrastructures..

<p align="center">
  <img src="https://www.kali.org/tools/legion/images/legion-logo.svg" width="250" 
       alt="legion"/> <br/>
</p>

## legion
- Legion, a fork of SECFORCE's Sparta, is an open source, easy-to-use, super-extensible, and semi-automated network penetration testing framework that aids in discovery, reconnaissance, and exploitation of information systems.
- Legion, a fork of SECFORCE's Sparta, is an open source, easy-to-use, super-extensible, and semi-automated network penetration testing framework that aids in discovery, reconnaissance, and exploitation of information systems.
- It has the feature of real-time auto-saving of project results and tasks.
- Modular functionality of Legion Tool allows users to easily customize Legion.

<p align="center">
  <img src="https://www.kali.org/tools/nikto/images/nikto-logo.svg" width="250" 
       alt="nikto"/> <br/>
</p>

## nikto
- - Nikto is a free software command-line vulnerability scanner that scans webservers for dangerous files/CGIs, outdated server software and other problems. 
- It performs generic and server type specific checks.
- Nikto is a pluggable web server and CGI scanner written in Perl, using rfp's LibWhisker to perform fast security or informational checks. Features: Easily updatable CSV-format checks database.
- Output reports in plain text or HTML. Available HTTP versions automatic switching.

<p align="center">
  <img src="https://www.kali.org/tools/unix-privesc-check/images/unix-privesc-check-logo.svg" width="250" alt="unix-prives-check"/> <br/>
</p>

## unix-prives-check
- Unix-privesc-checker is a script that runs on Unix systems.
- It tries to find misconfigurations that could allow local unprivilged users to escalate privileges to other users or to access local apps (e.g. databases).
- It’s intended to be run by security auditors and pentetration testers against systems they have been engaged to assess, and also by system admnisitrators who want to check for “obvious” misconfigurations. 
- It can even be run as a cron job so you can check regularly for misconfigurations that might be introduced.

# 3.Web Application Analysis

## CMS & Framework Identification

<p align="center">
  <img src="https://www.kali.org/tools/wpscan/images/wpscan-logo.svg" width="250" 
       alt="wpscan"/> <br/>
</p>

### wpscan
- WPScan scans remote WordPress installations to find security issues.
- Wpscan is a vulnerability scanning tool, which comes pre-installed in Kali Linux. This scanner tool scans for vulnerabilities in websites that run WordPress web engines.
- The wpscan tool itself isn't a malicious tool, as it is only for reconnaissance against a particular site.

## Web Application Proxies

<p align="center">
  <img src="https://www.kali.org/tools/burpsuite/images/burpsuite-logo.svg" width="250" alt="burpsuite"/> <br/>
</p>

### burpsuite
- Burp Suite is a fully featured web application attack tool: it does almost anything that you could ever want to do when penetration testing a web application.
- Burp Suite is an integrated platform for performing security testing of web applications. Its various tools work seamlessly together to support the entire testing process, from initial mapping and analysis of an application's attack surface, through to finding and exploiting security vulnerabilities.
- We can tweak the raw HTTP in various ways before forwarding the request on to the web server.
-  The goal with the Burp intercepting proxy feature is to tweak requests so they still follow the rules of HTTP, but can make the application act unexpectedly.

<p align="center">
  <img src="https://www.kali.org/tools/dirb/images/dirb-logo.svg" width="250" 
       alt="dirb"/> <br/>
</p>

### dirb
- DIRB is a Web Content Scanner. It looks for existing (and/or hidden) Web Objects. 
- Works by launching a dictionary based attack against a web server and analyzing the responses. DIRB comes with a set of preconfigured attack wordlists for easy usage but you can use your custom wordlists.
- DIRB can recursively scan directories and look for files with different extensions in a web server.
- It can automatically detect the Not Found code when it's not the standard 404. It can then export the results to a text file, use session cookies in case the server requires having a valid session, and conduct basic HTTP authentication and upstream proxy among other features.

## Web Vulnerability Scanners

<p align="center">
  <img src="https://www.kali.org/tools/commix/images/commix-logo.svg" width="250" 
       alt="commix"/> <br/>
</p>

### commix
- Command injection exploiter (commix) is an automated tool written in Python that is pre-compiled in Kali Linux to perform various OS commands if the application is vulnerable to command injection. 
- It allows attackers to inject into any specific vulnerable parts of the application, or even into an HTTP header.
- It has a simple and it can be used, from web developers, penetration testers or even security researchers to test web applications with the view to find bugs, errors or vulnerabilities related to command injection attacks.

<p align="center">
  <img src="https://www.kali.org/tools/skipfish/images/skipfish-logo.svg" width="250" alt="skipfish"/> <br/>
</p>

### skipfish
- Skipfish is an active web application security reconnaissance tool.
- It prepares an interactive sitemap for the targeted site by carrying out a recursive crawl and dictionary-based probes.
- The resulting map is then annotated with the output from a number of active security checks.
- This tool is meant to provide accurate and meaningful results. Three-step differential probes are preferred to signature checks for detecting vulnerabilities.

<p align="center">
  <img src="https://www.kali.org/tools/sqlmap/images/sqlmap-logo.svg" width="250" 
       alt="sqlmap"/> <br/>
</p>

### sqlmap
- sqlmap is an open source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers.
- SQLMap is a tool used for the automated exploitation of SQL injection vulnerabilities.
- We can use SQLMap to test websites and databases for vulnerabilities and exploit those vulnerabilities to take over the database. 
- To use SQLMap, we first need to identify a website or database that is vulnerable to SQL injection 

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

<p align="center">
  <img src="https://www.kali.org/tools/hashcat/images/hashcat-logo.svg" width="250" alt="hashcat"/> <br/>
</p>

### hashcat
- World's fastest password cracker.
- Hashcat is an advanced free  multi-threaded password recovery tool and it is world's fastest password cracker and recovery utility, which supports multiple unique attack modes of attacks for more than 200 highly optimized hashing algorithms.
- Hashcat currently supports CPUs and GPUs and other hardware accelerators on Linux, Windows, and OSX, and has facilities to help enable distributed password cracking.
- Hashcat offers multiple unique attack modes for cracking passwords. Those are following: 
Brute-Force attack
Combinator attack
Dictionary attack
Fingerprint attack
Hybrid attack

<p align="center">
  <img src="https://www.kali.org/tools/hashid/images/hashid-logo.svg" width="250" 
       alt="hashId"/> <br/>
</p>

### hashid
- hashID is a tool written in Python 3. x which supports the identification of over 175 unique hash types using regular expressions. It is able to identify a single hash or parse a file and identify the hashes within it.
- Using a tool called hash-identifier, we can easily fingerprint any hashes to discover the right Hashcat mode to use to retrieve a password.
- Aside from cracking hashes, hash-identifier is also helpful for identifying which hashing algorithm is being used to provide a checksum value for a download.

<p align="center">
  <img src="https://www.kali.org/tools/ophcrack/images/ophcrack-logo.svg" width="250" alt="ophcrack-cli"/> <br/>
</p>

### ophcrack-cli
- Ophcrack is a Windows password cracker based on a time-memory trade-off using rainbow tables. 
- This is a new variant of Hellman's original trade-off, with better performance. It recovers 99.9% of alphanumeric passwords in seconds.
- Ophcrack is a free open-source (GPL licensed) program that cracks Windows log-in passwords by using LM hashes through rainbow tables.
- The program includes the ability to import the hashes from a variety of formats, including dumping directly from the SAM files of Windows

## Online Attack

<p align="center">
  <img src="https://www.kali.org/tools/hydra/images/hydra-logo.svg" width="250" 
       alt="hydra"/> <br/>
</p>

### hydra
- Hydra is a parallelized login cracker which supports numerous protocols to attack. It is very fast and flexible, and new modules are easy to add. 
- This tool makes it possible for researchers and security consultants to show how easy it would be to gain unauthorized access to a system remotely.
- Hydra is a brute-forcing tool that helps penetration testers and ethical hackers crack the passwords of network services. 
- Hydra can perform rapid dictionary attacks against more than 50 protocols

<p align="center">
  <img src="https://www.kali.org/tools/patator/images/patator-logo.svg" width="250" alt="patator"/> <br/>
</p>

### patator
- Patator is a command-line tool designed to brute force directories and files in web servers. It can be used to find hidden resources such as directories, files, and CGIs. 
- Patator is written in Python and is available for download from GitHub. Patator is developed and maintained by Gleg.
- Hashes are generated by single-way mathematical algorithms, that means they can't be reversed. So the only way to crack is to brute force them.

<p align="center">
  <img src="https://www.kali.org/tools/thc-pptp-bruter/images/thc-pptp-bruter-logo.svg" width="250" alt="thc-pptp-bruter"/> <br/>
</p>

### thc-pptp-bruter
- It is a brute force program against pptp vpn endpoints.
- Its a fully standalone. 
- Tested against Windows and Cisco gateways.

## Passinth the Hash Tools

<p align="center">
  <img src="https://www.kali.org/tools/mimikatz/images/mimikatz-logo.svg" width="250" alt="mimikatz"/> <br/>
</p>

### mimikatz
- Mimikatz is an open-source tool that both attackers and penetration testers can use to steal credentials and escalate privileges within Active Directory (AD). 
- The tool allows you to exploit various kinds of vulnerabilities in order to extract passwords, hashes, and Kerberos tickets from memory
- Mimikatz uses admin rights on Windows to display passwords of currently logged in users in plaintext.

## Password Profiling & Wordlists

<p align="center">
  <img src="https://www.kali.org/tools/cewl/images/cewl-logo.svg" width="250" 
       alt="cewl"/> <br/>
</p>

### cewl
- CeWL (Custom Word List generator) is a ruby app which spiders a given URL, up to a specified depth, and returns a list of words which can then be used for password crackers such as John the Ripper. 
- CeWL can also create a list of email addresses found in mailto links.
- Cewl also has an associated command-line app FAB, which uses the same metadata extraction techniques to generate author/producer lists from already downloaded files using information extraction algorithms like CeWL.

<p align="center">
  <img src="https://www.kali.org/tools/john/images/john-logo.svg" width="250" 
       alt="john"/> <br/>
</p>

### john
- John the Ripper is a tool designed to help systems administrators to find weak (easy to guess or crack through brute force) passwords, and even automatically mail users warning them about it, if it is desired.
- In addition to the “john” command, John comes with a few other utilities. One of them is called “unshadow”. The unshadow command combines the passwd and shadow files together into a single file. This can then be used by John to crack passwords
- John the Ripper cracks passwords. During the cracking process, John the Ripper uses a rainbow table approach where it takes words from an in-built dictionary that comes with it. It then compiles the variations of that dictionary and compares the hashed password to what is in the password file trying to find a match.

# 6.Wireless Attacks
## 802.11 Wireless Tools

<p align="center">
  <img src="https://www.kali.org/tools/bully/images/bully-logo.svg" width="250" alt="bully"/> <br/>
</p>

### bully
- Bully is a new implementation of the WPS brute force attack, written in C. It is conceptually identical to other programs, in that it exploits the design flaw in the WPS specification. 
- It has several advantages over the original reaver code.
- You can take a look at Brute Force Attack Against WPS – Reaver, to see its features and compare them to the Bully.

<p align="center">
  <img src="https://www.kali.org/tools/fern-wifi-cracker/images/fern-wifi-cracker-logo.svg" width="250" alt="fern wifi cracker"/> <br/>
</p>

### fern wifi cracker (root)
- Fern WiFi cracker, The name says about it. It's a GUI based WiFi security auditing tool that written on Python. 
- Fern WiFi cracker can crack and recover WEP/WPA/WPS keys and also run other network based attacks on wireless or Ethernet based networks. 
- Fern created by Saviour Emmanuel Ekiko.

## Bluetooth Tools

<p align="center">
  <img src="https://www.kali.org/tools/aircrack-ng/images/aircrack-ng-logo.svg" width="250" alt="aircrack"/> <br/>
</p>

### aircrack-ng
- Aircrack-ng is a tool that comes pre-installed in Kali Linux and is used for wifi network security and hacking. 
- Aircrack is an all in one packet sniffer, WEP and WPA/WPA2 cracker, analyzing tool and a hash capturing tool. It helps in capturing the package and reading the hashes out of them and even cracking those hashes by various attacks like dictionary attacks. 
- It supports almost all the latest wireless interfaces. 
- It mainly focuses on 4 areas:
Monitoring: Captures cap, packet, or hash files.
Attacking: Performs deauthentication or creates fake access points
Testing: Checking the wifi cards or driver capabilities
Cracking: Various security standards like WEP or WPA PSK

<p align="center">
  <img src="https://www.kali.org/tools/kismet/images/kismet-logo.svg" width="250" 
       alt="kismet"/> <br/>
</p>

### kismet
- Kismet is a wireless network and device detector, sniffer, wardriving tool, and WIDS (wireless intrusion detection) framework.
- Kismet works with Wi-Fi interfaces, Bluetooth interfaces, some SDR (software defined radio) hardware like the RTLSDR, and other specialized capture hardware.
- It is most often used for its “RFMON” or ”radio frequency monitoring” mode. 
- Kismet's ability to facilitate RFMON means that a user is able to monitor traffic and identify wireless networks without having to associate with an access point, which is common for Wireshark, NetScout or Aircrack packet-sniffing tools.

<p align="center">
  <img src="https://www.kali.org/tools/reaver/images/reaver-logo.svg" width="250" 
       alt="reaver"/> <br/>
</p>

### reaver
- Reaver performs a brute force attack against an access point's WiFi Protected Setup pin number. 
- Once the WPS pin is found, the WPA PSK can be recovered and alternately the AP's wireless settings can be reconfigured.
- The Reaver is a large, long, heavy hybrid of a dane axe and a scythe with a foldable blade, which will fold out when the user performs a certain attack.
- It functions like the Two-handed Weapons, albeit with some difference. The Reaver is used by the mini-boss Shroud and a Looter from the Factory.



# 7.Reverse Engineering

<p align="center">
  <img src="https://www.kali.org/images/kali-tools-icon-missing.svg" width="250" 
       alt="clang"/> <br/>
</p>

### clang
- Clang project is a C, C++, Objective C and Objective C++ front-end for the LLVM compiler.
-  Its goal is to offer a replacement to the GNU Compiler Collection (GCC).
-  Clang tool is a front end compiler that is used to compile programming languages such as C++, C, Objective C++ and Objective C into machine code. Clang is also used as a compiler for frameworks like OpenMP, OpenCL, RenderScript, CUDA and HIP.


<p align="center">
  <img src="https://www.kali.org/tools/metasploit-framework/images/metasploit-framework-logo.svg" width="250" alt="NASM shell"/> <br/>
</p>

### NASM shell
- Metasploit provides a great utility for writing short assembly codes using the NASM shell. 
- The generate_seh_record() method created an SEH frame automatically and used a small assembly code in the previous section; \xeb\x0a, which denoted a short jump of 12 bytes.
- However, in case of generation of a manual SEH record, instead of searching the internet for op codes, we can use the NASM shell to write assembly codes with ease.

<p align="center">
  <img src="https://www.kali.org/tools/radare2/images/radare2-logo.svg" width="250" alt="radare2"/> <br/>
</p>

### radare2
- Radare2 (also known as r2) is a complete framework for reverse-engineering and analyzing binaries; composed of a set of small utilities that can be used together or independently from the command line.
- It is composed by an hexadecimal editor (radare) with a wrapped IO layer supporting multiple backends for local/remote files, debugger , stream analyzer, assembler/disassembler (rasm) for x86, ARM, PPC, m68k, Java, MSIL, SPARC, code analysis modules and scripting facilities.
- Radare2 is an open-source framework for reverse engineering and binaries analysis that implements a rich command-line interface for disassembling, analyzing data, patching binaries, comparing data, searching, replacing, visualizing, and more. 
- It has great scripting capabilities, it runs on all major platforms.

# 8.Exploitation Tools

<p align="center">
  <img src="https://www.kali.org/tools/crackmapexec/images/crackmapexec-logo.svg" width="250" alt="crackemapexec"/> <br/>
</p>

## crackemapexec
- CrackMapExec (CME) is another post-exploitation tool that helps automate assessing the security of large Active Directory networks.
- This package is a swiss army knife for pentesting Windows/Active Directory environments. From enumerating logged on users and spidering SMB shares to executing psexec style attacks, auto-injecting Mimikatz/Shellcode/DLL's into memory using Powershell, dumping the NTDS. dit and more.
- CrackMapExec is an open-source tool that leverages Mimikatz to enable adversaries to harvest credentials and move laterally through an Active Directory environment. This blog post details how this tool works and offers a solution for defending against it.
- CME makes heavy use of the Impacket library and PowerSploit for working with network protocols and performing a variety of post-exploitation techniques.

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

<p align="center">
  <img src="https://www.kali.org/tools/binwalk/images/binwalk-logo.svg" width="250" alt="binwalk"/> <br/>
</p>

## binwalk
- Binwalk is a tool for searching a given binary image for embedded files and executable code. Specifically, it is designed for identifying files and code embedded inside of firmware images. 
- Binwalk uses the libmagic library, so it is compatible with magic signatures created for the Unix file utility.
- Binwalk is a popular command-line tool in Linux that is used for analyzing, reverse engineering, and extracting firmware images.
- Binwalk also includes a custom magic signature file which contains improved signatures for files that are commonly found in firmware images such as compressed/archived files, firmware headers, Linux kernels, bootloaders, filesystems, etc.

<p align="center">
  <img src="https://www.kali.org/tools/bulk-extractor/images/bulk-extractor-logo.svg" width="250" alt="bulk_extractor"/> <br/>
</p>

## bulk_extractor
- bulk_extractor is a C++ program that scans a disk image, a file, or a directory of files and extracts useful information without parsing the file system or file system structures. The results are stored in feature files that can be easily inspected, parsed, or processed with automated tools.
- The syntax for using bulk_extractor is quite simple and requires that an output folder (-o) and the forensic image be specified.

<p align="center">
  <img src="https://www.kali.org/tools/hashdeep/images/hashdeep-logo.svg" width="250" alt="hashdeep"/> <br/>
</p>

## hashdeep
- hashdeep is a set of tools to compute MD5, SHA1, SHA256, tiger and whirlpool hashsums of arbitrary number of files recursively.
- Hashdeep is a program for recursively computing hashes with multiple algorithms simultaneously. 
- It can also perform matching operations like the md5deep family of programs, but in a more powerful way. 
- Hashdeep can perform an audit of hashes against a set of known hashess.

## Forensic Carving Tools

<p align="center">
  <img src="https://www.kali.org/tools/magicrescue/images/magicrescue-logo.svg" width="250" alt="magicresue"/> <br/>
</p>

### magicresue
- MagicTree is a data management and reporting tool similar to Dradis. 
- Magic Rescue scans a block device for file types it knows how to recover and calls an external program to extract them. 
- It looks at “magic bytes” (file patterns) in file contents, so it can be used both as an undelete utility and for recovering a corrupted drive or partition.
- It is preinstalled on Linux and it organizes everything using a tree and node structure. It also allows us to execute commands and export the results as a report.

<p align="center">
  <img src="https://www.kali.org/tools/scalpel/images/scalpel-logo.svg" width="250" alt="scalpal"/> <br/>
</p>

### scalpel
- Is a fast file carver that reads a database of header and footer definitions and extracts matching files from a set of image files or raw device files.
- Once we have made our changes to include file types and saved the scalpel.conf file, we can then start Scalpel by clicking on the Show Applications button on the sidebar and enter scalpel into the search box which then appears at the top of the screen. 
- Once started, a Terminal opens showing the version number (1.60), the author (Golden G. Richard III), and as mentioned, states that it is based on Foremost 0.69. As seen with Foremost, Scalpel-usage syntax and additional options are also displayed

<p align="center">
  <img src="https://www.kali.org/tools/scrounge-ntfs/images/scrounge-ntfs-logo.svg" width="250" alt="scrounge-ntfs"/> <br/>
</p>

### scrounge-ntfs
- Scrounge NTFS is a data recovery program for NTFS filesystems. It reads each block of the hard disk and try to rebuild the original filesystem tree into a directory.
- This package is useful in forensics investigations.
- We can shrink an NTFS partition, first use ntfsresize to shrink the size of the filesystem. Then you could use fdisk(8) to shrink the size of the partition by deleting the partition and recreating it with the smaller size.
- linux will 100% corrupt our NTFS partition sooner or later.

## Forensic Imaging Tools

<p align="center">
  <img src="https://www.kali.org/tools/guymager/images/guymager-logo.svg" width="250" alt=" guymanager"/> <br/>
</p>

### guymanager(root)
- Guymager is another standalone acquisition tool that can be used for creating forensic images and also performing disk cloning.
- Guymager is a Qt-based forensic imager. It is capable of producing image files in EWF, AFF and dd format.
- Image acquisition is a must need process in digital forensic researches.
- With this process we can clone an entire disk like pen drives or hard disks or memory cards. We can copy a total disk with guymager.

## PDF Forensics Tools

<p align="center">
  <img src="https://www.kali.org/tools/pdfid/images/pdfid-logo.svg" width="250" 
       alt="pdfid"/> <br/>
</p>

### pdfid
- This tool is not a PDF parser, but it will scan a file to look for certain PDF keywords, allowing you to identify PDF documents that contain for example JavaScript or execute an action when opened. 
- PDFiD will also handle name obfuscation.

<p align="center">
  <img src="https://www.kali.org/tools/pdf-parser/images/pdf-parser-logo.svg" width="250" alt="pdf-parser"/> <br/>
</p>

### pdf-parser
- This tool will parse a PDF document to identify the fundamental elements used in the analyzed file. 
- It will not render a PDF document.
- A PDF Parser (also sometimes called PDF scraper) is a software that can be used to extract data from PDF documents. 
- PDF Parsers can come in form of libraries for developers or as standalone software products for end-users. 
- PDF Parsers are used mainly to extract data from a batch of PDF files.

<p align="center">
  <img src="https://www.kali.org/images/kali-tools-icon-missing.svg" width="250" 
       alt="Sleuth Kit Suite"/> <br/>
</p>

## Sleuth Kit Suite
- The Sleuth Kit® (TSK) is a library and collection of command line tools that allow you to investigate disk images. 
- The core functionality of TSK allows you to analyze volume and file system data.
- Usage and audience. The Sleuth Kit is commonly used for criminal investigations, digital forensics, or file system analysis. Target users for this tool are forensic specialists and security professionals.

<p align="center">
  <img src="" width="250" alt="        "/> <br/>
</p>

### autopsy(root)
- The Autopsy Forensic Browser is a graphical interface to the command line digital forensic analysis tools in The Sleuth Kit.
-  It is used by law enforcement, military, and corporate examiners to investigate what happened on a computer. You can even use it to recover photos from your camera's memory card.
- The 3 types of autopsy:
Medico-Legal Autopsy or Forensicorcoroner's autopsies.
Anatomicaloracademic autopsies.
Clinical or Pathological autopsies.

<p align="center">
  <img src="" width="250" alt="        "/> <br/>
</p>

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












