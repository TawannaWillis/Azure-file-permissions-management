# Azure-file-permissions-management
A project focused on configuring and managing file permissions in Azure, ensuring security and proper access control for users and groups.

<p align="center">
<img src="https://i.imgur.com/EObLCuZ.png" alt="Permissions Photo"/>




</p>


<br /><h2>Objectives</h2>
A project focused on configuring and managing file permissions in Azure, ensuring security and proper access control for users and groups. <br />

<h2>Skills</h2>

<br />-File Sharing and Permissions Management
<br />-Active Directory Security Group Management
<br />-Windows Server Administration
<br />-Testing and Troubleshooting Access Control

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
  

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 Pro (21H2)

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/OVXNl0I.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/mRs20oU.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/kk5oRi8.png" height="80%" width="80%" alt="Configuration Steps"/>  
<img src="https://i.imgur.com/CDuuNhk.png" height="80%" width="80%" alt="Configuration Steps"/>  
  


<br />-Log into the domain controller (DC-1) as a domain admin.
<br />-Create four folders: read-access, write-access, no-access, and accounting.
<br />-Assign appropriate file share and NTFS permissions for Domain Users and Domain Admins.
 


</p>
<br />

<p>

</p>
<p>
   
</p>
 

<p>
<img src="https://i.imgur.com/mhfZx02.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/32av1PX.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/8UaZH2U.png" height="80%" width="80%" alt="Configuration Steps"/> 

</p>
<p>

  



<br />-Test File Share Access
<br />-Log into Client-1 as a normal user
<br />-Attempt to access and interact with the shared folders (read-access, write-access, no-access) and observe results based on permissions

</p>
<br />

<p>
<img src="https://i.imgur.com/v7I4sk1.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/Iaue1FJ.png" height="80%" width="80%" alt="Configuration Steps"/> 
<img src="https://i.imgur.com/K02vvze.png" height="80%" width="80%" alt="Configuration Steps"/> 
<img src="https://i.imgur.com/qMEksbZ.png" height="80%" width="80%" alt="Configuration Steps"/> 
<img src="https://i.imgur.com/eKV4wNl.png" height="80%" width="80%" alt="Configuration Steps"/>  
<img src="https://i.imgur.com/cmd2Q4J.png" height="80%" width="80%" alt="Configuration Steps"/>  
</p>
<p>
<br />


<br />-Create and Test a Security Group
<br />-Create a security group called ACCOUNTANTS in Active Directory.
<br />-Assign Read/Write permissions for the accounting folder to the ACCOUNTANTS group.
<br />-Test access to the accounting folder as a normal user and observe failure.
<br />-Add the user to the ACCOUNTANTS group, then retest access to confirm permissions update.

</p>
<br />

<p>

</p>


</p>

<p>

</p>
<p>

</p>
<br />

<h2>Lessons Learned</h2>

This lab provided hands-on experience in configuring file share permissions and managing access in a Windows domain. I learned to set up shared folders with specific permissions, create and manage Active Directory security groups, and test access based on group membership. The exercise reinforced key concepts in file sharing, permission management, and troubleshooting access issues in an enterprise environment.
