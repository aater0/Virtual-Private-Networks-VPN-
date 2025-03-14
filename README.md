![VPN](https://github.com/user-attachments/assets/36f89a7f-e304-4352-94d9-a4015e60b17a)


# Virtual-Private-Networks-VPN-
This repository documents my hands-on experience with VPN setup and configuration

## Overview  
This repository documents my experience with VPNs, their functionality, and practical implementation based on the CourseCareers IT lab. It covers VPN configuration, usage, and security principles to ensure encrypted and private network communication.  

## What is a VPN?  
A **Virtual Private Network (VPN)** is a secure tunnel that encrypts internet traffic between a user’s device and a remote server. VPNs enhance security, privacy, and remote access capabilities by masking IP addresses and encrypting data transmissions.  

## Key Concepts Covered  
- **Types of VPNs** – Remote Access vs. Site-to-Site VPN
  - Remote Access VPN:
    - Used by individuals to securely connect to a private network from a remote location.
    - Common for employees working from home or traveling.
    - Example: Connecting to your company's internal network from your laptop using OpenVPN.
  - Site-to-Site VPN:
    - Connects entire networks (e.g., two office locations) instead of individual users.
    - Used by businesses to link multiple offices securely over the internet.
    - Example: A company with offices in New York and Los Angeles uses a VPN to securely share data between both locations.
- **Common VPN Protocols** – OpenVPN, IPSec, WireGuard
  - OpenVPN
    - Open-source and widely used.
    - Uses strong encryption (AES-256) and supports various authentication methods.
    - Reliable and works well even in restrictive networks.
  - IPSec (Internet Protocol Security)
    - Often used in corporate or government networks.
    - Works at the network layer to encrypt data between two endpoints.
    - Commonly paired with L2TP (Layer 2 Tunneling Protocol) for added security.
  - WireGuard
    - Newer and faster than OpenVPN and IPSec.
    - Uses modern cryptography and has a simpler codebase, reducing security vulnerabilities.
    - Becoming popular for personal and corporate use due to its speed and security. 
- **Encryption & Authentication** – Ensuring secure communication  
- **VPN Use Cases** – Privacy protection, secure remote access, bypassing geo-restrictions  

## Lab Observations  

### 1. Setting Up the Environment  
- Created a virtual machine on **Microsoft Azure** to simulate a remote device.

![Virtual Machine](https://github.com/user-attachments/assets/2a73bbb2-6221-49bc-811c-8470fe5e010b)
 
- Installed and configured **Proton VPN** to establish a secure connection on the Virtual Machine.

![Proton VPN](https://github.com/user-attachments/assets/1cba33f1-9563-423f-bc26-dede7ec2f7c3)

- I used https://whatismyipaddress.com/ to see what my IP address was for my virtual machine.

![Whats My IP address](https://github.com/user-attachments/assets/ff4e37ac-7090-4686-b867-394e0ecffae7)


### 2. Connecting to a VPN  
- Used Proton VPN to connect to different server locations.  
- Observed how my public IP address changed after connecting.  
- Noted differences in connection speed with and without the VPN.

![VPN connection](https://github.com/user-attachments/assets/c3f2962a-31f9-4c30-bf7d-bb92f59bf26c)


### 3. Security and Privacy Features  
- Tested encryption by monitoring traffic before and after using the VPN.  
- Observed how a VPN protects data on public Wi-Fi.  
- Noted the impact of VPN servers located in different countries.  

### 4. Real-World Applications  
- VPNs provide secure access to private networks (e.g., work or school).  
- Used to bypass geo-restricted content and censorship.  
- Essential for protecting sensitive data from hackers.  

## Key Takeaways  
✔ **VPNs enhance privacy by hiding IP addresses.**  
✔ **They encrypt data, making it harder for attackers to intercept information.**   
✔ **VPNs are useful for both personal security and corporate network access.**  
✔ **Secure Remote Access**  - Enables safe connections to private networks
✔ **Bypass Geo-Restrictions**  - Access region-locked content securely
  
