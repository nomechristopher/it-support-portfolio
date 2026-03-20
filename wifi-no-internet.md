Project 1: Resolving Wi-Fi “No Internet, Secured” Issue (Windows 10)
Problem

User reported that their laptop was connected to Wi-Fi but displayed “No Internet, secured”, preventing access to online resources. Other devices on the same network were functioning normally.

Diagnosis

Verified issue was isolated to a single device

User confirmed other devices had working internet access

Ran ipconfig and identified 169.254.x.x (APIPA address)

Determined system failed to obtain a valid IP address from DHCP

Resolution

Guided user to open Command Prompt

Executed:

ipconfig /release

ipconfig /renew

Successfully obtained a valid IP address (192.168.x.x range)

Restored internet connectivity

Outcome

Network connection fully restored

User regained internet access without further issues

Key Skills Demonstrated

Network troubleshooting (DHCP/IP addressing)

Command-line tools (ipconfig)

Root cause identification

Clear user communication

What I Learned

This scenario reinforced the importance of identifying whether an issue is device-specific or network-wide. I also gained a deeper understanding of APIPA addresses and how to resolve DHCP-related issues efficiently.
