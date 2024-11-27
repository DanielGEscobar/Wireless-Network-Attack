# Wireless-Network-Attack

## Objective
This project focuses on simulating common wireless network attacks and implementing defensive strategies. The goal is to understand the vulnerabilities in Wi-Fi networks and explore countermeasures. The project highlights ethical hacking techniques for educational purposes only.


### Skills Learned

-Wireless network protocols (WPA2/WPA3)
-Packet analysis and interception
-Ethical hacking principles and legal considerations
-Network monitoring and defense strategies
-Incident response planning

### Tools Used

-Kali Linux: Primary OS for penetration testing
-Aircrack-ng: Suite for wireless network security testing
-Wireshark: Network protocol analyzer
-Hashcat: Password recovery tool
-Router or Wi-Fi Adapter: To set up a test network

- 

## Steps
Steps in the Project

1. Environment Setup
Install Kali Linux on a virtual machine or dedicated system.
Ensure a wireless network adapter that supports monitor mode is connected.
Set up a secure lab environment using a router with WPA2 encryption.

2. Passive Reconnaissance
Use Airodump-ng to monitor wireless traffic and capture the handshake between devices.
Identify SSID, BSSID, and client devices connected to the network.

3. Deauthentication Attack
Launch a deauthentication attack using Aireplay-ng to disconnect a target device.
Capture the re-authentication process to obtain the WPA2 handshake.

4. Handshake Capture and Cracking
Capture WPA2 handshake packets using Airodump-ng.
Use Aircrack-ng or Hashcat to perform a dictionary attack on the captured handshake.

5. Packet Analysis
Use Wireshark to analyze captured packets and identify sensitive data leaks or unusual traffic patterns.

6. Mitigation Techniques
Demonstrate secure configurations:
Enable WPA3 encryption (if available).
Disable WPS (Wi-Fi Protected Setup).
Implement MAC address filtering and network monitoring tools to detect intrusions.

7. Documentation and Reporting
Document each attack method, results, and the steps taken to mitigate vulnerabilities.
Create a report with recommendations for improving wireless network security.


