# Enhance Security

## Firewall

### Rules
###### Exist to control the flow of data.
```
ALLOW TCP from ANY to 203.0.113.5 PORT 80
```
### Access Control List (ACL)
###### Is a fundamental feature of firewall technology. 
###### ACLs can be used to allow or deny: IPs, Protocols, Ports, Time of Day.
### Ports
###### Like a virtual dock used by a running program to service outside users.
### Protocol
###### Set series of steps or ways of doing things.
### Screened Subnet
###### Specific network segment situated between an organization and internal network.

## Intrusion Detection System (IDS) / Intrusion Prevention System (IPS)
### Signatures
###### Such as hashes of specific chunks of a file.

## Web Filtering
###### A mechanism that controls access to websites.
### Agent-Based Web Filtering
###### Software on the users device to filter.
### Centralized Proxy
###### Server based method of web filtering.
### URL Scanning
###### A process that involves examining and categorizing web addresses to see potentially harmful websites.
### Content Categorization
###### Instead of straight up blocking, examines content within the site.
### Block Rules
###### Black lists. Predifined rules.

## OS Security
### Group Policy
###### Framework for admins to make rules for the OS
### SELinux
###### Policies and Sandboxing for linux applications to run in.
### Protocol Selection
###### Choosing a standard to communicate of send data over.
### Port Selection
###### Choosing specific entry and exit points
### Table 18-2
```
PORT     PROTOCOL
23       TELNET
25       SMTP
49       TACACS
80       HTTP
88       KERBEROS
110      POP3
123      NTP
139      NETBIOS
143      IMAP2
161      SNMP
389      LDAP
443      HTTPS
465      SMTPS
636      LDAPS
990      FTP/S
993      IMAP/S
995      POP3/S
1433     MS SQL
1812     RADIUS
3389     RDP
5060     SIP
```
### Transport Method Selection
###### Pertains to how data packets are sent across a network.

## DNS Filtering
###### Blocking access to particular domain resolutions

## Email Security
###### Secure access and content of an email account/service
### Domain-Based Message Authentication Reporting and Conformance (DMARC)
###### CRITCAL in combatting email-based attacks
### DomainKeys Identified Mail (DKIM)
###### Tries to verify the authenticity by allowing sender to sign parts of the email digitally.
### Sender Policy Framework (SPF)
###### User can verify email was sent from a server authorized by domain owner.
### Email Gateways
###### Special email servers between you and internet.

## File Integrity Monitoring
###### Security process that involves checking files for changes

## DLP
###### An end-to-end goal to make sure users do not send sensitive data.

## Network Access Control (NAC)
###### A method for enforcing policy-driven security solutions at the network entry level.

## Endpoint Detection and Response (EDR) / Extended Detection and Response (XDR)
### (EDR)
###### Solutions are inward. Analyze files, processes, and file changes.
### (XDR)
###### Holistic view, correlating data across various methods. Email, Cloud, Network, Traffic.

## Use Behavior Analytics (UBA)
###### Machine Learning Algorithms to track, collect, and assess behavior of a specific user.

