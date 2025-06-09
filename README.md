# Task 5: Capture and Analyze Network Traffic Using Wireshark

## Objective
To capture live network packets using Wireshark and identify at least three different network protocols from the traffic.

---

## Tools Required
- **Wireshark** (Free, open-source packet analyzer)

---

## Steps Performed

1. **Installed Wireshark** on my system.
2. **Started a capture** on the active network interface (e.g., Wi-Fi).
3. Generated traffic by:
   - Visiting websites (e.g., `example.com`)
   - Running `ping google.com` in terminal.
4. **Stopped the capture** after ~1 minute.
5. Used display filters to analyze different protocols:
   - `http`
   - `dns`
   - `tcp`
6. Identified and documented key details of at least **three protocols**.

---

##  Deliverables

- `network_traffic_capture.pcapng` – The packet capture file.
- `report.md` – A short report describing:
  - Protocols identified
  - Packet summaries
  - Key observations

---

##  Protocols Identified

| Protocol | Description                         | Example Use Case                  |
|----------|-------------------------------------|-----------------------------------|
| TCP      | Transport layer protocol            | Reliable communication            |
| DNS      | Domain Name System                  | Resolving domain names to IPs     |
| HTTP     | HyperText Transfer Protocol         | Web browsing                      |



