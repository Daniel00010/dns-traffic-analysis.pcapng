 DNS & HTTPS Traffic Analysis

 📘 Overview
This is a basic cybersecurity project using Wireshark to analyze DNS and HTTPS traffic on my local machine.

 🔧 Tools Used
- Wireshark
- Browser (visited https://example.com)

 📡 What I Did
1. Started a packet capture on my Wi-Fi interface using Wireshark.
2. Visited [https://example.com](https://example.com) to generate some web traffic.
3. Filtered the results using `tcp.port == 443` to isolate HTTPS traffic.
4. Observed encrypted traffic and DNS resolution in the capture.

 📎 Project Files
- `dns-traffic-analysis.pcapng`: Saved packet capture

 💡 What I Learned
- How to use Wireshark to sniff and filter network traffic
- How DNS and HTTPS traffic appears in packet captures
- Basic understanding of TCP port 443 and HTTPS encryption

 🚀 Future Ideas
- Try simulating a basic DDoS or port scan in a virtual lab
- Use tshark (command-line Wireshark) to automate analysis
