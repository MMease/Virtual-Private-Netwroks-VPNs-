<p align="center">
<img src="https://i.imgur.com/V9Mdz0m.png" height="80%" width="80%" alt="VPN_EX"/>
</p>

<h1>Virtual Private Network Configuration</h1>
This tutorial outlines how to use and configure a VPN within Vitual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create Resoure Group and Virtual Machine
- Get Personal PC's IP Address 
- Open Virtual Machine and check IP
- Download Proton VPN
- Check new VPN from selected Countries 

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/g7IMro4.png" height="80%" width="80%" alt="Resoure Group"/>
<img src="https://i.imgur.com/MTiP8Sz.png" height="80%" width="80%" alt="VM"/>
</p>
<p>
First, I created a resource group named "VPN". Next, I created a virtual machine named "VM1".When configuring it, ensure you choose a different region than your current location.
</p>
<br />

<p>
<img src="https://i.imgur.com/rTxxEWR.png" height="80%" width="80%" alt="Personal IP"/>
</p>
<p>
Check the current IP Address of your machine through "https://whatismyipaddress.com"
</p>
<br />

<p>
<img src="https://i.imgur.com/ff2P7GU.png" height="20%" width="80%" alt="MRD"/>
<img src="https://i.imgur.com/ZbXfjeB.jpg" height="60%" width="80%" alt="login"/>
</p>
<p>
Log in to the virtual machine using the login credentials created when configuring the VM.
</p>
<br />

<p>
<img src="https://i.imgur.com/UDzmRDm.png" height="80%" width="80%" alt="New_IP"/>
</p>
<p>
After the VM has opened. Go to Microsoft edge and open up "https://whatismyipaddress.com" to retrieve the Ip address of the Virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/g9GDACz.png" height="80%" width="80%" alt="Proton_Download"/>
</p>
<p>
Download the proton VPN to the virtual machine. You will create a free account that will give you three regions for the VPN. You'll have the option of paying for the more advanced account to add more regions. However, for this project, we don't need it.
</p>
<br />

<p>
<img src="https://i.imgur.com/yASyFag.png" height="80%" width="80%" alt="VPN IP"/>
<img src="https://i.imgur.com/qjN3kSN.jpg" height="80%" width="80%" alt="JP-Netflix"/>
</p>
<p>
Finally, I selected the Japan region for my new VPN. To confirm the switch, I checked the new IP address for the VM. After that, you can see that Netflix advertises the Japan region.
</p>
<br />

