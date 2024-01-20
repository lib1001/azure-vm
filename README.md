<p align="center">
  <img src="https://i.imgur.com/0WCSsqE.png" alt="Azure Virtual Machine logo">
</p>

<h1>Creating a Virtual Machine in Microsoft Azure</h1>
This tutorial outlines the creation of Virtual Machines in Windows 10 and Linux.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure 
- Remote Desktop
- Wireshark
- PowerShell

<h2>Operating Systems Used </h2>

- Linux
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4


<h2>Deployment and Configuration Steps</h2>

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


- Create an Administrator account. Keep your login information stored in a secure place. Click the checkbox under "Licensing," and press the "Review + Create" button.
 <p>

  <img src="https://i.imgur.com/aOzhTB9.png" height="80%" width="80%" alt="Creating an account">
  <img src="https://i.imgur.com/W2Lnf7k.png" height="40%" width="40%" alt="licensing checkbox">
</p>
<br />
