<h1>Active Directory Home Lab (Oracle VirtualBox)</h1>

<p>
  A hands-on cybersecurity project demonstrating how to build and configure a functional Windows Active Directory environment using Oracle VirtualBox.  
  Includes step-by-step setup of a Domain Controller, Windows client, DNS configuration, and automated user creation with PowerShell.
</p>

<h2>Project Overview</h2>

- Build a Windows Server **Domain Controller (DC)**
- Configure **DNS, AD DS**, and promote to create the domain: <strong>lab.local</strong>
- Create a Windows 10/11 **domain-joined client**
- Configure a VirtualBox **Internal Network**
- Automate **bulk user creation** using PowerShell + CSV
- Perfect for blue-team labs, identity management practice, and security engineering fundamentals.

<h2>Repository Contents</h2>

- <strong>README.md</strong> — Documentation and setup instructions  
- <strong>/powershell/Add-DomainUsers.ps1</strong> — Script to bulk-create AD users  
- <strong>/powershell/lab-users.csv</strong> — CSV template used for automation  
- <strong>/docs/</strong> — Optional screenshots or references  

<h2>PowerShell Automation</h2>

<p>Example command to run bulk user import:</p>

```powershell
.\Add-DomainUsers.ps1 -CsvPath ".\lab-users.csv"
