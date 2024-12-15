<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configurations</h1>
This demonstrates the necessary changes I make to configure osTicket so it can be used as a proper ticketing system.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- osTicket 

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (21H2)


<h2>Configuration Steps</h2>

<p>

After Installation of OS Ticket we will need to configure Roles for grouping permissions.


  
<img src="https://i.imgur.com/V1ZmNsd.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/AE6Fw5m.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>



First on the top right panel you can see the Admin Panel click on this tab  ,now navigate to > Agents > Roles add a new role.
Name this Supreme Admin. They will need access to all components. Next move to permissions and select all boxes as the Supreme Admin will be allowed access to all areas areas in Tickets/ Tasks /and Knowledgebase.Once complete add role and now, a new role  for Supreme Admin was added.


<img src="https://i.imgur.com/AtMPBCO.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/Jrersip.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/u9R8Guz.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/ZpqCv0T.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/SV0bnSx.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/MWM32ts.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/YlM623I.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/2WTIUAd.png" height="80%" width="80%" alt="Configuration Steps"/>


<p>
After Installation of OS Ticket we will also need to configure departments.This will be for Ticket visability. Help desk vs SYSAdmin , VS Networking.
We will go to Departments and add new.
Now in Add new Department under parent select Top-Level- Department and next name this Sysadmins and leave all settings the same. Scroll down and create dept.And now we have added SysAdmins to the list of Departments.




<p>
<img src="https://i.imgur.com/2WTIUAd.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/Cqtzs2i.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/TzTaZYS.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/rAF36uR.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/AoD1SI1.png" height="80%" width="80%" alt="Configuration Steps"/>




  
</p>


Once the Departments are setup we will now configure Teams. From the same screen now navigate to the Teams tab and now add a new team.
Name this Online Banking.
<p>




<img src="https://i.imgur.com/AoD1SI1.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/q8lQuHt.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/qpW8wt6.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<br />

<p>

</p>

Now we will create and configure agents /workers.
<p>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<br />

<p>

</p>
<p>
We will also have to add Users/ Customers 
</p>
<br />
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<p>

</p>
<p>
Once the steps above are created we will now need to set SLA priorities 
</p>
<br />
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<img src="" height="80%" width="80%" alt="Configuration Steps"/>
<p>

</p>
<p>

</p>
<br />

<p>

<p>
Finally, Help Topics need to be created to help users select an appropriate category that describes their problem so that Agents get an idea of what problem is described in the ticket. To make a new Help Topic, enter the Admin panel and open the Manage menu. Click on Help Topics and click on Add New Help Topic. In this case, I have added the following in order to use later for when I create new tickets to resolve: Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Request.
</p>
<br />

<h2>osTicket Configurations are Complete </h2>

Now that the configurations have been set in place, I can now utilize osTicket as a proper ticketing system. I can create tickets and be able to traige them as if I were in a real environment.
