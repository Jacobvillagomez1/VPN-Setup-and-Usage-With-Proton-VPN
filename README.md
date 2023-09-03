# VPN-Setup-and-Usage-With-Proton-VPN
<p align="center">
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h1>VPN Setup and Usage With Proton VPN</h1>
In this tutorial, we are going to make a VPN using Proton VPN and measure the different IP addresses. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- Proton VPN
- Whatsmyipaddress.com


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Use whatsmyipaddress.com to grab your current IP address
- Create a Virtual Machine in Microsoft Azure
- Log into the virtual machine using Remote Desktop Connection
- Use whatsmyipaddress.com to grab your VM IP address
- Download Proton VPN then connect to any VPN
- Use whatsmyipaddress.com to grab your new Proton VPN IP address


<h2>Actions and Observations</h2>

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/474afdee-24eb-46dc-962d-198d0617d678"/>
</p>
<p>
Go to whatismyipaddress.com to grab your current IP address. Open notepad or grab a piece of paper to write it down  
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/6bd772e2-db85-4537-8c31-f2ffb67fff99"/>
</p>
<p>
Go to Microsoft Azure and type Virtual Machine 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/1368238d-044b-467b-b1d3-201fefc9f283"/>
</p>
<p>
Next click create and go to Azure Virtual Machine 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/fbb99a9f-58e6-4eff-b4ff-a0797294442b"/>
</p>
<p>
Go to the Resource Group tab and click create new, the name will be Vm-practice. then click the blue ok button
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/3dd3bf2a-66b8-4bbf-8d07-e1cc1463d586"/>
</p>
<p>
Now go to the Virtual Machine name and type VMP, the region I will put Europe North Europe so we can get a out of America IP address. The Image click Windows 10 Pro version
</p>
<br />


<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/c3f19692-9390-4387-bb62-25ac46a0e498"/>
</p>
<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/55bbedaa-3693-4cd5-b1cb-2cb6e901f227"/>
</p>
<p>
Next the size can be under Standard E2, the username will be named labuser, and the password can be your unique password. Then once your done click the Licensing box in the bottom left. {NOTE} write down yur username, password, and region to rememeber when you log in
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/de16a6f0-7f6e-4370-afd9-ae0d3dcbac3d"/>
</p>
<p>
Next go to the Review and Create tab and click Create on the bottom left side
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/9caa3db1-6b7f-4574-8b90-4de7d0a1500d"/>
</p>
<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/080a6731-1d7e-4eca-9f9e-6411098f6d9a"/>
</p>
<p>
Now the deployment progess will start, then once its finish you will see a green check to the left
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/223ad33f-02b9-43a3-86b1-d3a94b5e8911"/>
</p>
<p>
Now go back to the search bar and type Virtual Machine and you will see VMP was created, click the VM
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/1f10916b-d053-4c43-bca6-04ba20f77797"/>
</p>
<p>
Now go copy the public IP address
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/c3f8bd04-8b79-4085-8b57-2009576f3ef3"/>
</p>
<p>
Type Remote Desktop Conenction on your pc
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/63002229-ce44-4ff5-8799-d00ee129ea61"/>
</p>
<p>
Now copy the IP of VMP in the Computer section, then click connect
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/445a1eea-6254-48b8-be11-72dc1db73b9a"/>
</p>
<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/61f296b8-90fa-4a5c-a0f8-66ec5a795775"/>
</p>
<p>
Now for your username type labuser, and the password section type in your password then click the blue ok button
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/3f4d8a0a-8a08-4a66-97c4-f419121f3505"/>
</p>
<p>
Now click yes to log into the VM
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/67ff3b3d-ced0-48df-8274-68fae0dbd63d"/>
</p>
<p>
Now you should see the VM loading with the name labuser
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/316dbb0e-2596-4de4-afdb-19604cf12ff8"/>
</p>
<p>
Now click no for the following in the image above
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/757ba510-9f32-4db1-b079-84f39ab643c0"/>
</p>
<p>
Now click yes for the networks tab when it pops up
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/9a8530c0-a988-4b49-8600-e0a044a79faf"/>
</p>
<p>
Now open microsoft excel and click start without your data
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/26f2717b-6cae-4c2f-b577-e4f3e19e25ea"/>
</p>
<p>
Then click continue without this data 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/3b282d2e-c1df-4546-a4f7-401e811d97e0"/>
</p>
<p>
Then click confirm and continue 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/ca0f42c7-8c64-4365-950c-2de9c7f5d42b"/>
</p>
<p>
Then click confirm and start browsing 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/00835c30-edb4-4073-8808-21e723672fd4"/>
</p>
<p>
Then type whatismyipaddress in the search bar and click the site
</p>
<br />
