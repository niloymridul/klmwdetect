<p align="center">
<img src="https://github.com/niloymridul/virtualbox-prereqs/assets/139414980/63225cc3-499b-455a-b390-e97d3b7f3d6c" height="40%" width="40%" alt="VirtualBox logo"/>
</p>

<h1>VirtualBox - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the virtual machines through VirtualBox<br />

<h2>Environments and Technologies Used</h2>

- VirtualBox (Virtual Machines/Compute)
- Kali Linux
- Windows 10
  
<h2>List of Prerequisites</h2>

- Computer or Laptop
- At least 25 GB of space to spare
- 6 GB of ram to spare
- Good and steady internet connection to download heavy files
- The ability to turn on virtualization.

<h2>Installation Steps</h2>

<p>
Virtualbox is a virtualizer that is used for both servers and desktops. A virtualizer simply put is software that loads the equivalent of computers on your computer. You can load various OS (operating systems) and have them interact with each other. And because it's not physical hardware you can also destroy them as well. All within one computer.
</p>
<br />
<p>
With this in mind, we will plan on downloading and configuring it for this lab. But first, you will need to make sure you have a computer that can handle virtualization. 
</p>

- Computer or Laptop
- At least 25 GB of space to spare
- 6 GB of ram to spare
- Good and steady internet connection to download heavy files
- The ability to turn on virtualization.

<p>
If you think your PC has all of the requirements then we will do the last step before downloading the software. First, you will need to enable virtualization. By turning this on, your computer will be able to create virtual machines on your pc. This is within your NETBIOS and boot settings of your pc.

Once that is out of the way, we can start by clicking the link below.
</p>

https://www.virtualbox.org/wiki/Downloads

<p>
<img src="https://github.com/niloymridul/virtualbox-prereqs/assets/139414980/434a8f03-6efd-4f0b-934d-fad20eadf2be" height="80%" width="80%" alt="VirtualBox"/>
</p>

<p>
This link should take you to the VirtualBox website where you can download the package for the host computer(your PC's operating system and the actual hardware) and click on the exe file that is downloaded. Hit yes.

Afterward, click next to start configuring and then click browse to see where you want to store it. Then click yes and start installing the program. When you finish you will need to download the two virtual machines. Click on both of the links and download them in a safe location. Please refer to the images below to see where to click and download.
</p>
<br />

https://developer.microsoft.com/en-us/windows/downloads/virtual-machines/

https://www.kali.org/get-kali/#kali-virtual-machines

<p>
<img src="https://github.com/niloymridul/virtualbox-prereqs/assets/139414980/bc7f1135-bb44-4575-9b96-fa6dd25dc031" height="70%" width="70%" alt="VirtualBox"/>
</p>
<p>
<img src="https://github.com/niloymridul/virtualbox-prereqs/assets/139414980/b8a54041-55b5-4152-934a-fa388c6c1d7b" alt="VirtualBox"/>
</p>

<p>
Afterward, you will need to open up Virtualbox and then import the virtual machines in. First, open VirtualBox Manager and then new at the top. Then give it a name. The folder is where the virtual machine will be placed so click the folder button. Then depending on where you downloaded the iso file (unpacking the Winrar package), you will have to click other in the dropdown menu and then go to the path where the iso file is. The VirtualBox Manager will automatically load it in. If in the event, you clicked on the vdi or VirtualBox file, a virtual machine will already be loaded on Virtualbox and will then open the operating system for you.
</p>

<p>
<img src="https://github.com/niloymridul/virtualbox-prereqs/assets/139414980/683c57b0-ec65-410b-bc16-fd6a2cd4c837" alt="VirtualBox"/>
</p>

<p>
After hitting next you will then have to create a username and password for the operating system. Be sure to write it down or remember it. Afterward, you will be taken to the hardware page. The more specs you give to the Virtual Machine, the more you take away from your actual computer so keep that in mind. You will then need to allocate virtual hard disk space. For this part of the Virtual Machine, the space will only be used if you use the virtual machine. 
</p>

<p>
After you finish it, the manager will give you a summary of the virtual machine and then, if everything looks ok to you, you can then finish and the virtual machine will be fully implemented. And now do the same for the other machine(Kali or Windows or another OS you had in mind) and congratulations. You now have two operating systems on your device to experiment with which we will do in the next park.
</p>
