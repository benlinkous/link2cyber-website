# ✅ LinksOS Bootcamp — Day 44

**Full-Time Learner Track (8–10 hours/day)**  
**Cert Focus:** Network+ (N10-008 or N10-009) — DHCP, DNS, Wireless, and NAT  
**Integrated Focus:** Linux+ (XK0-005) — Hostname resolution, name servers, and wireless tools  
**Goal:** Understand DHCP leasing, DNS name resolution, wireless security, and NAT behavior

---

## 📡 Task 1: DHCP and DNS Overview

**Mapped Objectives:**  
- Network+ 2.3 – DNS, DHCP operation  
- Network+ 2.4 – DHCP lease process and DNS zones

**Actions:**  
- Diagram:
  - DHCP DORA process  
  - Forward and reverse DNS lookups  
- Explain zone files, resolvers, and recursive queries

**Output:**  
- Markdown: `dhcp-dns-overview.md`  
- Diagram (optional): DHCP workflow and DNS resolution

---

## 🔐 Task 2: Wireless Security Concepts

**Mapped Objectives:**  
- Network+ 3.3 – Wireless encryption and protocols  
- Network+ 3.2 – SOHO wireless setup and configuration

**Actions:**  
- Compare WPA2, WPA3, TKIP, AES, PSK, EAP  
- Document wireless attacks (evil twin, deauth, spoofing)

**Output:**  
- Markdown: `wireless-security-guide.md`  
- Table: Protocol | Encryption | Weakness | Replacement

---

## 🧪 Task 3: TryHackMe Labs – NAT, DNS, Wireless

- [TryHackMe: DNS in Detail](https://tryhackme.com/room/dnsindetail)  
- [TryHackMe: Wireless Attacks](https://tryhackme.com/room/wirelessattacks)

**Actions:**  
- Capture DNS behavior or NAT flow  
- Simulate wireless sniffing or mapping with `airodump-ng` (optional)

**Output:**  
- Markdown: `dns-nat-wireless-lab.md`  
- Screenshot: DNS queries, wireless SSIDs, or NAT logs

---

## 🛠️ Task 4: Linux DHCP and DNS Configuration

**Actions:**  
- Review `/etc/resolv.conf`, `/etc/hosts`, and hostname lookup  
- Run `dig`, `host`, and `nmcli device wifi list`  
- Connect to a test wireless network with `nmtui` or `iwconfig`

**Output:**  
- Markdown: `linux-dhcp-dns-log.md`  
- Screenshot: DNS or wireless interface results

---

## 🛠️ Tools Learned Today

| Tool / Command     | Purpose                                        |
|--------------------|------------------------------------------------|
| `dig`, `host`, `nslookup` | DNS resolution and trace              |
| `nmtui`, `nmcli`, `iwconfig` | Wireless interface control         |
| DHCP & NAT Diagram | Visualize leasing and private-public mapping  |

---

## 📁 Documentation Checklist

- [ ] `dhcp-dns-overview.md`  
- [ ] `wireless-security-guide.md`  
- [ ] `dns-nat-wireless-lab.md`  
- [ ] `linux-dhcp-dns-log.md`  
- [ ] Git Commit:
  ```bash
  git add . && git commit -m "Day 44 – DHCP, DNS, Wireless, and NAT" && git push origin main
  ```

---

**📦 Final Export & Backup Step**

Save this file and commit updates to your Obsidian vault and GitHub repo:

```bash
git add . && git commit -m "Daily update – LinksOS Bootcamp Day 44" && git push origin main
```
