<p align="center">
<img src="https://github.com/niloymridul/klmwdetect/assets/139414980/3787196e-c042-4313-bdcf-952365e8ad02" height="40%" width="40%" alt="Kali Linux logo"/>
</p>

<h1>Kali Linux, Nmap & Wireshark - Packet Detection </h1>
This tutorial details the steps of using and understanding packet-detecting software. <br />

<h2>Environments & Softwares Used</h2>

- VirtualBox (Virtual Machines/Computer)
- Kali Linux
- Windows 10
- Nmap
- Wireshark
  
<h2>Project Steps</h2>
<p>
If you remember from our last tutorial, we have installed the virtual machine software called VirtualBox Manager and set up two virtual machines for both Kali Linux and Windows. Now we still have only two things to do before we can actually get into the packet detection set up. 
</p>

<p align="center">
<img src="https://github.com/niloymridul/klmwdetect/assets/139414980/206a2b3f-6670-4d89-b910-5b7d9ea78462" height="80%" width="80%" alt="VMBOX look"/>
</p>

<p>First I want you to open VirtualBox Manager if you haven't yet. Then I want you to click on tools above the named virtual machines. After you click on tools, I want you to click on Nat Networks and then create. There are various forms of Networks you can make but for this lab, we will want to create NAT Network. The reason why is because this network mode allows us to connect both our host computer and our virtual machines. If you want, you can give it whatever name you want.
</p>

<p align="center">
<img src="https://github.com/niloymridul/klmwdetect/assets/139414980/f9580457-4b8c-4d11-ad12-8d47e1c1aa07" height="80%" width="80%" alt="VMBOX look"/>
</p>

<p>
After that, go to both virtual machines and press the gear that says settings because we have to make sure that both virtual machines can connect with each other. You will need to go to settings -> network -> adapter 1 for each virtual machine. Click on the dropdown menu, click on attached to, and click Nat Network. Afterward, you will need to click on the specific nat network that you made and named. Click ok and now the settings should be finalized.

Now you can finally start and log in to the virtual machines you have finally made. Click on start for both of them and log in.
</p>

<p align="center">
<img src="https://github.com/niloymridul/klmwdetect/assets/139414980/b2d6bdc1-4f84-4351-9b23-79283af3ddd3" alt="Wireshark logo"/>
</p>

<p>
Now you can finally start and log in to the virtual machines you have finally made. Click on Start for both of them and log in. We will have to install a program called Wireshark on the Windows computer. This will be the last thing we will need to install before we can start packet detection. Click the link below and we will start installing the software.
</p>

[Click here to go to the official download webpage of Wireshark!](https://www.wireshark.org/download.html)

<p>

</p>
