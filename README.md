# DNS Lookup and Traceroute Tool

A Python-based network diagnostic utility for performing DNS resolution, traceroute analysis, and latency checks. Built using low-level networking libraries such as `socket` and `scapy`, this tool is designed for educational, troubleshooting, and network monitoring purposes.

## Features

- Resolve domain names to IP addresses using custom or system DNS servers
- Perform traceroute to track packet paths and identify routing issues
- Measure per-hop latency
- Support both IPv4 and basic IPv6 (where applicable)
- Command-line interface for ease of use

## Technology Stack

- **Language**: Python
- **Libraries**:
  - `socket` – for DNS resolution and basic networking
  - `scapy` – for sending/receiving low-level network packets
  - `argparse` – for command-line argument parsing
  - `time` – for latency measurement

