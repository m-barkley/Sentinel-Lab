# Sentinel-Lab
<h1>Failed RDP to IP Geolocation Information</h1>

##


<h2>Description</h2>
In this lab, I successfully set up Azure Sentinel, a Security Information and Event Management (SIEM) solution, and connected it to a live virtual machine that is acting as a honeypot. By utilizing a PowerShell script, I was able to gather the geolocation information of the attackers. This feature provides real-time visibility into various attacks, particularly RDP brute force attacks, originating from different locations worldwide. To enhance the monitoring capabilities, I developed a custom PowerShell script that performs geolocation lookup of the attackers and visualizes the data on an Azure Sentinel Map. This visualization provides an intuitive representation of the global distribution of the attacking activities, helping to identify patterns, trends, and potential areas of concern. Overall, this setup enables comprehensive threat detection and monitoring, leveraging the power of Azure Sentinel's advanced security analytics and visualization capabilities.
<br />
<br />

<img src="https://i.imgur.com/iapl6YC.png" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>

</p>
  
</p>
<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Attacks from Tunisia coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://i.imgur.com/UtIAqAf.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<p align="center">
<img src="https://i.imgur.com/E1E3BkL.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
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
