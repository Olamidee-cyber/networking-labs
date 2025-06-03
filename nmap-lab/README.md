# 🔍 Nmap Scanning Lab

This project contains output logs from a hands-on Nmap scanning lab, completed in a Kali Linux environment.

## 📁 Files Included

| Filename             | Description                                       |
|----------------------|---------------------------------------------------|
| `scan_localhost.txt`   | SYN scan (`-sS`) of localhost (127.0.0.1)            |
| `scan_version.txt`    | Version detection (`-sV`) scan of 10.0.3.3          |
| `scan_os.txt`         | OS fingerprinting scan (`-O`) of 10.0.3.3          |
| `scan_ports.txt`      | Port scan on ports 22, 80, and 443 (`-p`)          |
| `scan_script.txt`     | Vulnerability script scan (`--script vuln`)        |

## 🛠️ Tools Used
- **Nmap 7.95**
- **Kali Linux**
- **Local network environment**

## 💾 Notes
- All scans were run with `sudo` and saved using `-oN` for readable output.
- Each scan targeted either localhost or an active LAN IP.

