# Python Nmap Port Scanner

## Overview

This repository contains a Python-based Nmap automation tool designed to simplify network reconnaissance by performing multiple scan types through an interactive command-line interface.

## Features

* SYN ACK Scan
* UDP Scan
* Comprehensive Scan
* Service Detection
* OS Detection
* Script Scanning
* Nmap Version Detection
* Interactive CLI Interface
* Open Port Enumeration

## Requirements

* Python 3.x
* Nmap
* python-nmap

## Usage

Run the scanner:

```bash
python port_scanner.py
```

Enter the target IP address and select a scan type:

```text
1) SYN ACK Scan
2) UDP Scan
3) Comprehensive Scan
```

## Example Output

```bash
IP Status: up
Protocols: ['tcp']
Open TCP Ports: [22, 80, 443]
```

## Skills Demonstrated

* Python Programming
* Nmap Automation
* Network Reconnaissance
* Port Enumeration
* Service Discovery
* Security Tool Development

## Disclaimer

This tool is intended for educational purposes and authorized security assessments only. Always obtain proper authorization before scanning any systems or networks.
