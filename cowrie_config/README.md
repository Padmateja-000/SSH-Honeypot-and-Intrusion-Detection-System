# Cowrie Configuration

This directory contains configuration notes for deploying the Cowrie SSH honeypot used in this project.

## Environment

- Operating System: Ubuntu Server / Kali Linux
- Honeypot: Cowrie
- Python 3
- Virtual Environment

## Configuration Summary

The following configuration is required before running the monitoring scripts:

- Enable SSH honeypot service
- Configure Cowrie log output
- Store logs under:

```
cowrie/var/log/cowrie/
```

Expected log files:

```
cowrie.log
cowrie.json
```

## Monitoring Scripts

The Bash scripts inside `/scripts` monitor these log files to:

- Extract attacker IP addresses
- Count authentication attempts
- Detect brute-force attacks
- Generate attack reports
- Block malicious IPs using iptables

## Notes

Cowrie configuration files are not included in this repository because they belong to the official Cowrie project. Refer to the official Cowrie documentation for installation and default configuration.
