Got it — here's the **clean and GitHub-friendly markdown** version. This version ensures:

* Proper headings
* Code blocks are correctly closed
* Bullet points and spacing are consistent
* No collapsed inline code inside code blocks

You can **copy-paste this directly into GitHub** (as `Nmap_Basics.md`), and it will render cleanly and professionally:

---

````markdown
# 🔍 TryHackMe: Nmap Basics & Advanced Scanning

---

## 🛠️ Key Topics Covered

- Nmap Basics: What is Nmap & Why it is used  
- Common Port Scans  
- Advanced Port Scan Techniques  
- Nmap Scripting Engine (NSE)  
- Searching and Using NSE Scripts  

---

## 🚀 Common Port Scanning Techniques

### 1. **TCP Connect Scan**
- **Flag:** `-sT`
- Full TCP handshake  
- Easily detectable  
- **Use Case:** When SYN scans aren't permitted (e.g., due to restricted permissions)  

### 2. **SYN Scan (Half-Open)**
- **Flag:** `-sS`
- Sends SYN and waits for SYN-ACK, but doesn't complete handshake  
- Stealthier than `-sT`  
- **Default and most popular scan type**  

### 3. **UDP Scan**
- **Flag:** `-sU`
- Probes UDP ports  
- Often slower due to no response on closed ports  

---

## 🧪 Less Common (Advanced) Scan Types

### 4. **Null Scan**
- **Flag:** `-sN`
- Sends a packet with no TCP flags set  
- Used to evade some firewalls  
- May be ineffective on modern systems  

### 5. **FIN Scan**
- **Flag:** `-sF`
- Sends a packet with only the FIN flag  
- May bypass stateless firewalls  

### 6. **Xmas Scan**
- **Flag:** `-sX`
- Sends a packet with FIN, PSH, and URG flags set (lights up like a Christmas tree)  
- Similar use case as FIN/Null scans  

---

## 📂 NSE (Nmap Scripting Engine)

### 🔍 What is NSE?

- A powerful feature of Nmap that allows custom script-based scanning  
- Scripts are written in **Lua**  

---

### 📌 Basic Usage

```bash
nmap --script <script-name> <target>
nmap --script-help <script-name>
````

---

### 🔍 Script Categories

* `auth` – authentication bypass scripts
* `vuln` – check for known vulnerabilities
* `exploit` – active exploitation
* `discovery` – gather additional host/network info
* `malware` – check for infections, backdoors

---

### 🔍 Example Commands

```bash
nmap -sV --script vuln 192.168.1.100
nmap --script-help http-enum
nmap -p 80 --script http-title,http-methods scanme.nmap.org
```

---

## 🧠 Key Takeaways

* Use `-sS` whenever possible for speed and stealth
* UDP scanning is essential for full coverage but slower
* Use `-T4` or `-T5` timing options to control speed
* NSE scripts extend Nmap from simple port scanning to full-blown security auditing
* You can search for scripts using:

```bash
locate *.nse | grep <keyword>
```

---

## ✅ Tasks Completed

* [x] Learned all common and advanced Nmap scanning methods
* [x] Explored and practiced NSE scripting
* [x] Understood when to use different scan types
* [x] Practiced using flags, commands, and script lookups

---

```

Let me know when you want the next room's markdown (e.g., vulnerability scanning, metasploit, etc.), or if you need a homepage `README.md` that links all your rooms like a portfolio!
```
