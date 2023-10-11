<h1>Failed RDP to IP Geolocation Information</h1>

<h2>Description</h2>
<b>I set up Azure Sentinel, a Security Information and Event Management (SIEM) solution, and connected it to a live virtual machine acting as a honeypot. With this setup, I can actively monitor live attacks, specifically RDP brute force attacks, originating from all around the world. I also used a PowerShell script to retrieve the attackers geolocation information and visualize it on the Azure Sentinel Map.


</b>
<br />
<br />

<br />
<p align="center">
<img src="https://i.imgur.com/lYv9SsU.jpg" alt="RDP event fail logs to iP Geographic information"/>
</p>
<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Failed log on attempts coming in</h2>

<p align="center">
<img src="https://i.imgur.com/pbs6lqS.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="https://i.imgur.com/K3W2TBl.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
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
