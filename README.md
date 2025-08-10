# Task-4-firewall-Setup-Task
Firewall Setup Task
Overview
This task involved configuring and testing basic firewall rules to control inbound network traffic on Windows using Windows Defender Firewall. The specific goal was to block Telnet traffic on port 23.

Steps Completed
Opened Windows Defender Firewall with Advanced Security (wf.msc).

Listed existing inbound firewall rules.

Created a new inbound rule named "block telnet port 23" to block TCP traffic on port 23 for all profiles (Domain, Private, Public).

Documented how to test the rule by attempting a Telnet connection from another device, expecting it to fail.

Described the importance of removing the test rule after verification to restore the original firewall state.

Captured a screenshot evidencing the rule creation and active status.

Testing Notes
Physical testing from another device was not performed but described in detail.

Expected test: Telnet connection attempts on port 23 should be rejected or time out.

Summary
This setup demonstrates basic firewall management skills, specifically controlling inbound connections by blocking insecure services like Telnet. The firewall filters traffic based on rules that allow or deny packets depending on port, protocol, and profiles.

Deliverables Included
Screenshot of the Windows Firewall inbound rule blocking port 23.

Documentation of steps taken.

Summary of firewall filtering functionality.

<img width="1914" height="1050" alt="Screenshot 2025-08-09 204309" src="https://github.com/user-attachments/assets/531f912f-969e-4d1e-b13e-bc7a3143db3e" />
