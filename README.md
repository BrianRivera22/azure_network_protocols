<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

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

 1) Create VMs in the same Virtual Network/Subnet
 2) Observe ICMP traffic
 3) Configure firewall (Network Security Group)
 4) Observe SSH traffic
 5) Observe DHCP traffic
 6) Observe DNS traffic
 7) Observe RDP traffic

<h2>Actions and Observations</h2>

<h4>First, I created VMs in the same Virtual Network/Subnet</h4>
<p>
<img src="https://github.com/BrianRivera22/azure_network_protocols/blob/main/Lab%201%20step%201/1%20resource%20group.png"/>
<img src="https://github.com/BrianRivera22/azure_network_protocols/blob/main/Lab%201%20step%201/2%20windows%20vm.png"/>
<img src="https://github.com/BrianRivera22/azure_network_protocols/blob/main/Lab%201%20step%201/3%20linux%20vm.png"/>
<img src="https://github.com/BrianRivera22/azure_network_protocols/blob/main/Lab%201%20step%201/4%20vm%20environment.png"/>
</p>
<p>
Observation: This first step involved creating my virtual environment and organizing everything into the correct resource group and network so that communication could run efficiently for this lab. This set the tone for the rest of my project.
</p>
<br />

<h4>Observing ICMP traffic</h4>
<p>
<img src="https://github.com/BrianRivera22/azure_network_protocols/blob/main/Observe%20ICMP%20Traffic/1.png"/>
<img src="https://github.com/BrianRivera22/azure_network_protocols/blob/main/Observe%20ICMP%20Traffic/2.png"/>
<img src="https://github.com/BrianRivera22/azure_network_protocols/blob/main/Observe%20ICMP%20Traffic/3.png"/>
<img src="https://github.com/BrianRivera22/azure_network_protocols/blob/main/Observe%20ICMP%20Traffic/4.png"/> 
</p>
<p>
Observation: Wireshark helped me understand and recognize IP packets and information about network conditions, like when a service is unavailable or when a host can't be reached. The ICMP traffic filter was useful to pinpoint the traffic when I used the ping command. The “ipconfig /all” command helped verify that the IP Address and MAC Address were correct.
</p>
<br />

<h4>Configuring firewall (Network Security Group)</h4>
<p>
<img src="https://github.com/BrianRivera22/azure_network_protocols/blob/main/Configuring%20a%20firewall%20%5BNetwork%20Security%20Group%5D/1.png"/>
<img src="https://github.com/BrianRivera22/azure_network_protocols/blob/main/Configuring%20a%20firewall%20%5BNetwork%20Security%20Group%5D/2.png"/>
<img src="https://github.com/BrianRivera22/azure_network_protocols/blob/main/Configuring%20a%20firewall%20%5BNetwork%20Security%20Group%5D/3.png"/>
<img src="https://github.com/BrianRivera22/azure_network_protocols/blob/main/Configuring%20a%20firewall%20%5BNetwork%20Security%20Group%5D/4.png"/> 
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<h4>Observing SSH traffic</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<h4>Observing DHCP traffic</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<h4>Observing DNS traffic</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<h4>Observing RDP traffic</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
