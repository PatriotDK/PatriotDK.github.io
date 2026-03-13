# Linux System Hardening

## Overview

System hardening reduces the attack surface of a Linux system.

Key areas include:

- user management
- service configuration
- firewall rules
- patch management

---

## System Updates

Always keep the system updated:

```bash
sudo apt update
sudo apt upgrade
```

---

## Remove Unnecessary Packages

```bash
sudo apt autoremove
```

---

## Firewall Configuration

Enable firewall:

```bash
sudo ufw enable
```

Check rules:

```bash
sudo ufw status
```

---

## Disable Unnecessary Services

List services:

```bash
systemctl list-unit-files --type=service
```

Disable service:

```bash
sudo systemctl disable service-name
```

---

## Security Principle

A hardened system follows:

- least privilege
- minimal services
- regular patching
