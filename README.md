# Task5-Capture-and-Analyze-Network-Traffic-Using-Wireshark.
Capture live network packets and identify basic protocols and traffic types.
Objective : Capture live network packets and identify common protocols and traffic types on your machine/network. Deliver:

1. a packet capture file (.pcapng or .pcap) and

2. a short report summarizing protocols observed.

**Prerequisites **: Wireshark (includes the CLI tool tshark). Download: https://www.wireshark.org/download.html.
**Permissions:** Live capture may require admin/root or the OS‑specific capture group (e.g., wireshark on Linux). See Wireshark’s prerequisites and capture setup notes.

**Quick Start (GUI)**

Open Wireshark → choose your active interface (e.g., Ethernet, Wi‑Fi) → click Start Capturing. 
Wireshark

Let it run for 1–3 minutes while you browse a few sites, ping a host, perform a DNS lookup, etc.

Click Stop.

Optional: use the Display Filter bar to focus on traffic 

File → Save As… → choose pcapng (default) or pcap → name it capture-session-YYYYMMDD.pcapng. (Wireshark’s native format is pcapng.)

**Common Display Filters (for Analysis)**

Use these in Wireshark’s Display Filter bar after capture:

ARP: arp

ICMP (ping): icmp

DNS: dns

TCP: tcp (or a port, e.g., tcp.port == 443)

UDP: udp

HTTP: http

TLS/HTTPS handshake

**Notable Findings**

Packet loss, retransmissions, latency indicators, or protocol errors (cite filter/field used).

**Screenshots (optional)**

Protocol Hierarchy, Conversations, example packet decode (with sensitive data redacted).
