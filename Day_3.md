## Day 3

### Malicious Activity

#### 1. Malware Attacks
- Ransomware - Encrypts files and hosts them hostage
- Trojan - Disguised as something
- Worm - Self replicating
- Spyware - Monitor a system
- Bloatware - Take up system resources
- Virus - Plain code
- Keylogger - Spyware
- Logic Bomb - Event or Time bomb
- Rootkit - Malware infecting BIOS

#### 2. Physical Attacks
- Brute-Force attacks - Try until it works
- RFID Cloning
- Environmental

#### 3. Network Attacks
- DDoS - DoS distrubuted amongst many different deniers
- DNS Attacks - Redirect users to different sites
- Wireless Attacks - Deauth, Packet sniffing, Rogue access points
  - Evil Twin - Replicate legitimate network
  - Spoofing - Impersonate another device
  - Encryption - cracking, if theres a weak wifi security, or password is obtained
  - On-path - MitM
  - WiFi Jamming
- Credential replay - replay traffic to capture creds
- Malicious Code
  
#### 4. Application Attacks
- Injection
- Buffer Overflow
- Replay
- Priv Esc
- Forgery - Perform actions a user did not intend to
- Directory Traversal

#### 5. Cryptographic Attacks
- Degrade
- Deny
- Destroy
- Collision

#### 6. Password Attacks
- Password Spraying
- Brute-Force

#### 7. Indicators
- Account Lockout
- Concurrent session usage
- Blocked Content
- Impossible Travel
- Resource Inaccessability
- Out-of-cycle Logging
- Published Indicators
- Missing Logs

-----

### Mitigation Techniques

#### 1. Segmentaion 
- Dividing a network into subnetworks

#### 2. Access Control
- ACLs - List of acceptable or deniable actions
- Permissions
- Windows/Linux permisions


#### 3. Application Allow List
- Approved Applications
- Allow List
- Deploy central managing system
- Respong to an Incident
- Access user impact

#### 4. Isolation
- Form of forensic analysis

#### 5. Patching
- Stay up-to-date

#### 6. Encryption
- Keep information protected

#### 7. Monitoring
- Stay watching just in case something happens

#### 8. Least Privilege
- Don't give more privilege than you need

#### 9. Configuration Enforcement
- Standardization, such as, strong passwords

#### 10. Decommissioning
- If it isn't needed, don't use it. Could be a source of vulnerability

#### 11. Hardening Techniques
- Get tools, get rid of functions, restrict access, set configurations
- Encryption
- Installation of protection
- Host-Based Firewall
- HIPS Host-Bassed Prevention System
- Disbale unecesassary services/ports
- Default password changes
- Remove software

-----

### Security Implications

#### Architecture and infrastructure concepts
> Cloud computing is a way of offering on-demand services

![image](https://github.com/user-attachments/assets/74d9ff95-f1bf-4b86-9ca7-2c63d1c9f374)

##### Infrastructure as a Service
> VMs, storage, networking

##### Platform as a Service
> Provide a platform that users can dev, run, and manage

##### Software as a Service
> Provides basically everything except storage and applications

##### Everything as a Service
> Everything is provided

#### 2. Considerations
nothing lol

-----

### Applying Security Principles

#### 1. Infrastructure Considerations
- Device Placement
- Security Zones - under specific policies or controls
- Attack Surface - all services that are exposed to the internet (disable unecesassary services)
- Connectivity - self explantory
##### Failure Modes
- fail-open - if a part fails, the rest works
- fail-closed - if a part fails, the rest shuts down

</br>

- Device Attribute - how it works in an environment
> Active v Passive
  - Active one device performs work while others stand by
  - Passive only active when active goes offline
> Inline v Tap
  - Inline is a device directly in the network
  - Tap is hearing it and responding maybe later
- Network Appliances
  - Jump server
  - Proxy server
  - IPS/IDS
  - Load balancer
  - Sensor
- Port security
- Firewall types

#### 2. Secure Communitcations
- VPNs
- Remote Access
- Tunneling
