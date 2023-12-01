<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install and enable IIS with Windows CGI
- Install PHP Manager
- Install MySQL
- Install osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/ONnqFvY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


</p>
<p>
Have a Azure tenant created. Once created you need a subscription in order to create a resource group, virtual machine & subnet. Then we can install the dependencies and osTicket through the virtual machine. 
</p>
<br />

<p><img src="https://i.imgur.com/p3OkZkv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
IIS has been succesfully installed after doing the following steps: Control panel ->Programs -> Turn windows features on or off -> Find Internet information services (IIS) on the list and check it off. Click the drop box -> World wide web services -> Application development -> check CGI. Collapse application development and go to Common HTTP features. Make sure all the options are checked off. Lastly, press ok and wait for the it to install. When thats's finished you can test it by typing 127.0.0.1 in a web broweser. The picture above should be the result of that.
</p>
<br />

<p><img src="https://i.imgur.com/7C8atNQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
MySQL, the server database for osTicket was installed sucessfully. 
</p>
<br />

<p><img src="https://i.imgur.com/RUQYP0y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After configurating IIS and registering PHP as an adminstrator, osTicket was installed.
</p>
<br />
