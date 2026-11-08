# Week 12: Security Tools
## What I Learned
- Captured live network traffic using Wireshark
- Applied display filters to isolate HTTP and DNS traffic
- Followed a TCP stream to read a full HTTP conversation
- Analysed Windows Security logs using Event Viewer
- Learned how SIEM systems centralise log analysis
## Tools Used
- Wireshark (packet capture and analysis)
- Windows Event Viewer (log analysis)
## Key Findings
# Wireshark Packet Capture
- The Packet List Pane with multiple protocols visible (TCP,HTTP, DNS, etc.)
- The display filter bar showing 'http' and the filtered results including a request to neverssl.com
- The TCP Stream window showing an HTTP request (red) and response (blue)
- The display filter bar showing 'dns' with at least one query and response visible
# Log Analysis Evidence
- A successful login event with details visible (account name, logon type, time)
- Failed login attempts
- Audit log cleared events and screenshot showing zero results with the filter active
