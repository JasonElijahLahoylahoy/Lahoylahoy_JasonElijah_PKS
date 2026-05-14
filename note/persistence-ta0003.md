# Persistence (TA0003)

## Overview

Persistence techniques allow attackers to maintain access even after reboots or credential changes.

Without persistence, attackers lose access after system interruptions.

---

# Key Categories of Persistence

## Account Manipulation

Creating or modifying accounts.

## Boot or Logon Autostart

Automatically executing malware during startup.

## Scheduled Tasks

Using task schedulers for execution.

## Execution Flow Hijacking

Redirecting legitimate processes.

## Browser Extensions

Abusing trusted browser extensions.

---

# T1098 Account Manipulation

Attackers modify administrative groups for persistence.

## Example

Scattered Spider added accounts to:

```text
ESX Admins
