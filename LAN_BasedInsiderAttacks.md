# ETTERCAP
<p align="center">
          <img src="https://www.kali.org/tools/ettercap/images/ettercap-logo.svg"/> <br/>
</p>

### Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis. Data injection in an established connection and filtering (substitute or drop a packet) on the fly is also possible, keeping the connection synchronized. Many sniffing modes are implemented, for a powerful and complete sniffing suite. It is possible to sniff in four modes: IP Based, MAC Based, ARP Based (full-duplex) and PublicARP Based (half-duplex). Ettercap also has the ability to detect a switched LAN, and to use OS fingerprints (active or passive) to find the geometry of the LAN. This package contains the Common support files, configuration files, plugins, and documentation. You must also install either ettercap-graphical or ettercap-text-only for the actual GUI-enabled or text-only ettercap executable, respectively.

# ARP Poisoning
### ARP Poisoning (also known as ARP Spoofing) is a type of cyber attack carried out over a Local Area Network (LAN) that involves sending malicious ARP packets to a default gateway on a LAN in order to change the pairings in its IP to MAC address table. ARP Protocol translates IP addresses into MAC addresses. 


# Performing Password stealing (over plaintext) using ARP Cache Poisoning attacks
- We first scan for host ip address

![image](https://user-images.githubusercontent.com/68326118/227765272-f8acc10e-79b6-4241-acbd-a3d987a29a71.png)

- We get the list of scanned Host list in the Ettercap as shown in the image , here we can find our host ip address

![image](https://user-images.githubusercontent.com/68326118/227765369-be70a619-bd97-405a-a8d9-cd2f594ef4d2.png)

- Then we select our host ip and add it to the target. And choose ARP poisoning from MITM

![image](https://user-images.githubusercontent.com/68326118/227765465-eb9d0e97-a971-4239-aafe-a386a2ae836e.png)

- Now open a web page in the victims machine. And enter the login credentials.

![image](https://user-images.githubusercontent.com/68326118/227765555-53060835-0f2c-4dd8-832a-6a7f1da68ee5.png)

- Now when the victim enters the login credentials we can see the USER & PASS in the attackers window.

![image](https://user-images.githubusercontent.com/68326118/227765661-43c8ec4e-f382-4f99-8273-5a053be49864.png)

# Perform Denial of Service (DoS) attacks using ARP Cache Poisoning attacks 

### DOS ATTACK:
- In computing, a denial-of-service attack is a cyber-attack in which the perpetrator seeks to make a machine or network resource unavailable to its intended users by temporarily or indefinitely disrupting services of a host connected to a network.
### What cause DoS attacks?
- A distributed denial-of-service (DDoS) attack occurs when multiple systems flood the bandwidth or resources of a targeted system, usually one or more web servers. A DDoS attack uses more than one unique IP address or machines, often from thousands of hosts infected with malware.

### The following steps are to be followed to perform this attack
1. Open ettercap , scan hosts and add the victim's IP address to the target.
2. Start ARP Poisoning and select DOS attack plugin and enter victim's IP address and fake host IP address
3. To check the website is accessable or not we will open any site in the victim's machine.
4. Then we can see that the page does'nt respond .
( the page appears like tihs)
![image](https://user-images.githubusercontent.com/68326118/227771153-2b1c763b-fb6e-463d-a6e7-ea3f947546fd.png)

#  Perform DNS Spoofing attack using ARP Cache Poisoning attacks 

- To peform this task first we need to make ec_uid and ec_guid values as zero and give some domain name and assign the attackers IP address.

![image](https://user-images.githubusercontent.com/68326118/227768095-16ce5d30-d4d8-42fc-a58e-01e464aa4a53.png)

![image](https://user-images.githubusercontent.com/68326118/227767987-e11b0d5b-f7db-4aa4-9880-4478eb4f5843.png)

![image](https://user-images.githubusercontent.com/68326118/227768060-efe57151-bf1e-4b9c-a06c-c5cc0578e629.png)

- After doing this we start apache2 and open the ettercap and scan for the hosts and add the attackers host to the target. And choose ARP Spoofing and choose DNS spoofing pulgin
- Then when we open snapchat.com in the attackers web , then we can see the spoofed web page.

`snapchat.com` spoofing

![image](https://user-images.githubusercontent.com/68326118/227766876-3e0a3252-2be0-4a24-897d-6d7221a833a1.png)

`DNS Spoofed page`

![image](https://user-images.githubusercontent.com/68326118/227767905-73f6ada5-ba86-40d9-9a61-a9f4ec16ff71.png)

#  Invoke ‘sslstrip tool’ for stealing passwordsfrom any machine that is connected toa LAN by stripping the HTTPSconnection. 

 - Open ettercap tool , scan the host 
 - select the vicitms ip and add to target 1 
 - Start MITM Attacks of ARP Poisoning 
 - And select the SSLStrip plugin 
### Here we can see the above output 
 
![image](https://user-images.githubusercontent.com/68326118/227952722-2608aaac-f09f-428e-bafc-312c185c2427.png)

- We can check the ssl striping on the victim's machine 

![image](https://user-images.githubusercontent.com/68326118/227953206-e0ff1f37-edc3-4133-85a8-87b71294d157.png)

# arp_cop and scan_poisoner plugins to learn about the detection of ARP attacks
### arp_cop: It reports suspicious ARP activity by passively monitoring ARP requests and replies. It can report ARP posioning attempts, or simple IP-conflicts or IP-changes. We follow following steps to perform the attack
- Open ettercap and select arp_cop plugin.
- Open ettercap in another machine and scan the hosts.
- Add the first machine's IP address as Target.

![image](https://user-images.githubusercontent.com/68326118/228004106-ac3f82de-af6f-4dc2-8667-dc6995d64b32.png)

- Start the ARP poisoning in second machine.
- We can see in first machine's window that it reports the ARP activity.

![image](https://user-images.githubusercontent.com/68326118/228004219-3596fcc9-60ff-4ae8-b779-bbf527e378ef.png)

# SCAN Poisoner
### scan_poisoner scans if someone is poisoning between the user machine and the hosts in the scanned list. It checks whether if two hosts in the list have same MAC address.
- Open ettercap and select the scan_poisoner plugin.
- Open ettercap in another machine and scan the hosts.
- Add the first machine's IP address as Target.
- Start the ARP Poisoning.
- We can see that one host is replying to other in the lists of hosts that captured by scan_poisoner.


- if there is no host poisoning other host the output will be like below

![image](https://user-images.githubusercontent.com/68326118/228006787-18b8b82c-f1b5-4bdd-a3ab-edb92dfe90e3.png)

- if there is host poisoning other host the output will be like below 
- 
![image](https://user-images.githubusercontent.com/68326118/228007089-6a2ad6b4-0021-4c28-80ff-0e88a57d0d49.png)
