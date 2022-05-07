<h1>Raspberry Pi "Pi-Hole" Lab</h1>

<h2>Description</h2>
This project will enable a Raspberry Pi 4 with Raspberry Pi Os Lite to act as a DNS (also, optionally, a DHCP server) server for clients on a home network. This allows the Pi to filter unwanted traffic.
<br />


<h2>Utilities & Technologies Used</h2>

- <b>PuTTY - SSH</b> 
- <b>Windows Network and Sharing Center</b>

<h2>Environments</h2>

- <b>Windows 10</b>
- <b>Debian Linux CLI</b>

<h2>Program Walk-Through</h2>

<p align="center">
Identify the Raspberry Pi's ip address and connect to it via SSH: <br/>
 <br/>
<img src="https://i.imgur.com/PTJPGfP.png" height="80%" width="80%" alt=""/>
<br/>
<br/>
Run this command to install the Pi-Hole software:  <br/>
 <br/>
<img src="https://i.imgur.com/2OxmOZT.png" height="80%" width="80%" alt=""/>
<br />
<br />
Set the DNS server for the client(s) of the Pi-Hole: <br/>
 <br/>
<img src="https://i.imgur.com/M948uzT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Access the Pi-Hole through the Web Interface for further options and configurations:  <br/>
 Credit to https://pi-hole.net <br/>
 <br/>
<img src="https://i.imgur.com/qSyFwqe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
