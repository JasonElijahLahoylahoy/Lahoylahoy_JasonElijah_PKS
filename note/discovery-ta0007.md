# Discovery (TA0007)

## Overview

Discovery techniques help attackers understand systems and networks before lateral movement.

---

# Goals of Discovery

- Topology mapping
- Identity harvesting
- Target selection
- Defense evasion

---

# Discovery Taxonomy

## Identity & Access

- T1087 Account Discovery
- T1069 Permission Groups
- T1201 Password Policy Discovery

## Network & Infrastructure

- T1046 Network Service Discovery
- T1580 Cloud Infrastructure Discovery

## System State & Environment

- T1057 Process Discovery
- T1518 Software Discovery

---

# T1046 Network Service Discovery

Attackers scan for:

- Open ports
- Running services
- Vulnerable systems

## Tools

- Nmap
- Ping
- mDNSResponder

---

# T1087 Account Discovery

Attackers enumerate:

- Local users
- Domain users
- Cloud accounts

## Objectives

- Privilege escalation
- Password spraying
- Phishing target identification

---

# Evasion Techniques

## T1622 Debugger Evasion

Avoids malware analysis tools.

## T1497 Sandbox Evasion

Detects virtualized environments.

---

# Host & System Discovery

## T1083 File and Directory Discovery

Searches for:

- Sensitive files
- Backups
- Credentials

## T1057 Process Discovery

Enumerates running processes.

## T1012 Query Registry

Queries Windows registry keys.

---

# Cloud Discovery Techniques

## T1580 Cloud Infrastructure Discovery

Enumerates:

- Cloud instances
- Buckets
- Load balancers

## T1619 Cloud Storage Object Discovery

Searches exposed cloud objects.

---

# Discovery Target Matrix

| Domain | Targets |
|---|---|
| Endpoint | Files, processes, registry |
| Network | Ports, shares, subnets |
| Cloud | IAM, buckets, dashboards |

---

# Detection & Prevention

## TTP-Based Detection

Detects attacker behaviors.

## Anomaly-Based Detection

Uses machine learning.

## IOC-Based Detection

Detects hashes, IPs, and domains.
