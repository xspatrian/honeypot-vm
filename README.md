# honeypot-vm
This project is build for Trap the hackers from all over the world .

<h2>Description</h2>
<b>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.
</b>
<br />
<br />
The script is used in this demo where I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot.
We will observe live attacks (RDP Brute Force) from all around the world. I will use a custom PowerShell script to
look up the attackers Geolocation information and plot it on an Azure Sentinel Map!
<br />
<br />

## Tools and resources utilized
1. Azure cloud service
2. RDP
3. ipgeolocation API key


<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

## World map of incoming attacks after 24 hours (geodata) 
![Alt text](https://github.com/xspatrian/honeypot-vm/blob/main/screenshots/honeypot-dashboard.png)




