# cyber-task-5
Wireshark-Network-Capture

##  Objective

To capture live network traffic using Wireshark and identify core protocols used in typical internet activity.

---

##  Tools Used

* **Wireshark** (for packet capturing)
* **Web Browser** (to trigger DNS/TCP activity)

---

##  Steps Performed

1. Installed and launched Wireshark.
2. Selected the active interface: **Wi-Fi 2** (with visible activity).
3. Started a live capture while:

   * Running `google.com` to generate **ICMP**
   * Opening websites to trigger **TCP** and **DNS** traffic
4. Captured for approximately 1 minute.
5. Stopped the capture and saved the file as `network_capture.pcapng`.
6. Applied protocol filters to isolate:

   * `icmp`
   * `dns`
   * `tcp`

---

##  Protocols Identified

| Protocol | Description                                                                         |
| -------- | ----------------------------------------------------------------------------------- |
| ICMPv6   | Internet Control Message Protocol for IPv6 — used by \`ping\` and neighbor discover |
| DNS      | Domain Name System — translates domain names to IP addresses                        |
| TCP      | Transmission Control Protocol — ensures reliable data transfer                      |

---

##  What I Learned

* How to capture live network traffic using Wireshark.
* How to filter specific protocols like ICMPv6, DNS, and TCP.
