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
- 

<p align="center">
  <img src="" width="250" alt="        "/> <br/>
</p>

## PDF Forensics Tools

<p align="center">
  <img src="" width="250" alt="        "/> <br/>
</p>

### pdfid

<p align="center">
  <img src="" width="250" alt="        "/> <br/>
</p>

### pdf-parser

<p align="center">
  <img src="" width="250" alt="        "/> <br/>
</p>

## Sleuth Kit Suite

<p align="center">
  <img src="" width="250" alt="        "/> <br/>
</p>

### autopsy(root)

<p align="center">
  <img src="" width="250" alt="        "/> <br/>
</p>

### hfind

<p align="center">
  <img src="" width="250" alt="        "/> <br/>
</p>

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












