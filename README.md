<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this project, I observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create Virtual machines, Vnet, Resource Group
- Observe ICMP Traffic
- Configuring a firewall [Network Security Group]


<h2>Actions and Observations</h2>

<h2>1. Create Virtual machines, Vnet, Resource Group</h2>

<p>
<img src="https://i.imgur.com/vmdzc1w.png" height="40%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/JvLS4Bn.png" height="60%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/UlU18E6.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
This project observes traffic between virtual machines, to start, 2 virtual machines are created, one linux and one windows. ALong with these machines a resource group and Vnet is required. All of these items will be created using the cloud computing platform, Microsoft Azure.
</p>
<br />

<h2>2. Observe ICMP Traffic</h2>
<p>
<img src="https://i.imgur.com/aMKE5S7.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/uwsvL0u.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/WFcNeq0.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
A program called Wireshark is installed in order to record and analyze data traffic between the two virtual machines. Types of traffic that will be observed are ICMP,SSH, DHCP, DNS, and RDP. In addition, connectivity, security poliocies and protocol behaviour is observed. 
</p>
<br />

<h2>3. Configuring a firewall [Network Security Group]</h2>
<p>
<img src="" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
