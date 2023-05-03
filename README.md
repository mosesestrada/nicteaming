<p align="center">
 <img src="https://i.imgur.com/NOqjMqX.jpg" height="80%" width="80%" alt="VM logo"/>
</p>

<h1>Daily disk backup in Windows</h1>


<h2>Description</h2>
Get ready to experience the power of NIC teaming! NIC teaming, also known as network adapter teaming, is a cutting-edge technology that allows you to group multiple network interfaces (NICs) into a single logical interface. This incredible technology brings a host of benefits to your Windows environment, including increased bandwidth, improved fault tolerance, load balancing, and simplified network management.

And today, I'm going to show you how to take it to the next level! We're going to combine not one, not two, but three network adapters into a single logical interface that will share the same IP address as the primary adapter. 

So buckle up and get ready to witness the power of NIC teaming in action. 
<br />

<h2>Environments Used </h2>

 <b>Windows Server 2022</b> <p>


<h2>Program walk-through:</h2>

<p align="center">


<br />
Right-click Start and then select Settings.
 <br/>
<img src="https://i.imgur.com/mIbxP5u.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Select Update & security.
 <br/>
<img src="https://i.imgur.com/nhvps4p.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
From the left pane, select Backup. From the right pane, select Add a drive.

 <br/>
<img src="https://i.imgur.com/CHjIPxC.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Locate the drive where you want to store the backup. For this demonstration I chose to backup drive (E:).
<br/>
<img src="https://i.imgur.com/cCgpdL7.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Select More options.
(1) Under Back up my files, use the drop-down to select Daily.
Under Keep my backups, use the drop-down to select 6 months or however long you want to keep the backup saved. (2) Under Back up these folders, select Add a folder.
Double-click what you want backed up. For this demo I'm choosing the Data (D:) volume. When you are ready select Choose this folder.


 <br/>
<img src="https://i.imgur.com/S3NAGb6.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Select Back up now.
Wait for the completion of the backup.
 <br/>
<img src="https://i.imgur.com/iWPNpWi.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
That's it! You're done. Your drive will be backed up daily to your designated drive. You can get updates on your backup here in the backup options.
 <br/>
<img src="https://i.imgur.com/MA92P0Y.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
I hope you enjoyed this demonstration.
 <br/>
<img src="https://i.imgur.com/Ogt5mZm.jpg" height="80%" width="80%" alt="DHCP"/>
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
