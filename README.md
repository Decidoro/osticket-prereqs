<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
In this tutorial, we follow our instructor as he demonstrates the osTicket installation. <br>A system used to practice using a ticketing system dealing with user's tickets and their permissions.<br/>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Database (HeidiSQL)
- IIS (To host osTicket)
- osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/QgU5hrq.png" height="80%" width="80%"/>
</p>
<p>
To begin we create a resource for our virtual machine to be assigned to. <br>We create a virtual machine where our ticketing system will be installed with all the dependencies.
</p>
<br />

<p>
<img src="https://i.imgur.com/EKTAA4W.png" height="80%" width="80%"/>
</p>
<p>
Next, we install Heidi, which is a database management tool used to run osTicket. <br>We then create a new database for our ticketing system.<br><br>**NOTE: Other dependencies are required to run the ticketing system that aren't shown.
</p>
<br />

<p>
<img src="https://i.imgur.com/uJKcAfn.png" height="80%" width="80%"/>
</p>
<p>
After the database is set up, we need to enable a few more prerequisites in PHP so our ticketing system can run.
</p>
<p>
<img src="https://i.imgur.com/PrD3TvT.png" height="80%" width="80%"/>
</p>
<p>
Finally, we set up our osTicket account log-in. <br>Here we also create our admin account and connect the database our ticketing system will use.
</p>
<br />
