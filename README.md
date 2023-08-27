<h1>Active Derectory Configuration Lab</h1>

 
 ### [YouTube Video for brief overview ](https://www.youtube.com/watch?v=sRi7qTpZLLI)


<h2>Description</h2>
Active Directory Configuration Lab using Oracle Virtual Box.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
 Network Diagram for this lab: <br/>
<img src="img/Screenshot 2023-08-17 192312.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
First, I installed Windows 2022 on Virtual Box and operated basic configurations for Domain Controller, and used PowerShell script to add 1000 new users automatically on the domain
 <br/>
<img src="img/Screenshot 2023-08-17 123815.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 <br/>
 I set up DHCP and established a connection to the Internal Network using a virtual client computer (Windows 10). The client successfully communicated with the Domain Controller server's domain and was also able to ping www.google.com. This indicates that the client is capable of accessing the internet through the Domain Controller.
<img src="img/Screenshot 2023-08-16 140815.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="img/Screenshot 2023-08-17 180208.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
Lastly, I installed AD CS (Certificate Service) and enabled SMB file share service for the future lab: <br/>
<img src="img/Screenshot 2023-08-17 143243.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
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
