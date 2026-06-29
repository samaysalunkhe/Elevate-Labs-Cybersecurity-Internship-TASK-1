# 🔍 Task 1: Scan Your Local Network for Open Ports

## 📌 Objective

Discover active devices and identify open TCP ports on the local network using **Nmap**.

## 🛠️ Tools Used

* 🐉 Kali Linux
* 🔎 Nmap

## ⚡ Command Used

```bash
sudo nmap -sS 192.168.1.0/24 -oN scan_results.txt
```

## 📊 Scan Summary

| IP Address    | Open Ports       | Services           |
| ------------- | ---------------- | ------------------ |
| `192.168.1.1` | 53, 80, 443      | DNS, HTTP, HTTPS   |
| `192.168.1.6` | 8008, 8009, 8443 | HTTP, AJP13, HTTPS |

## 📂 Repository Contents

* 📄 `README.md`
* 📄 `scan_results.txt`
* 📸 Network scan screenshots

## 🎯 Key Learnings

* ✅ Network Reconnaissance
* ✅ TCP SYN Scanning
* ✅ Identifying Open Ports
* ✅ Understanding Common Network Services
* ✅ Basic Security Assessment

## 🚀 Conclusion

Successfully scanned the local network, identified live hosts and open ports, and gained hands-on experience with **Nmap** for basic network reconnaissance and security analysis.

---

⭐ **Cyber Security Internship – Task 1**
