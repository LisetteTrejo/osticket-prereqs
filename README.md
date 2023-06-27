# osticket-prereqs <p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>






<h2>Environments and Technologies Used</h2>

- Microsoft Azure Virtual Machines
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Set up Virtual Machines in Azure
- Installation Files
- Enable IIS with CGI and common HTTP features
- Register PHP within IIS
- Enable Extensions in IIS Manager for osTicket


<h2>Installation Steps</h2>

<p>
<img  height="80%" width="80%" alt="1" src="https://github.com/LisetteTrejo/osticket-prereqs/assets/136425839/8fa4f49d-046d-48b6-ad89-2fb7b0e8bcbc">

</p>
<p>
Step 1, create a resource group containing VM1 running Windows. Connect to this virtual machine using Remote Desktop with its' public IP address and the password that was created.
</p>
<br />

<p>
<img  height="80%" width="80%" alt="2" src="https://github.com/LisetteTrejo/osticket-prereqs/assets/136425839/abdcf05f-5892-4f01-9dfa-0afac2d5a165">

</p>
<p>
Step 2, Install osTicket requirements (Installation Files) but make sure to enable IIS with CG1 and common HTTP features first.
</p>
<br />

<p>
<img height="80%" width="80%" alt="3" src="https://github.com/LisetteTrejo/osticket-prereqs/assets/136425839/e99105f4-04b6-43d6-85c6-601b2dafd98e">


</p>
<p>
Step 3, Create the directory PHP on local C: drive and unzip the contents from PHP7.3.8 onto the drive.
</p>
<br />

<p>
<img height="80%" width="80%" alt="4" src="https://github.com/LisetteTrejo/osticket-prereqs/assets/136425839/6d59a355-8e49-400f-b2c5-c593a9193491">

</p>
<p>
Step 4, Register PHP within IIS. 
</p>
<br /> 
<p>
<img width="1728" alt="5" src="https://github.com/LisetteTrejo/osticket-prereqs/assets/136425839/8d95f762-b9f0-49a3-abb1-8ba4cb1ac4a3">

<img width="1728" alt="5" src="https://github.com/LisetteTrejo/osticket-prereqs/assets/136425839/b30e5b45-ff5c-4f4f-9138-4226d4238327">


</p>
<p>
Step 5, Download osTicket from the Installation Files Folder. Extract and copy "upload" folder to (C:>inetpub>wwwroot). Within (C:>inetpub>wwwroot) , rename "upload" to "osTicket".
</p>
<br />

<p>

<img height="80%" width="80%" alt="6" src="https://github.com/LisetteTrejo/osticket-prereqs/assets/136425839/2c032b8e-76b9-41e3-9324-1add62b25fa9">


</p>
<p>
Step 6, In IIS Manager enable some extensions for osTicket (php_opache.dll, php_imap.dll, php_intl.dll).
</p>
<br />

<p>


<img height="80%" width="80%" alt="7" src="https://github.com/LisetteTrejo/osticket-prereqs/assets/136425839/a922f6ba-822e-4fa4-b792-ab86f35e004b">
<img height="80%" width="80%" alt="Screenshot 2023-06-13 at 11 12 27 PM" src="https://github.com/LisetteTrejo/osticket-prereqs/assets/136425839/50743b86-fb16-4419-97a0-742869b7d50e">



</p>
<p>
Step 7, rename "ost_sampleconfig.php" to "ost_config.php" and continue setting up osTicket.
</p>
<br />

<p>


<img height="80%" width="80%" alt="Screenshot 2023-06-14 at 12 01 22 AM" src="https://github.com/LisetteTrejo/osticket-prereqs/assets/136425839/d21d50fa-6137-4fec-b6dc-ee3eedd657b4">




</p>
<p>
Step 8, Create Admins that are assigned to diffrent teams and departments.
</p>
<br />

<p>




<img height="80%" width="80%" alt="Screenshot 2023-06-14 at 12 07 49 AM" src="https://github.com/LisetteTrejo/osticket-prereqs/assets/136425839/4089a51b-53a8-48f0-99ee-c0e7d790496b">




</p>
<p>
Step 9, Create\configure users (customers).
</p>
<br />

<p>
<img height="80%" width="80%" alt="sla" src="https://github.com/LisetteTrejo/osticket-prereqs/assets/136425839/5dba7c37-caff-403d-9e28-62a9f68f0f16">
<img height="80%" width="80%" alt="Screenshot 2023-06-14 at 12 30 07 AM" src="https://github.com/LisetteTrejo/osticket-prereqs/assets/136425839/521e0cdb-0d61-4e75-bd0b-063164b025e2">





</p>
<p>
Step 10, Configure SLA's and Help Topics.
</p>
<br />

<p>
  <img height="80%" width="80%" alt="Screenshot 2023-06-14 at 1 31 03 AM" src="https://github.com/LisetteTrejo/osticket-prereqs/assets/136425839/ae0271fa-9725-4427-a076-154c441b76f6">

<img height="80%" width="80%" alt="Screenshot 2023-06-14 at 1 32 25 AM" src="https://github.com/LisetteTrejo/osticket-prereqs/assets/136425839/35ca89f4-0a9b-484f-9e2e-ea1b1f457c0f">







</p>
<p>
Step 11, Create osTickets as endusers and solve the tickets as an Admin.
</p>
<br />

<p>



