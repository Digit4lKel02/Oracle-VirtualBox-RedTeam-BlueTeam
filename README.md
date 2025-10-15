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
Configured the VM to have an internal network so that it can communicate with other VM's but not my host. Kali Linux VM network was also configured to be internal <br/>
<img src="https://imgur.com/UyBVvfR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
 Statically assigned IP addresses so that both machines can communicate with each other via my windows machine. Repeat this process with the Kali Machine.  <br/>
<img src="https://imgur.com/8qcZY4E.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://imgur.com/pOJ3ICp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
 Run msfvenom -l payloads to see what kind of malware is available to use in Kali Linux<br/>
<img src="https://imgur.com/0UKYrik.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
