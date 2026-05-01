# 📑 Port Scanning Report using Nmap

## 1. 🧾 Introduction

Port scanning is a fundamental technique in cybersecurity used to identify open ports and services running on a target system. It plays a key role in the **reconnaissance phase** of penetration testing.

This project demonstrates how to perform port scanning using **Nmap** and analyze the results to understand potential security risks.

---

## 2. 🎯 Objectives

- To understand the concept of port scanning  
- To perform network reconnaissance using Nmap  
- To identify open ports and services  
- To analyze potential security risks  

---

## 3. 🛠️ Tools Used

- **Nmap** (Network Mapper)  
- Terminal (macOS / Kali Linux)

---

## 4. 🖥️ Target Information

- **Target:** scanme.nmap.org  
- **Purpose:** Safe and legal testing (provided by Nmap)

---

## 5. ⚙️ Methodology

The following command was used:

```bash
nmap -sS -sV -O scanme.nmap.org
