# 🧠 TryHackMe: Network Fundamentals

**Date:** July 3, 2025  
**Status:** ✅ Completed

---

## 📌 Topics Covered

- OSI Model: 7-layer architecture breakdown (from Physical to Application)
- TCP/IP Stack: Protocol mapping to OSI layers
- Key Protocols:
  - **ICMP**, **TCP**, **UDP**, **IP**, **HTTP/HTTPS**, **Telnet**
- Introduction to:
  - Defensive vs Offensive Security
  - Red Team, Blue Team, Purple Team roles
- Tools Practiced via AttackBox:
  - `ping` – test connectivity
  - `traceroute` – trace packet path
  - `telnet` – test port connectivity
  - `whois` – domain ownership & info
  - `dig` – DNS info
  - `dirb` – directory brute-forcing

---

## 🔧 Tools/Commands Practiced

```bash
ping <IP>
traceroute <domain>
telnet <domain> <port>
whois tryhackme.com
dig tryhackme.com
dirb http://target.com
```
 🧠 Key Learnings
  OSI vs TCP/IP: OSI has 7 layers; TCP/IP typically groups into 4.
  ICMP (Ping) doesn't use TCP/UDP, it's a Layer 3 protocol.
  Traceroute helps identify where packet loss or delay happens.
  Red vs Blue Team:
    Red Team simulates attacks (offensive)
    Blue Team defends (monitoring, detection)
    Purple = collaboration between both
  DNS lookups using dig vs nslookup
  Basic web scanning with dirb for directory enumeration
🧪 Hands-On Summary
  Used TryHackMe’s AttackBox to simulate real-world scanning.
  Practiced querying DNS servers and web directories.
  Understood how tools like ping and traceroute work behind the scenes.
  Saw live responses from DNS/TCP/IP stack tools.
