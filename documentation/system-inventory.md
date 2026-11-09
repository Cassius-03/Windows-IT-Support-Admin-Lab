Module 01 – Windows System Inventory
1. Objective

Collect and inspect hardware and operating system information from a Windows 11 workstation.

2. Environment
Operating System: Windows 11 Home
Tool: PowerShell
Device Type: Personal workstation
3. Commands Used
powershell
Get-ComputerInfo

Get-CimInstance Win32_OperatingSystem

Get-CimInstance Win32_Processor

Get-CimInstance Win32_LogicalDisk

Get-Process | Sort-Object CPU -Descending |
Select-Object -First 10

4. Results
Information	Result
Windows Version	To be completed
OS Build	To be completed
Processor	To be completed
Installed RAM	To be completed
Available Disk Space	To be completed
Top CPU Processes	To be completed
5. Screenshots

Add screenshots from the screenshots/module-01-system-inventory folder.

6. Findings

To be completed.

7. Challenges

To be completed.

8. Lessons Learned

To be completed.

9. Status

In Progress
