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
<p align="center">
<br>
<em>User receives "Access Denied" when opening restricted folder.</em>
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

<h2>Ticket #24 – Incorrect Access to Network Shared Drive</h2>

<h3>Issue</h3>
<p>
User reported being unable to access a shared network drive. The drive either appeared disconnected or was not accessible due to incorrect or missing permissions.
</p>

<h3>Root Cause</h3>
<p>
The shared folder was not properly configured for network sharing, and permissions were either missing or incorrectly set. As a result, the mapped drive could not establish a valid connection.
</p>

<h3>Troubleshooting Steps</h3>
<ul>
<li>Verified that the network drive was missing or displayed as disconnected in File Explorer</li>
<li>Attempted to access the shared folder directly via network path</li>
<li>Reviewed folder sharing settings under the <strong>Sharing</strong> tab</li>
<li>Checked Security permissions to confirm user access rights</li>
<li>Identified that the folder was not properly shared and permissions were not applied</li>
</ul>

<h3>Resolution</h3>
<p>
Reconfigured the shared folder by enabling network sharing and applying the correct permissions. The network drive was then successfully mapped, restoring user access.
</p>

<h3>Screenshots</h3>

<h4>1. Ticket Creation</h4>
<p align="center">
<img src="https://github.com/jasons559/IT-Support-Ticketing-NOC-Simulation-Lab/blob/main/images/Ticket_24_1_Ticket_Creation.png" width="65%">
<br>
<em>Initial support ticket submitted by user reporting inability to access shared drive.</em>
</p>

<h4>2. Mapping Attempt Error</h4>
<p align="center">
<img src="https://github.com/jasons559/IT-Support-Ticketing-NOC-Simulation-Lab/blob/main/images/Ticket_24_2_mapping_attempt_error.png" width="65%">
<br>
<em>Error encountered when attempting to access or map the network drive.</em>
</p>

<h4>3. Unmapped / Disconnected Drive</h4>
<p align="center">
<img src="https://github.com/jasons559/IT-Support-Ticketing-NOC-Simulation-Lab/blob/main/images/Ticket_24_3_Unmappd_Drive.png" width="65%">
<br>
<em>Network drive appears disconnected or unavailable in File Explorer.</em>
</p>

<h4>4. Broken Sharing / Permissions</h4>
<p align="center">
<img src="https://github.com/jasons559/IT-Support-Ticketing-NOC-Simulation-Lab/blob/main/images/Ticket_24_4_Security_Tab__permissions_broken_.png" width="65%">
<br>
<em>Shared folder is not properly configured for network access (not shared / missing permissions).</em>
</p>

<h4>5. Permissions Fixed (Folder Shared)</h4>
<p align="center">
<img src="https://github.com/jasons559/IT-Support-Ticketing-NOC-Simulation-Lab/blob/main/images/Ticket_24_5_Permissions_Fixed_Shared_Folder.png" width="65%">
<br>
<em>Folder sharing enabled and permissions correctly configured.</em>
</p>

<h4>6. Mapped Drive Restored</h4>
<p align="center">
<img src="https://github.com/jasons559/IT-Support-Ticketing-NOC-Simulation-Lab/blob/main/images/Ticket_24_6_Mapped_Drive_Restored.png" width="65%">
<br>
<em>Network drive successfully mapped and accessible after applying fixes.</em>
</p>

<h3>Outcome</h3>
<p>
User confirmed access to the shared network drive was successfully restored. No further issues reported.
</p>

<h3>Skills Demonstrated</h3>
<ul>
<li>Network Drive Mapping</li>
<li>File Sharing & Permissions (NTFS & Share)</li>
<li>Windows File System Troubleshooting</li>
<li>End-User Support & Issue Resolution</li>
</ul>

<h2>Ticket #11 – User Unable to Log In</h2>

<h3>Issue</h3>
<p>
User reported inability to log into their account due to incorrect password.
</p>

<h3>Troubleshooting Steps</h3>
<ul>
<li>Verified login attempt resulted in authentication failure</li>
<li>Confirmed username was entered correctly</li>
<li>Reviewed available password reset options on login screen</li>
<li>Guided user through password reset process</li>
</ul>

<h3>Resolution</h3>
<p>
User was guided through password reset process and successfully regained access to their account.
</p>

<h3>Screenshots</h3>

<h4>1. Ticket Creation</h4>
<p align="center">
<img src="images/ticket11_1_creation.png" width="65%">
<br>
<em>User submits ticket reporting login issue.</em>
</p>

<h4>2. Failed Login Attempt</h4>
<p align="center">
<img src="images/ticket11_2_failed_login.png" width="65%">
<br>
<em>System displays error indicating incorrect credentials.</em>
</p>

<h4>3. Password Reset Option</h4>
<p align="center">
<img src="images/ticket11_3_password_option.png" width="65%">
<br>
<em>Password reset option available on login screen.</em>
</p>

<h4>4. Ticket Resolution</h4>
<p align="center">
<img src="images/ticket11_4_resolved.png" width="65%">
<br>
<em>Issue resolved after guiding user through credential update process.</em>
</p>

<h3>Outcome</h3>
<p>
User confirmed successful login after updating credentials.
</p>


