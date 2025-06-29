# Firewall-on-Windows---4

# Tools:
- Windows Defender Firewall with Advanced Security

# Steps
1. Opened **Windows Defender Firewall with Advanced Security**.
2. Created a new Inbound Rule to **block TCP Port 23 (Telnet)**.
3. Created a new Inbound Rule to **allow TCP Port 22 (SSH)**.
4. Verified rules appear under Inbound Rules.
5. Successfully tested that port 23 was blocked.
6. Removed the "Block Telnet Port 23" rule after testing.

# Summary:
Firewall successfully blocked Telnet traffic while keeping SSH open. This exercise demonstrated basic inbound traffic control using Windows Firewall.
