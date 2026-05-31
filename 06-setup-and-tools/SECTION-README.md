# ⚙️ 06 — Setup & Tools

> **Get your attack machine connected to TryHackMe properly, with VPN security hardened.**

---

## What's in here

A complete guide to connecting **Kali Linux or Parrot Security** to TryHackMe via VPN. Sourced from [@fartaviao's tryhackme-connectkali](https://github.com/fartaviao/tryhackme-connectkali).

| File/Folder | Contents |
|-------------|----------|
| `README.md` | Overview and repo structure |
| `Tutorial.md` | Full step-by-step connection guide |
| `tutorial-write-up.pdf` | Same content in PDF format |
| `Scripts/safevpn-thm.sh` | iptables firewall script to lock down VPN traffic |
| `Screenshots/` | Visual reference for each step |

---

## What you'll be able to do after this

- Connect your Kali / Parrot VM to TryHackMe's VPN network
- Verify connectivity to THM machines
- Use `safevpn-thm.sh` to restrict all internet traffic through the VPN interface only (important for OPSEC and avoiding accidental traffic leaks)
- Complete the TryHackMe Tutorial machine

---

## The `safevpn-thm.sh` script

This script sets up `iptables` rules to:
- Allow traffic only through the THM VPN interface (`tun0`)
- Block all other outbound internet traffic while the VPN is active
- Prevent accidental clearnet traffic during CTF/labs

**Usage:**
```bash
chmod +x Scripts/safevpn-thm.sh
sudo ./Scripts/safevpn-thm.sh
```

Review the script before running — it modifies your firewall rules.

---

## Prerequisites

- TryHackMe account ([tryhackme.com](https://tryhackme.com))
- Kali Linux or Parrot Security (VM or native install)
- OpenVPN installed
- Your `.ovpn` config file downloaded from THM

---

*Source: [github.com/fartaviao/tryhackme-connectkali](https://github.com/fartaviao/tryhackme-connectkali) — credit to @fartaviao (Fausto Artavia Ocampo)*
