# SentinelLab: SOC Monitoring Lab with Wazuh and Suricata

SentinelLab is a beginner-friendly SOC monitoring lab built to practice blue-team security monitoring, log analysis, and alert investigation using Wazuh and Suricata.

## Lab Overview

This lab simulates common security monitoring scenarios in a small virtual environment. Kali Linux was used to generate test activity, while Ubuntu hosted Wazuh and Suricata to collect, analyze, and display security alerts.

## Tools Used

- Wazuh
- Suricata
- Ubuntu Linux
- Kali Linux
- Nmap
- OpenSSH

## Lab Architecture

```text
Kali Linux
Attacker / Test Machine
IP: 192.168.1.11

        ↓

Ubuntu Linux
Wazuh Server + Suricata IDS + SSH Target
IP: 192.168.1.7
