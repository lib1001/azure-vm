<p align="center">
  <img src="https://i.imgur.com/0WCSsqE.png" alt="Azure Virtual Machine logo">
</p>

<h1>Creating a Virtual Machine in Microsoft Azure</h1>
This tutorial outlines the creation of Virtual Machines in Windows 10 and Linux.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure 
- Virtual Machine

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Linux

<h2>High-Level Deployment and Configuration Steps</h2>

- Begin creating a Virtual Machine
- Enter in basic information
- Create an administrator account
- Review + Create!


<h2>Deployment and Configuration Steps (Windows 10)</h2>

- Start by opening up the <a href="https://portal.azure.com" target="_blank">Azure portal</a> and search for "virtual machines."
 <br />

- Select the "Create" dropdown menu, then select "Azure virtual machine."


<img src="https://i.imgur.com/w0LTl3P.png" height="40%" width="40%" alt="Create a virtual machine"/>
</p><br />

- Under "Instance Details," provide a unique name for your virutal machine, and select a region. Try to pick the region most relative to your geographic location. 

<p>
<img src="https://i.imgur.com/aEnZ4Gn.png" height="80%" width="80%" alt="instance details"/>
</p>
<br />

- Under "Image," select Windows 10 Pro, and select a size. For this setup, we are using 2 vcpus.
<p>
<img src="https://i.imgur.com/K3B26gn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />


- Create an Administrator account, following the listed requirements. Keep your login information stored in a secure place. Click the checkbox under "Licensing," and press the "Review + Create" button. Once validated, click "Create" to initiate deployment.
 <p>

  <img src="https://i.imgur.com/aOzhTB9.png" height="80%" width="80%" alt="Creating an account">
  <img src="https://i.imgur.com/W2Lnf7k.png" height="40%" width="40%" alt="licensing checkbox">
</p>
<br />

-Congrats! :tada: You have successfully created your first Windows 10 Virtual Machine in Microsoft Azure!

<h2>Deployment and Configuration Steps (Linux)</h2>
- Here we will create a second virtual machine, this time using Linux, using the same virtual network as our first virtual machine.
- Start by opening up the <a href="https://portal.azure.com" target="_blank">Azure portal</a> and search for "virtual machines."
 <br />

- Select the "Create" dropdown menu, then select "Azure virtual machine."


<img src="https://i.imgur.com/w0LTl3P.png" height="40%" width="40%" alt="Create a virtual machine"/>
</p><br />

- Under "Instance Details," select the Resource Group created with our previous virtual machine. Provide a unique name for your virutal machine, and select a region. Be sure to use the same region we used above. 

<p>
<img src="https://i.imgur.com/mSFRB9m.png" height="80%" width="80%" alt="instance details"/>
</p>
<br />

- Under "Image," select Ubuntu Server (Linux), and select a size. For this setup, we are using 2 vcpus.
<p>
<img src="https://i.imgur.com/WzmbTCb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />


- Create an Administrator account, selecting "Password" and following the listed requirements. Keep your login information stored in a secure place. Click the checkbox under "Licensing," and press the "Review + Create" button. Once validated, click "Create" to initiate deployment.
 <p>

  <img src="https://i.imgur.com/DmWvcfg.png" height="80%" width="80%" alt="Creating an account">
  <img src="https://i.imgur.com/W2Lnf7k.png" height="40%" width="40%" alt="licensing checkbox">
</p>
<br />

-Congrats! :tada: You have successfully created your first Linux Virtual Machine in Microsoft Azure!

