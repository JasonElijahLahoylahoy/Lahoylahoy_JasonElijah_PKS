# Initial Access (TA0001) - Phishing (T1566)

 [Phishing (T1566)](02-phishing-t1566.md)
 
## Overview
Phishing is a social engineering technique used to gain unauthorized access by tricking users into revealing sensitive information or opening malicious files.

## Objectives of Phishing
- Steal credentials
- Deliver malware
- Establish initial foothold
- Bypass technical defenses using human manipulation

---

# Types of Malicious Emails

## Spam
Bulk unsolicited email.

## Phishing
Attempts to steal sensitive information.

## Spear Phishing
Targets a specific individual or organization.

## Whaling
Targets executives or high-ranking individuals.

## Smishing
Phishing through SMS messages.

## Vishing
Voice-call-based phishing attacks.

---

# Characteristics of Phishing Emails

- Spoofed sender addresses
- Urgent subject lines
- Suspicious hyperlinks
- Malicious attachments
- Social engineering tactics

---

# How Email Works

1. User composes email
2. SMTP server sends message
3. DNS locates destination mail server
4. MX server receives email
5. Email reaches recipient inbox

---

# Email Header Analysis

## Authentication Mechanisms

### SPF
Validates sender IP addresses.

### DKIM
Uses cryptographic signatures to validate email integrity.

### DMARC
Provides enforcement policies for SPF and DKIM.
