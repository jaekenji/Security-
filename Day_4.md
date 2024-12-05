## Day 4
### Protecting Data
#### 1. Data Types
- Regulated - subject to law
- Trade Secret - confidential
- Intellectual Property - works corrected by legal rights
- Legal Information - Data directly related to legal processes
- Financial Information
- Human and Non-Human-Readable Data - Understood/Computer Readable

#### 2. Data Classifications
- Confidential or Proprietary - Could cause grave damage
- Sensitive - Do some damage
- Public - Openly available information
- Restricted - Requires highest level of security
- Private - Could cause severe damage
- Critical - Essential to continue function of company

#### 3. General Data Considerations
- Data States - Rest, Transit, In Use
- Data Sovereingty - Legal or regulatory requirements
- Geolocation - Indentifying real-world geographic locations

#### 4. Methods to Secure Data
- Geographic Locations - Limit access to data based on a user's location
- Encryption - Transforming to a no readble form
- Hashing - Verify integrity
- Masking - Replacing specific data with fake (similar) data (EDIPI/SSN)
- Tokenization - (XXXX-XXXX-XXXX-2055)
- Obfuscation - Make not readable, or harder to understand (Steganography)
- Segmentation - Dividing data across a network (Differnet Servers/VLANS)
- Permission restrictions
-----
### Resilience and Recovery in Security Architecture
#### 1. High Availability
- Redundant Hardware - Uses hardware components (Severs/Switches/Routers)
- Automated Backups - Scheduled backups
- Failover Mechanisms - If a network fails, switch to a different one

#### 2. Site Considerations
- Hot Site - A near duplicate a company can switch to
- Warm Site - Has computers, phones, and servers, but may need configurations
- Cold Site - Tables, Chairs, Bathrooms, and MAYBE som tech, needs much configuration
- Geographically Distant Site - A data center at least 50 miles away

#### 3. Platform Diversity
- Platform Diversity - Implement different hardware or software platforms

#### 4. Multi-Cloud Systems
- Multi-Cloud System - Involve multiple cloud services

#### 5. Continuity of Operations
- Continuity of Operations Planning (COOP) - Federal initiative to see how operations will continue under a range of circumstances

#### 6. Capacity Planning
- Technology Evaluating computational power
- Infrastructure - Resources that support the technology

#### 7. Testing
- Testing - critical in evaluating an organizations resiliance and recovery strategies
  - Recovery Time Objectives (RTO)
  - Recovery Point Objectives (RPO)
- Tabletop Exercise - Validate an orginizations inident repsonse plan (IRP)
- Failover Testing - Switching operational functions from primary to secondary
   - Timing
   - Notification
   - Who performs the test
   - ACTIVE
   - PASSIVE
- Simulations Internal event that provides a structured exercise to practice (SIRS)
- Parallel Processing 

#### 8. Backups
- Onsite
- Offsite
- Frequency
- Encryption Algorithm
- Snapshot
- Recovery
- Replication
- Journaling
- Full
- Incremental
- Differential
- Mirror
- Continuous Data Protection (CDP)
- Cloud
- Virtual
- Bare-Metal backup

#### 9. Power
- Power management - Effective use of electricity
- Uninterruptible Power Supply (UPS)
