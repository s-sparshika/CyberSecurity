<p align="center">
  <img src="https://www.cisco.com/c/en/us/products/wireless/what-is-wifi/jcr:content/Grid/category_atl_d6eb/layout-category-atl/anchor_info_8bec.img.png/1638359791836.png"/> <br/>
</p>
          
# The basic working of Wi-Fi and its types with various types of attacks on it.

## What is Wi-Fi?
Wi-Fi is a wireless networking technology that allows devices such as computers (laptops and desktops), mobile devices (smart phones and wearables), and other equipment (printers and video cameras) to interface with the Internet. 
It allows these devices--and many more--to exchange information with one another, creating a network. Internet connectivity occurs through a wireless router. When you access Wi-Fi, you are connecting to a wireless router that allows your Wi-Fi-compatible devices to interface with the Internet.

## How does Wi-Fi work?
On the technical side, the IEEE 802.11 standard defines the protocols that enable communications with current Wi-Fi-enabled wireless devices, including wireless routers and wireless access points. Wireless access points support different IEEE standards.
Each standard is an amendment that was ratified over time. The standards operate on varying frequencies, deliver different bandwidth, and support different numbers of channels.

## Types of Wi-Fi
1. Personal WiFi
2. Enterprise Wi-Fi

## 1.Personal Wi-Fi
   - Appropriate for most home networks. 
   - When a password is set on a wireless router or an access point, it must be entered by users when connecting to the Wi-Fi network.
   - The wireless access can not be individually or centrally managed. One password applies to all users, and it should be manually changed on all the wireless clients once it’s manually modified on the original wireless router.
   - The password is stored on the wireless clients i.e anyone on the computer can connect to the network and also see the password.
 ## 2.Enterprise Wi-Fi
   - Provides security needed for wireless networks in business environments. 
   - It is more complicated to set up, and offers individualized and centralized control over access to Wi-Fi network. When users try to connect to the network, they need to present their login credentials.
   - This mode supports 802.1x RADIUS authentication and is appropriate in cases where a RADIUS server is deployed. 
   - WPA-Enterprise should only be used when a RADIUS server is connected for client authentication.

## Various types of attack on Wi-Fi

## setting up wifi and configuring it to monitor mode 

![image](https://user-images.githubusercontent.com/68326118/230085018-846fedf7-5883-4968-bb88-e99a0a89f4ed.png)

## Perform Wi-Fi fingerprinting using Wigile, Inssider, and Kismet.

#### Kismet, inSSIDer, and WiGLE are three different tools that are used for wireless network analysis and monitoring. Here is a brief overview of each tool:
1. Kismet:
Kismet is an open-source wireless network detector, sniffer, and intrusion detection system. It is designed to work with any 802.11 wireless network and can be used for packet sniffing, network traffic analysis, and wireless network monitoring. Kismet is available for Linux, Windows, and macOS and supports a variety of wireless network cards.

2. inSSIDer:
inSSIDer is a wireless network scanner that can be used to analyze and troubleshoot Wi-Fi networks. It provides information about wireless networks including signal strength, channel, encryption, and other network parameters. inSSIDer is available for Windows and macOS and can be used with any Wi-Fi network adapter.

3. WiGLE:
WiGLE is a website and a mobile app that allows users to search for and map wireless networks. It collects data from wireless networks and provides information about the location, SSID, and signal strength of nearby Wi-Fi networks. Users can also use WiGLE to upload their own wireless network data and contribute to the database. WiGLE is available for both Android and iOS devices.
In summary, Kismet is more of an intrusion detection system that focuses on monitoring wireless networks for potential security breaches, while inSSIDer and WiGLE are tools for analyzing and troubleshooting Wi-Fi networks.

### Kismet 

`sudo kismet -c wlan0`
 
####  Its a linux tool. A wireless network and device detector, sniffer, wardriving tool, reconnaissance tool and WIDS (wireless intrusion detection) framework. Displays all the information such as bssid,ssid,devices per channel, etc of all the devices in that range. 
  
### ssid image of our personal hotspots 
![image](https://user-images.githubusercontent.com/68326118/230277751-378aead2-7b6d-4265-8827-225fb5148c0e.png)

### bssid of all the devices in the range
![image](https://user-images.githubusercontent.com/68326118/230278154-626833a7-3e83-45bf-978f-d6f69880eb16.png)

### Devices per channel
![image](https://user-images.githubusercontent.com/68326118/230282537-3daebb9e-a7f1-49f1-a6ad-0f4d3369b77b.png)

### Wigle 
- Here we downloanded an application from the playstore and we can see the information and also the geographical location of a particular ip address.

![WhatsApp Image 2023-04-06 at 11 03 15 (1)](https://user-images.githubusercontent.com/68326118/230281125-e5f0daa6-adfb-4bbf-83fd-933939593905.jpeg)

- Location of a particular ip address

![WhatsApp Image 2023-04-06 at 11 03 15](https://user-images.githubusercontent.com/68326118/230281089-b5314c23-91c6-43d5-b1dc-28876fca6ae4.jpeg)

### inssider
![WhatsApp Image 2023-04-06 at 11 02 11](https://user-images.githubusercontent.com/68326118/230281222-70d53cee-88c9-4ad5-a157-0133da147a44.jpeg)


###

![image](https://user-images.githubusercontent.com/68326118/230288530-283984ae-ecfa-4505-aa33-20cd4b29d1b6.png)

![image](https://user-images.githubusercontent.com/68326118/230288179-632e0714-1066-4c56-b52e-ff09a387e1d4.png)

![image](https://user-images.githubusercontent.com/68326118/230288706-550ab92e-af93-47a7-b253-d0a04add8422.png)

The created access point

![image](https://user-images.githubusercontent.com/68326118/230289028-56a1687a-33c6-4ae5-a07b-12a90415f66a.png)



### After capturing the required filesfortesting, usedictionarygeneration and password cracking tools to crack the Wi-Fi password. 
a.You mustuse an existing word file to crack the password.
b.Also you have to create your dictionaryfilefor cracking the passwords.
c.Keep 3 different types of passwordsforyour Wi-Fi to test it. 
Simple, medium,and complex passwords can be used for testing. Simple can be a dictionary word, medium can be of dictionaryword with some numbers, and complex can be generated from any password generatoronline. 

![image](https://user-images.githubusercontent.com/68326118/230714611-9913f2c1-dbaf-43dc-8315-0d44a8e025d9.png)

![image](https://user-images.githubusercontent.com/68326118/230719251-dccc8f8f-33a8-4a49-897b-fef9ff3bf72e.png)

![image](https://user-images.githubusercontent.com/68326118/230719444-a9869e42-e9bd-41d5-8a7c-d3d9eedc9f2f.png)

![image](https://user-images.githubusercontent.com/68326118/230720754-a0153f7c-f81f-40fa-9f54-f737ce53058e.png)
