# Lab: Local DNS Server with dnsmasq

## 🔧 What I Did
- Set up a local DNS server using `dnsmasq` on my Kali VM.
- Created a custom config (`dnsmasq.conf`) to resolve `test.local` to `10.0.3.15`.
- Pointed my system's DNS to `127.0.0.1` via `/etc/resolv.conf`.
- Verified it worked using `nslookup`.

## ⚙️ Config File
```ini
port=53
domain-needed
bogus-priv
listen-address=127.0.0.1
address=/test.local/10.0.3.15
