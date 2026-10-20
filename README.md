# Learn-SecByte-CTF-Labs-Collection-Recon-Vuln-Assessment-Scripting
A curated collection of hands-on cybersecurity CTF labs covering Nmap Scanning, DNS &amp; Subdomain Discovery, Vulnerability Assessment, Python/Bash/PowerShell Scripting, and Hacking Lab Setup from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on virtual lab environment setup, Kali Linux operational basics, security automation scripting (Python, Bash, PowerShell), Git version control, web core technologies (HTTP, HTML, CSS, JavaScript), passive-to-active reconnaissance, DNS enumeration, Nmap scanning, service banner grabbing, and vulnerability assessment fundamentals labs designed for cybersecurity students, CTF players, junior security analysts, penetration testers, and security research trainees.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Building essential security proficiency begins with establishing isolated lab environments, mastering command-line operations, automating workflows with custom scripting, and executing structured reconnaissance and vulnerability assessments. Hosted on [Learn SecByte](https://learn.secbyte.org/), this foundational security operations, scripting automation, and reconnaissance collection provides practical, hands-on technical training to build, scan, enumerate, and analyze modern targets.

From constructing virtualized penetration testing labs and navigating Kali Linux to writing security automation scripts in Python, Bash, and PowerShell, managing source code with Git, executing passive-to-active recon pipelines, performing DNS subdomain discovery, running Nmap network scans, grabbing service banners, and conducting systematic vulnerability assessments, these exercises establish core offensive and defensive readiness.

---

## Lab Collection & Index

Below is the complete, searchable index of all virtual lab setup, Kali Linux, security scripting, Git, web fundamentals, reconnaissance, scanning, and vulnerability assessment challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Virtual Machines and Building a Hacking Lab** | Lab Setup & Core Environments | Hypervisor configuration (VirtualBox/VMware), isolated NAT networks, guest additions, snapshot management | [Access Lab](https://learn.secbyte.org/ctf/virtual-machines-and-building-a-hacking-lab) |
| 2 | **Introduction to Kali Linux** | Lab Setup & Core Environments | Kali Linux OS navigation, package management (`apt`), terminal shortcuts, built-in tool categories, environment setup | [Access Lab](https://learn.secbyte.org/ctf/introduction-to-kali-linux) |
| 3 | **Programming Basics with Python for Pentesters** | Security Scripting & Environment Automation | Python syntax, sockets programming, HTTP requests, custom port scanners, data parsing, automation scripts | [Access Lab](https://learn.secbyte.org/ctf/programming-basics-with-python-for-pentesters) |
| 4 | **Bash Scripting for Automation** | Security Scripting & Environment Automation | Linux shell scripting, command-line arguments, control loops, text filtering (`grep`/`sed`/`awk`), automation pipelines | [Access Lab](https://learn.secbyte.org/ctf/bash-scripting-for-automation) |
| 5 | **PowerShell Basics for Security Professionals** | Security Scripting & Environment Automation | PowerShell cmdlets, pipeline processing, object handling, Active Directory/Windows system querying, task automation | [Access Lab](https://learn.secbyte.org/ctf/powershell-basics-for-security-professionals) |
| 6 | **Git and Version Control Essentials** | Security Scripting & Environment Automation | Repository management (`clone`/`commit`/`push`/`pull`), branch workflows, merge conflict resolution, auditing commit history | [Access Lab](https://learn.secbyte.org/ctf/git-and-version-control-essentials) |
| 7 | **HTTP, HTML, CSS, JavaScript: Web App Fundamentals** | Web Technology Fundamentals | HTTP request/response header inspection, HTML DOM parsing, CSS style analysis, client-side JavaScript execution | [Access Lab](https://learn.secbyte.org/ctf/http-html-css-javascript-web-app-fundamentals) |
| 8 | **Passive to Active Reconnaissance: Finding the Internet Without...** | Reconnaissance, Scanning & Discovery | Open-source intelligence (OSINT), WHOIS/ARIN queries, certificate transparency logs, active host discovery, OSINT synthesis | [Access Lab](https://learn.secbyte.org/ctf/passive-to-active-reconnaissance-finding-the-internet-without) |
| 9 | **DNS Enumeration and Subdomain Discovery** | Reconnaissance, Scanning & Discovery | DNS record querying (A, AAAA, MX, NS, TXT), zone transfers (`axfr`), subdomain brute-forcing, passive DNS parsing | [Access Lab](https://learn.secbyte.org/ctf/dns-enumeration-and-subdomain-discovery) |
| 10 | **Network Scanning with Nmap** | Reconnaissance, Scanning & Discovery | Port scanning modes (SYN/Connect/UDP), OS detection, Nmap Scripting Engine (NSE), scan optimization, output parsing | [Access Lab](https://learn.secbyte.org/ctf/network-scanning-with-nmap) |
| 11 | **Service Enumeration and Banner Grabbing** | Reconnaissance, Scanning & Discovery | Banner extraction via Netcat/Telnet, service version fingerprinting, protocol probing (FTP, SSH, HTTP, SMB) | [Access Lab](https://learn.secbyte.org/ctf/service-enumeration-and-banner-grabbing) |
| 12 | **Vulnerability Assessment Fundamentals** | Vulnerability Identification & Management | Vulnerability scanner operation (OpenVAS/Nessus), CVE lookup, CVSS v3 score calculation, triage, report generation | [Access Lab](https://learn.secbyte.org/ctf/vulnerability-assessment-fundamentals) |

---

## Categories

### 1. Lab Setup & Core Environments
Build isolated virtual lab topologies, configure internal hypervisor networks, manage OS snapshots, and navigate the Kali Linux penetration testing distribution.
- [Virtual Machines and Building a Hacking Lab](https://learn.secbyte.org/ctf/virtual-machines-and-building-a-hacking-lab)
- [Introduction to Kali Linux](https://learn.secbyte.org/ctf/introduction-to-kali-linux)

### 2. Security Automation Scripting, Git & Web Fundamentals
Develop custom security utilities using Python, Bash, and PowerShell, manage security codebases with Git, and inspect core web technologies (HTTP/HTML/CSS/JS).
- [Programming Basics with Python for Pentesters](https://learn.secbyte.org/ctf/programming-basics-with-python-for-pentesters)
- [Bash Scripting for Automation](https://learn.secbyte.org/ctf/bash-scripting-for-automation)
- [PowerShell Basics for Security Professionals](https://learn.secbyte.org/ctf/powershell-basics-for-security-professionals)
- [Git and Version Control Essentials](https://learn.secbyte.org/ctf/git-and-version-control-essentials)
- [HTTP, HTML, CSS, JavaScript: Web App Fundamentals](https://learn.secbyte.org/ctf/http-html-css-javascript-web-app-fundamentals)

### 3. Reconnaissance, Network Scanning & Subdomain Discovery
Transition from passive OSINT collection to active host discovery, execute DNS zone transfers and subdomain brute-forcing, run optimized Nmap scans, and extract service banners.
- [Passive to Active Reconnaissance: Finding the Internet Without...](https://learn.secbyte.org/ctf/passive-to-active-reconnaissance-finding-the-internet-without)
- [DNS Enumeration and Subdomain Discovery](https://learn.secbyte.org/ctf/dns-enumeration-and-subdomain-discovery)
- [Network Scanning with Nmap](https://learn.secbyte.org/ctf/network-scanning-with-nmap)
- [Service Enumeration and Banner Grabbing](https://learn.secbyte.org/ctf/service-enumeration-and-banner-grabbing)

### 4. Vulnerability Assessment & Management
Run automated vulnerability scanners, cross-reference discovered services against public CVE databases, calculate CVSS risk metrics, and prioritize remediation tasks.
- [Vulnerability Assessment Fundamentals](https://learn.secbyte.org/ctf/vulnerability-assessment-fundamentals)

---

## Learning Path

Follow this structured progression path to master virtual lab building, security scripting, active/passive reconnaissance, network scanning, and vulnerability assessments:

1. **Phase 1: Lab Environment Building & Operating System Foundations** — Set up isolated hypervisors and configure Kali Linux workstation environments:
   - [Virtual Machines and Building a Hacking Lab](https://learn.secbyte.org/ctf/virtual-machines-and-building-a-hacking-lab)
   - [Introduction to Kali Linux](https://learn.secbyte.org/ctf/introduction-to-kali-linux)

2. **Phase 2: Security Scripting, Version Control & Web Core** — Build CLI automation tools using Python, Bash, and PowerShell, manage repos with Git, and parse HTTP web elements:
   - [Git and Version Control Essentials](https://learn.secbyte.org/ctf/git-and-version-control-essentials)
   - [Bash Scripting for Automation](https://learn.secbyte.org/ctf/bash-scripting-for-automation)
   - [PowerShell Basics for Security Professionals](https://learn.secbyte.org/ctf/powershell-basics-for-security-professionals)
   - [Programming Basics with Python for Pentesters](https://learn.secbyte.org/ctf/programming-basics-with-python-for-pentesters)
   - [HTTP, HTML, CSS, JavaScript: Web App Fundamentals](https://learn.secbyte.org/ctf/http-html-css-javascript-web-app-fundamentals)

3. **Phase 3: Reconnaissance, Subdomain Discovery & Network Scanning** — Execute OSINT collection, discover subdomains via DNS, perform Nmap port scans, and extract service banners:
   - [Passive to Active Reconnaissance: Finding the Internet Without...](https://learn.secbyte.org/ctf/passive-to-active-reconnaissance-finding-the-internet-without)
   - [DNS Enumeration and Subdomain Discovery](https://learn.secbyte.org/ctf/dns-enumeration-and-subdomain-discovery)
   - [Network Scanning with Nmap](https://learn.secbyte.org/ctf/network-scanning-with-nmap)
   - [Service Enumeration and Banner Grabbing](https://learn.secbyte.org/ctf/service-enumeration-and-banner-grabbing)

4. **Phase 4: Vulnerability Identification & Assessment** — Identify open vulnerabilities across scanned targets, evaluate CVSS scores, and generate assessment reports:
   - [Vulnerability Assessment Fundamentals](https://learn.secbyte.org/ctf/vulnerability-assessment-fundamentals)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario directives, target configurations, and environment parameters on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy analysis toolsets (VirtualBox/VMware, Kali Linux terminal, Python, Bash, PowerShell, Git, Nmap, dig/nslookup, Netcat, OpenVAS/Nessus) inside an isolated workstation.
4. Execute custom Python/Bash scripts, query DNS records, run Nmap scans, grab service banners, analyze vulnerability reports, and capture target flags.

---

## Disclaimer

This repository and its linked challenge resources are strictly intended for educational, threat research, and authorized technical security training purposes. Never deploy automated port scanners, DNS brute-forcing scripts, or vulnerability assessment tools against unauthorized public targets, production networks, or third-party cloud systems.
