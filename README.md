<h1>Red Team/Blue Team Lab</h1>

<h2>Description</h2>
Built and managed a fully isolated home cybersecurity lab with attacker and defender VMs to simulate and analyze red-team/blue-team workflows. Used Splunk to detect malicious activity. Configured Sysmon on a Windows endpoint to generate detailed logs and enable endpoint visibility. This lab was achieved using Oracle Virtual box as well as Kali Linux.
<br />


<h2>Tools Used</h2>

- <b>Kail Linux, Splunk, SysMod, Oracle VirtualBox</b> 

<h2>Environments Used </h2>

- <b>Windows 10 Host</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility. Select new: <br/>
<img src="https://imgur.com/ywOAtSi.png" height="80%" width="80%" alt="virtual box image"/>
<br />
<br />
Enter the name and Folder Destination. As well as the ISO image. Check off "Skip unattended installation":  <br/>
<img src="https://imgur.com/Sv9RF8K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
VM specifications for hardware and CPU usage. You will then be taken to a summary screen. Click "Finish": <br/>
<img src="https://imgur.com/621TlPl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/nCSbKyU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After starting the VM, You will see a windows splash screen. Click next and install now:  <br/>
<img src="https://imgur.com/b7KjAdA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After clicking "I don't have a product key", windows 10 pro is the operating system. Goes through prompts, Custom install windows, Windows installs now:  <br/>
<img src="https://imgur.com/iBNy6jn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next, Download Kali Linux @ Kali.org. Install 7zip as well @ 7-zip.org. Once Installed, open your downloads folder. Right click the Kali linux file. Locate 7-zip - Extract to Kali. This will extract Kali and you can open it from the Kali linux folder <br/>
<img src="https://imgur.com/uDhIPka.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once downloaded, Kali linux will now be in the VM. Take a snapshot of Kali via VM settings. This makes it so that if I were to break my VM, I can restore it to it's original point by clicking the "restore" option.   <br/>
<img src="https://imgur.com/FjCnyHc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/5LshnQX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
