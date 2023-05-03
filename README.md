<p align="center">
 <img src="https://i.imgur.com/3XRSwO2.jpg" height="80%" width="80%" alt="VM logo"/>
</p>

<h1>Daily disk backup in Windows</h1>


<h2>Description</h2>
Get ready to experience the power of NIC teaming! NIC teaming, also known as network adapter teaming, is a cutting-edge technology that allows you to group multiple network interfaces (NICs) into a single logical interface. This incredible technology brings a host of benefits to your Windows environment, including increased bandwidth, improved fault tolerance, load balancing, and simplified network management.

And today, I'm going to show you how to take it to the next level! We're going to combine not one, not two, but three network adapters into a single logical interface that will share the same IP address as the primary adapter. 

So buckle up and get ready to witness the power of NIC teaming in action. 
<br />

<h2>Environments Used </h2>

 <b>Windows Server 2016</b> <p>


<h2>Program walk-through:</h2>

<p align="center">


<br />
Search for Network and Sharing Center.
 <br/>
<img src="https://i.imgur.com/G0FmySd.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Copy your the IP configuration of your primary ethernet adapter.
 <br/>
<img src="https://i.imgur.com/HUbLC6P.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Back in the Server Manager. Click Local Server then under Nic Teaming click the "Disabled" link.

 <br/>
<img src="https://i.imgur.com/1n4rirv.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Click the Tasks pull down menu and then select "New Team"
<br/>
<img src="https://i.imgur.com/Uj5yWLB.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Select and configure your adapters and settings. Research what settings works best for your network. I used the name NetTeam for this demonstration but you can name it whatever you want. Click ok when finished and close all boxes.

 <br/>
<img src="https://i.imgur.com/bDsCrYP.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Enter the IP configuration of our primary adapter from the first step.
 <br/>
<img src="https://i.imgur.com/jmQiPHR.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
That's it! You're done. Should you check the details of the NicTeam interface it should reflect the primary adapter and we're good to go.
 <br/>
<img src="https://i.imgur.com/BPI2puP.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
I hope you enjoyed this demonstration.
 <br/>
<img src="https://i.imgur.com/S5L4DXX.jpg" height="80%" width="80%" alt="DHCP"/>
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
