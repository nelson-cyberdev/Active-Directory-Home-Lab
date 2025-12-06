<h1>Active Directory Home Lab (Oracle VirtualBox)</h1>

<p>
  A hands-on cybersecurity project demonstrating how to build and configure a functional Windows Active Directory environment using Oracle VirtualBox.  
  Includes step-by-step setup of a Domain Controller, Windows client, DNS configuration, and automated user creation with PowerShell.
</p>

 </a><br/>
  Built a Domain Controller (DC), created an Active Directory forest/domain, and joined a client machine — all inside a virtualized lab.
</p>

<h2>Lab Goals</h2>

<ol>
  <li>Install Windows Server 2025 in a virtual machine</li>
  <li>Configure basic networking (static IP + DNS)</li>
  <li>Install Active Directory Domain Services (AD DS)</li>
  <li>Promote the server to a Domain Controller</li>
  <li>Create a new forest and domain (e.g., <code>lab.local</code>)</li>
  <li>Prepare the environment so a Windows 10/11 client can join the domain</li>
</ol>

<h2>Lab Environment</h2>

<ul>
  <li><strong>Hypervisor:</strong> Oracle VirtualBox (or similar)</li>
  <li><strong>Server VM:</strong> Windows Server 2025</li>
  <li><strong>Client VM:</strong> Windows 10/11 (optional but recommended)</li>
  <li><strong>Network:</strong> Internal / Host-only network for the lab</li>
</ul>

<h2>Prerequisites</h2>

<ul>
  <li>Windows Server 2025 ISO</li>
  <li>Windows 10/11 ISO (for client)</li>
  <li>At least 16 GB RAM (to comfortably run multiple VMs)</li>
  <li>At least 80–100 GB of free disk space</li>
  <li>Oracle VirtualBox installed on your host machine</li>
</ul>
