# Firewall Configuration Report

## Objective
The objective of this task was to configure and test firewall rules to control network traffic and improve system security.

---

## Tool Used
Windows Defender Firewall with Advanced Security

---

## Steps Performed

### 1. Reviewed Existing Firewall Rules
Accessed inbound firewall rules to understand the current security configuration.

### 2. Created a Rule to Block Telnet (Port 23)
A new inbound rule was created to block TCP traffic on port 23, which is commonly associated with the insecure Telnet protocol.

### 3. Tested the Firewall Rule
Attempted to connect to port 23 locally using Telnet.  
The connection failed, confirming that the firewall rule was functioning correctly.

### 4. Removed the Test Rule
The block rule was deleted after testing to restore the system to its original state.

---

## How Firewall Filters Traffic
A firewall monitors incoming and outgoing network packets and applies predefined rules to either allow or block traffic.

- **Allowed traffic** passes through the system.
- **Blocked traffic** is prevented from reaching the device.

This helps protect the system from unauthorized access and network-based attacks.

---

## Outcome
This task provided practical experience in configuring firewall rules and demonstrated how traffic filtering enhances system security.
