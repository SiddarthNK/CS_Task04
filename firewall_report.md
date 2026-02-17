# Firewall Configuration Report

## 📌 Overview
This report documents the configuration and testing of firewall rules on a local machine. The purpose of this task was to understand how firewalls filter network traffic and help protect systems from unauthorized access.

---

## 🎯 Objective
To configure and test basic firewall rules that allow or block specific network traffic and evaluate their effectiveness.

---

## 🛠 Tool Used
**Windows Defender Firewall with Advanced Security**

---

## ⚙️ System Details
- **Operating System:** Windows 10/11  
- **Firewall Type:** Host-based firewall  
- **Test Environment:** Local machine  

---

## 🔍 Procedure

### 1. Accessed Firewall Settings
Opened *Windows Defender Firewall with Advanced Security* to review existing inbound rules and understand the current traffic filtering configuration.

---

### 2. Listed Existing Firewall Rules
The inbound rules were examined to identify active connections and verify that the firewall was functioning properly before making changes.

---

### 3. Created a Rule to Block Port 23 (Telnet)

**Rule Configuration:**
- **Rule Type:** Inbound  
- **Protocol:** TCP  
- **Port:** 23  
- **Action:** Block the connection  
- **Profile Applied:** Domain, Private, Public  

**Purpose:**  
Port 23 is used by Telnet, an outdated protocol that transmits data without encryption. Blocking this port reduces potential security risks.

---

### 4. Tested the Firewall Rule
A connection attempt was made to port 23 using the Telnet command.

**Result:**  
The connection was unsuccessful, confirming that the firewall rule effectively blocked the traffic.

---

### 5. Removed the Test Rule
After verification, the block rule was deleted to restore the firewall to its original configuration and avoid unintended network restrictions.

---

## 📊 Observations
- The firewall successfully prevented communication through the blocked port.
- Traffic filtering occurred immediately after enabling the rule.
- No system instability was observed during testing.

---

## 🔐 How a Firewall Filters Traffic
A firewall acts as a security barrier between a trusted internal network and untrusted external sources. It monitors data packets and applies predefined rules to determine whether traffic should be allowed or denied.

### Key Functions:
- Blocks unauthorized access  
- Prevents exposure of vulnerable services  
- Controls inbound and outbound connections  
- Reduces the overall attack surface  

---

## ✅ Results
The firewall rule was successfully created, tested, and removed. The test demonstrated how blocking unused or insecure ports can enhance system security.

---

## ⚠️ Best Practices Identified
- Regularly review firewall rules.
- Block unnecessary ports and services.
- Avoid disabling the firewall.
- Monitor network activity for suspicious connections.

---

## 📷 Evidence
Screenshots of the firewall configuration, rule creation, testing, and deletion are available in the **/screenshots** directory.

---

## 🎯 Conclusion
This task provided practical experience in firewall configuration and demonstrated the importance of traffic filtering in protecting computer systems from network-based threats. Proper firewall management is a fundamental component of cybersecurity and helps maintain a secure operating environment.

---

## 🚀 Outcome
Gained hands-on knowledge of firewall rule creation, traffic blocking, and security best practices, strengthening foundational skills in system and network protection.
