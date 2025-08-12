# Task 5 — Wireshark Network Capture & Analysis

## Objective
Capture live network packets using Wireshark and identify at least 3 different protocols.

## Environment
- **OS:** Kali Linux (running in VMware Workstation)
- **Tool:** Wireshark
- **Network Interface:** eth0
- **Capture Duration:** ~1 minute

## Protocols Captured
1. **DNS** — Resolves domain names into IP addresses.
2. **TCP** — Reliable, connection-oriented transport protocol.
3. **ICMP** — Used for network diagnostics (e.g., ping).
4. **HTTP** — Protocol for web communication.

## Steps Performed
1. Launched Wireshark and selected the `eth0` interface.
2. Clicked the blue shark fin icon to start capturing.
3. Opened Firefox and visited various websites to generate traffic.
4. Stopped the capture and saved it as `task5.pcap`.
5. Applied filters (`dns`, `tcp`, `icmp`, `http`) to isolate and analyze each protocol.
6. Took screenshots for each protocol.

## Files in This Repository
- `task5.pcap` — The packet capture file.
- `screenshot_dns.png` — Example DNS packet.
- `screenshot_tcp.png` — Example TCP packet.
- `screenshot_icmp.png` — Example ICMP packet.
- `screenshot_http.png` — Example HTTP packet.

## Conclusion
The task demonstrated how to capture, filter, and analyze different network protocols using Wireshark.
