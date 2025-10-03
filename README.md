# CyberIntern-Task8

#  Task 8 - VPN Setup and Privacy 

##  Objective
The objective of this task is to gain **hands-on experience with Virtual Private Networks (VPNs)**, understand how they work, and evaluate their effectiveness in securing communication and protecting privacy.

---

##  Tools & Resources Used
- **VPN Provider:** ProtonVPN  
- **Operating System:** [Windows 11]
- **Verification Website:** (https://whatismyipaddress.com)  
- **Network Tools Used:** Command Prompt / Terminal (for `ping`, `tracert`)  

---

##  Step-by-Step Procedure

### 1️ Account Creation
- Registered for a free ProtonVPN/Windscribe account.  
- Verified email and activated free subscription.

### 2️ Installation
- Downloaded and installed the VPN client for my OS.  
- Logged in using registered credentials.  

   <img width="1608" height="919" alt="Screenshot 2025-10-03 161548" src="https://github.com/user-attachments/assets/344b1e86-7812-4f48-9aae-782d759e04f3" />
   <img width="1920" height="1080" alt="Screenshot (25)" src="https://github.com/user-attachments/assets/e0adf086-783d-4ca3-8127-e7b34728160d" />


### 3️ Connecting to VPN
- Opened the VPN client.  
- Selected a **server location** closest to me for better speed. proton vpn connected to norway server.
- Successfully connected to the server.  

   <img width="1920" height="1080" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/73d6cda0-83eb-4267-ba2a-647263e9f585" />
 

### 4️ Verifying VPN Connection
- Checked my public IP **before connecting to VPN**.  
- Connected VPN and checked my IP again .  
- Confirmed that the IP address changed successfully.  

   📷 *Before VPN (Real IP)*
  <img width="1918" height="967" alt="Screenshot 2025-10-03 161726" src="https://github.com/user-attachments/assets/6fed2840-0e40-44ba-a13a-761ef2628bbd" />

   📷 *After VPN (VPN IP)*
  <img width="1917" height="978" alt="Screenshot 2025-10-03 162344" src="https://github.com/user-attachments/assets/189ad42b-3d0b-4b54-ae5d-1d8b1040bad6" />


### 5️ Testing Encrypted Traffic
- Accessed websites like Google, YouTube, and BBC.  
- Traffic successfully tunneled through VPN.  
- Confirmed no DNS leaks using **dnsleaktest.com**.  

   📷 *Screenshot of DNS Leak Test Result*
  <img width="1919" height="812" alt="Screenshot 2025-10-03 163120" src="https://github.com/user-attachments/assets/74566a59-40a7-41a2-af1b-57253c1cfa7e" />


### 6️ Disconnecting VPN & Comparison
- Disconnected VPN and rechecked IP.  
- Compared browsing speed with and without VPN.  
- Observed a slight **speed reduction (~15-20%)** due to encryption overhead.  

---

##  Research & Concepts

###  What is a VPN?
A **Virtual Private Network (VPN)** creates a secure tunnel between a device and the internet. It hides the real IP address and encrypts all traffic.

###  How Does a VPN Protect Privacy?
- Encrypts data (AES-256, ChaCha20)  
- Hides user’s real IP address  
- Prevents ISP, government, and hackers from monitoring browsing activity  

###  VPN vs Proxy
| Feature | VPN | Proxy |
|---------|-----|-------|
| Encryption |  Yes |  No |
| System-wide protection |  Yes |  No (browser/app specific) |
| Speed | Moderate | Faster but less secure |
| Anonymity | High | Low |

###  VPN Protocols
- **OpenVPN** – Secure and widely adopted  
- **WireGuard** – Lightweight, faster performance  
- **IKEv2/IPSec** – Good for mobile stability  
- **L2TP/IPSec** – Older, less efficient  

---

##  Benefits of VPN
- Hides browsing activity from ISP & trackers  
- Secures communication over public Wi-Fi  
- Protects against Man-in-the-Middle attacks  
- Bypasses geo-restrictions (Netflix, YouTube, etc.)  
- Provides an additional layer of **cyber hygiene**  

##  Limitations of VPN
- Cannot ensure **100% anonymity**  
- Free VPNs may log user data  
- Slows down connection speed due to encryption  
- Some websites block known VPN IPs  
- Reliance on VPN provider’s trustworthiness  

---

