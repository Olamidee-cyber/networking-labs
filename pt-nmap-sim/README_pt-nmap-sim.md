# Packet Tracer + Simulated & Real Nmap Scan

This lab contains a hybrid network scanning demonstration using both Cisco Packet Tracer and Kali Linux.

---

## 📦 Contents

| File Name               | Description                                  |
|------------------------|----------------------------------------------|
| `fixed-nmap-sim-topology.pkt` | Packet Tracer file simulating basic network topology |
| `PT + Simulated Nmap Scan.docx` | Word doc report explaining the simulation approach |
| `pt-quick-scan.txt`     | Nmap quick scan of top 1000 TCP ports       |
| `pt-aggressive-scan.txt`| Aggressive Nmap scan with OS detection      |
| `pt-os-detect.txt`      | OS detection-only scan                      |
| `pt-udp-scan.txt`       | UDP top 100 port scan                       |
| `scan_10.0.3.2.txt`     | Full TCP port scan of target `10.0.3.2`     |

---

## 🧪 Key Concepts Demonstrated

- **Ping sweep (host discovery)** using `nmap -sn`
- **Service and port detection** using `nmap -sV -p-`
- **UDP enumeration** on top 100 ports
- **OS fingerprinting**
- **Manual port simulation** using `netcat` in Kali VM

---

## 🛠 Tools Used

- **Cisco Packet Tracer**
- **Kali Linux (VirtualBox + WSL)**
- **Nmap**
- **Netcat (`nc`)**

---

## ✅ Outcome

This lab demonstrated simulated and real scanning workflows, including firewall evasion limitations, full port scans, and basic recon strategies.
