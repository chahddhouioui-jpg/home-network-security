# Snort IDS Setup

## What is Snort?
Snort is an open source Intrusion Detection System (IDS).
It monitors network traffic and alerts on suspicious activity.

## Installation
```bash
sudo apt install snort -y
```

## Basic Usage
```bash
# Start monitoring
sudo snort -i eth0

# Monitor specific network
sudo snort -i eth0 -n 100
```

## What it detects
- Port scans
- Suspicious connections
- Known attack patterns
