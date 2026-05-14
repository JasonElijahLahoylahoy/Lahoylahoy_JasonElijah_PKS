# The Adversarial Hook

## Understanding Initial Access and Exploitation

This lecture discusses how attackers gain an initial foothold in systems using social engineering, drive-by compromise, and malicious scripting.

---

# MITRE ATT&CK Framework

The MITRE ATT&CK framework categorizes adversarial tactics and techniques.

## Relevant Techniques

- Initial Access
- Phishing (T1566)
- Command and Scripting Interpreter (T1059)
- Persistence

---

# Drive-by Compromise

Attackers compromise systems when users browse malicious or compromised websites.

## Common Methods

- Injecting malicious scripts into websites
- Malvertising
- Cloud bucket abuse
- Cross-site scripting (XSS)

---

# Fake CAPTCHA Campaign

A real-world attack campaign using:

- SEO poisoning
- Fake CAPTCHA prompts
- PowerShell abuse
- MSHTA execution

## Attack Flow

1. Victim visits compromised site
2. Fake CAPTCHA appears
3. User copies malicious PowerShell
4. Malware downloads silently
5. C2 communication begins

---

# Social Engineering & SEO Poisoning

Attackers lure users through:

- Fake software downloads
- Search engine manipulation
- Fake Apple verification pages

---

# T1059 Command and Scripting Interpreter

Attackers abuse scripting engines like:

- PowerShell
- cmd.exe
- mshta.exe

## Example

```powershell
Invoke-Expression
