# Networking-Lab-Testing-Connectivity-with-ping
# 🧍🏽 Performed By:
**Jessica Stovall**  
Aspiring Cybersecurity Analyst | Army Veteran 

---

## 📌 Lab Objective
Use the `ping` command in the Command Line Interface (CLI) to test network connectivity to an external domain (`facebook.com`) and interpret the returned IP address and latency data.

---

## 🧰 Tools Used
- Windows 11 Command Prompt (CMD)
- Internet connection
- 
- ## 🧪 Steps Performed
1. Opened the Command Prompt.
2. Typed and executed the following command: ping facebook.com
3. Observed the output to verify:
- IP address resolution (e.g., `157.240.22.35`)
- Response time (e.g., `time=20ms`)
- Packet loss statistics

---

## ✅ Lab Results
- The `ping` command successfully resolved `facebook.com` to an IP address.
- Received response packets confirming the system can reach Facebook's servers.
- No packet loss occurred.
- Pinging facebook.com [157.240.22.35] with 32 bytes of data:
Reply from 157.240.22.35: bytes=32 time=18ms TTL=59
Reply from 157.240.22.35: bytes=32 time=20ms TTL=59
...
Ping statistics for 157.240.22.35:
Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
Minimum = 18ms, Maximum = 20ms, Average = 19ms

## 🧠 Key Takeaways
- The `ping` command is a basic but powerful tool for network diagnostics.
- It helps verify if a host is reachable and provides latency information.
- IP resolution confirms DNS is functioning properly.

---
