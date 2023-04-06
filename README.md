# azure-network-protocols
<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, DNS, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create Resources
- Install Wireshark
- Inspect Network Traffic
<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/CGxN6Xt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Logging into Azure and creating our resources and virtual machines should be our first step.  
</p>
<br />

<p>
<img src="https://i.imgur.com/2vy8qa6.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating our resources the next step is to Install wireshark within our VM 1(Windows 10).
</p>
<br />

<p>
<img src="https://i.imgur.com/EVMRvx6.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open Wireshark and filter for ICMP traffic only.
Retrieve the private IP address of VM 2(Ubuntu Server 20.04) and attempt to ping it from within VM 1(Windows 10).
Observe ping requests and replies within WireShark.

</p>
<br />
