![CompTIA Security+ Badge](https://images.credly.com/size/340x340/images/80d8a06a-c384-42bf-ad36-db81bce5adce/blob)

# <div style="text-align: center;">CompTIA Security+ (SY0-701) Notes</div>

My study notes and key concepts for Security+

## Domain 1.0 - General Security Concepts (12%)

### 1.1 Compare and contrast various types of security controls

**Control Categories**
- **Technical** - Firewalls, encryption, antivirus
- **Managerial** - Policies, procedures, risk assessments
- **Operational** - Training, physical security, backups
- **Physical** - Fences, locks, cameras, guards

**Control Types**
- **Preventive** - Stop incidents before they happen
- **Detective** - Identify incidents
- **Corrective** - Fix issues after they occur
- **Deterrent** - Discourage potential attackers
- **Compensating** - Alternative controls when primary ones aren't feasible

### 1.2 Summarize fundamental security concepts

**CIA Triad**
- **Confidentiality** - Encryption, access controls
- **Integrity** - Hashing, digital signatures
- **Availability** - Redundancy, backups

**Non-repudiation**
- Digital signatures, audit logs

**Zero Trust**
- Never trust, always verify

**Defense in Depth**
- Multiple layers of security controls

## Domain 2.0 - Threats, Attacks, and Vulnerabilities (22%)

### 2.1 Given a scenario, analyze indicators of malicious activity

**Common Attack Indicators**
- Unusual network traffic
- High CPU/memory usage
- Unauthorized accounts or proceses
- Modified files or logs
- Phishing emails, suspicious attachments

**Malware Types**
- **Virus** - Attaches to legitimate files
- **Worm** - Self-replicatinig
- **Trojan** - Disguised as a legitimate software
- **Ransomware** - Encrypts files for ransom
- **Spyware** - Steals information
- **Rootkit** - Hides presence
- **Keylogger** - Records keystrokes

### 2.2 Compare and contrast different types of attacks

**Social Engineering Attacks**
- Phishing, spear phishing, whaling, vishing, smishing
- Pretexting, tailgating, piggybacking, baiting

**Network Attacks**
- Main-in-the-Middle (MITM)
- Denial of Service (DoS/DDoS)
- Evil twin / Rogue AP
- ARP poisoning

**Password Attacks**
- Brute force, dictionary, rainbow table
- Credential stuffing

### 2.3 Given a scenario, summarize security concerns associated with vulnerable systems

**Vulnerable Systems**
- Unpatched systems
- Legacy systems
- Weak configurations
- Default credentials
- Open ports / services

**Zero-Day Vulnerabilities**
- Exploits unknown to vendors

### 2.4 Given a scenario, analyze indicators associated with application attacks

**Web Application Attacks**
- SQL injection
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- Directory traversal

**API Attacks**
- Insecure direct object references
- Broken authentication

## Domain 3.0 - Security Architecture (18%)

### 3.1 Given a scenario, apply security principles to network architecture

**Network Segmentation**
- VLANs
- DMZ (Demilitarized Zone)
- Microsegmentation
- Zero Trust architecture

**Network Security Devices**
- **Firewalls**
  - **Stateful** — Tracks the state of active connections and makes decisions based on context
  - **Stateless** — Inspects each packet individually without tracking connection state (faster but less secure)
  - **NGFW (Next-Generation Firewall)** — Combines traditional firewall with advanced features like application awareness, intrusion prevention, and deep packet inspection
- Introsion Detection/Prevention Systems (IDS/IPS)
- Web Application Firewalls (WAF)
- Load balancers with security features

### 3.2 Given a scenario, implement secure network designs

**Secure Design Principles**
- Defense in Depth
- Least Privilege
- Secure by Default
- Fail security

**Cloud Security**
- Shared responsibility model
- CASB (Cloud Access Security Broker)
- Cloud security posture management

### 3.3 Given a scenario, implement secure application designs

**Secure Development Practices**
- Input validation
- Secure coding
- Code signing
- Sandboxing

 **Application Security**
 - Web Application Firewalls
 - API gateways
 - Secure authentication methods

### 3.4 Given a scenario, implement secure cloud technologies

**Cloud Deployment Models**
- Public
- Private
- Hybrid
- Community

**Cloud Service Models**
- **IaaS** - Infrastructure as a Service
- **PaaS** - Platform as a Service
- **SaaS** - Software as a Service

**Cloud Security Controls**
- Encryption
- Identity and Access Management (IAM)
- Loggin and monitoring

## Domain 4.0 - Security Operations (28%)

### 4.1 Given a scenario, perform vulnerability management activities

**Vulnerability Managment**
- Scanning (authenticated vs non-authenticated)
- Vulnerability assessment
- Remediation
- Patch management
- Compensating controls

**Common Tools**
- Vulnerability scanners
- SIEM
- SOAR

### 4.2 Given a scenario, assess vulnerabilities

**Common Vulnerabilities**
- Misconfigurations
- Unpatched systems
- Weak passwords
- Default credentials
- Open ports/services

### 4.3 Given a scenario, use security information and event management (SIEM)
**SIEM Capabilities**
- Log aggregation
- Correlation
- Alerting
- Dashboards
- Forensics

### 4.4 Explain the importance of incident response

**Incident Response Process**
- Preparation
- Identification
- Containment
- Eradication
- Recovery
- Lessons learned

### 4.5 Given a scenario, apply incident response procedures

**Incident Response Teams**
- CSIRT (Computer Securit5y Incident Response Team)
- Roles and responsibilities

**Evidence Handling**
- Chain of Custody
- Forensic best practices

### 4.6 Explain the importance of digital forensics

**Forensic Concepts**

- **Order of Volatility (Memory)** The order in which you should collect evidence during a forensic investigation (most volatile first):
1. **CPU Registers and Cache** — Fastest and most volatile data
2. **Routing Tables** — Network routing information
3. **RAM (Random Access Memory)** — Running processes and data in memory
4. **Swap / Page File** — Data swapped to disk when RAM is full
5. **Hard Drive / SSD** — Persistent storage (least volatile)
6. **Removable Media** — USB drives, external storage
7. **Logs and Backups** — Archived data
> **Tip**: Always collect from most volatile to least volatile to avoid losing evidence.
- Data acquisition
- Hashing for integrity
- Legal considerations

## Domain 5.0 - Security Program Management and Oversight (18%)

### 5.1 Summarize effective security governance concepts

**Governance**
- Policies, standards, procedures, guidelines
- Compliance and regulatory requirements
- Risk management
- Security awareness training

### 5.2 Explain the importance of security awareness and training

**Security Awareness**
- Phishing simulations
- Social engineering awareness
- Password hygiene

**Training Topics**
- Acceptable Use Policy (AUP)
- Incident reporting
- Physical security
- Mobile device security

### 5.3 Explain the importance of governance, risk, and compliance concepts

**Governance, Risk, and Compliance (GRC)**
- Risk assessment and management
- Compliance frameworks
- Third-party risk management
- Vendor due diligence

### 5.4 Explain the importance of data privacy and data protection

**Data Privacy**
- GDPR, CCPA, HIPPA
- Data classification
- Data retention and disposal
- Privacy impact assessments

### 5.5 Given a scenario, perform data loss prevention activities

**Data Loss Prevention (DLP)**
- Monitoring and blocking sensitive data
- Endpoint DLP
- Network DLP
- Email DLP


## Website
[View website](https://frankwjohns13.github.io/)
