<h1>Active Directory Bulk User Creation</h1>

<h2>Description</h2>
Welcome to the first installment of an ongoing series where we explore administrative tasks on Windows Server with a focus on Active Directory. This preliminary project lays the foundation for a series of network configurations and administrative simulations.
<br><br>
This project aims to establish a versatile and dynamic network environment that supports both Windows and Linux clients. By configuring a domain controller with Active Directory Domain Services (AD DS), we will demonstrate the seamless integration of diverse operating systems into a unified domain, facilitating centralized management and streamlined administrative tasks.
Below is the topology of the network that will eventually be created at the end of the projects.
<br />

<p align="center">
Topology: <br/>
<img src="https://imgur.com/a/topology-FLcgYx9.png" height="80%" width="80%" alt="Topology"/>
<br /> 

<h2>Key Configurations</h2>

- <b>Active Directory Domain Services (AD DS): Configure AD DS to manage all users, groups, and computers within the network domain, providing a single point of administration.<b>
- <b>Dynamic Host Configuration Protocol (DHCP): Set up DHCP to automatically assign IP addresses to all connected clients, enhancing network efficiency.<b>
- <b>Domain Name System (DNS): Implement DNS to resolve hostnames to IP addresses, critical for network communication between diverse operating systems.<b>
- <b>Network Address Translation (NAT)/Remote Access Service (RAS): Configure NAT/RAS to enable secure internet access and remote connections, bridging the gap between internal networks and external resources.<b>
<h2>Environments Used </h2>

- <b>Windows Server 2019</b>
- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Topology: <br/>
<img src="https://imgur.com/KJk3gQO.png" height="80%" width="80%" alt="Topology"/>
<br /> 
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
