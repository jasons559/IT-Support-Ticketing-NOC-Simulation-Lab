# IT-Support-Ticketing-NOC-Simulation-Lab
<h2>Description</h2>

<p>This project simulates real-world IT support and NOC (Network Operations Center) scenarios, using a ticketing system approach.The goal of this project is to demonstrate practical IT support skills, structured problem-solving, and clear technical communication.</p>
<p>Project consists of over 25 support tickets. Each of the 4 example tickets, documents a common IT issue including: 
<ul>
<li>User Reported Problem</li>
<li>Troubleshooting Steps</li>
 <li>Root cause analysis</li>
 <li>Resolution Process</li>
</ul>
</p>

<b>Skills Demonstrated</b>
<ul>
<li>Active Directory (User & Account Management</li>
<li>Windows Administration</li>
 <li>NFTS Permissions & File Access Troubleshooting</li>
 <li>Network Drive Mapping (UNC Paths)</li>
  <li>Group Policy (GPO) Basics</li>
  <li>Troubleshooting Methodology</li>
 <li>Ticket Documentation & Communication</li>
</ul>

<b>Tools Used</b>
<ul>
<li>Windows 10/11 Virtual Machine</li>
<li>Active Directory Environment(CORP Domain)</li>
 <li>Remote Desktop</li>
 <li>File Explorer/NFTS Permissions</li>
 <li>Command Prompt (takeown, icacls, gpupdate)</li>
</ul>

<b>Ticket Examples</b>
| Ticket # | Issue | Category |
|--------|------|---------|
| 22 | Folder Access Denied | Permissions |
| 24 | Unable to Map Network Drive | Networking |
| 11 | Password Reset | Active Directory |
| 12 | Account Lockout | Security |

<b>Key Takeaways</b>
<p>This project reflects hands-on experience troubleshooting real IT issues in a controlled lab environment, with a focus on repeatable processes and clear documentation.</p>


<h2>Ticket #22 – Folder Access Denied</h2>

## Issue
User unable to access folder. Received "Access Denied" error.

## Troubleshooting
- Checked folder permissions
- Attempted GUI fix (failed)
- Identified broken NTFS permissions

## Resolution
- Used takeown to regain ownership
- Used icacls to reset permissions
- Verified access restored

<h3>1. Ticket Creation</h3>
<p align="center">
<img src="https://github.com/jasons559/IT-Support-Ticketing-NOC-Simulation-Lab/blob/main/images/ticket-22-1-ticket-creation.png" width="70%">
</p>

<h3>2. Error (User Issue)</h3>
<p align="center">
<img src="https://github.com/jasons559/IT-Support-Ticketing-NOC-Simulation-Lab/blob/main/images/ticket-22-2-error-(User-issue).png" width="65%">
</p>

<h3>3. Root Cause (Permissions Issue)</h3>
<p align="center">
<img src="https://github.com/jasons559/IT-Support-Ticketing-NOC-Simulation-Lab/blob/main/images/ticket-22-3-root-cause-(permissions).png" width="65%">
</p>

<h3>4. Fix Applied</h3>
<p align="center">
<img src="https://github.com/jasons559/IT-Support-Ticketing-NOC-Simulation-Lab/blob/main/images/ticket-22-4-fix-applied.png" width="65%">
</p>

<h3>5. Ticket Resolution</h3>
<p align="center">
<img src="https://github.com/jasons559/IT-Support-Ticketing-NOC-Simulation-Lab/blob/main/images/ticket-22-5-ticket-resolution.png" width="65%">
</p>

<h2>Ticket #24 – Network Connectivity Issue</h2>

<h3>Issue</h3>
<p>
User reports they are unable to access internal and external network resources. No internet connectivity is available.
</p>

<h3>Troubleshooting Steps</h3>
<ul>
<li>Verified physical network connection (Ethernet cable connected)</li>
<li>Checked IP configuration using <code>ipconfig</code></li>
<li>Attempted to ping default gateway</li>
<li>Tested DNS resolution using <code>nslookup</code></li>
<li>Restarted network adapter</li>
</ul>

<h3>Resolution</h3>
<p>
Renewed IP address and reset network adapter. Connectivity restored successfully.
</p>

<h3>Screenshots</h3>

<h4>1. Ticket Creation</h4>
<p align="center">
<img src="images/ticket24_1_creation.png" width="65%">
</p>

<h4>2. No Network Connection</h4>
<p align="center">
<img src="images/ticket24_2_no_connection.png" width="65%">
</p>

<h4>3. IP Configuration Check</h4>
<p align="center">
<img src="images/ticket24_3_ipconfig.png" width="65%">
</p>

<h4>4. Troubleshooting (Ping Failure)</h4>
<p align="center">
<img src="images/ticket24_4_ping_test.png" width="65%">
</p>

<h4>5. Resolution (Connection Restored)</h4>
<p align="center">
<img src="images/ticket24_5_resolved.png" width="65%">
</p>



