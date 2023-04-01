<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/zqq3gP5.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this lab I wanted to demonstrate the functionality of the osTicketing system from start to finish. This includes creating and resolving a ticket. I also want to demonstrate an understanding SLAs (Service Level Agreements) and how they work with osTicket. Continuing from our the last lab, we want to go into our browswer in our VM and set type in "localhost/osticket". We should see the image above. 
</p>
<br />

<p>
<img src="https://i.imgur.com/x9IFHwD.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/H0Rg9tu.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
We want to start of by creating a ticket so we will click "Open A New Ticket" on the page. It should take us to what is shown in the image above. If you remember in the previous lab that we created a bunch of different "Help Topics" which we can now see in the "Help Topic" section. We also created some users for demonstration purposes such as Karen Karen and Ken Ken. For this example I will be entering Karen's credentials and creating a "Business Critical Outage" ticket. We are going to pretend that Karen is a manager and that she is reaching out to the help desk (which is us) to report an issue. She states that customers are reporting a 404 error when browsing to online banking. We are going to click "Create Ticket" and proceed. 
</p>
<br />

<p>
<img src="https://i.imgur.com/WghSs81.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Since I want to demonstrate how different SLAs work, we can go ahead and open another new ticket by clicking "Open a New Ticket". This time we want to use Ken's credentials. We are going to pretend that Ken is a member of the accounting team and that he wants to report an issue where nobody in his department can use Adobe Reader. Lets also pretend that he selected "Personal Computer Issues" from Help Topics. As before we'll click Create Ticket and move on. 
<br />

<p>
<img src="https://i.imgur.com/GwTxTn6.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
We will go on and create one more ticket again this time as Karen. For this ticket we'll select "General Inquiry" from Help Topics and say that Karen is interested in knowing when her department can expect a hardware refresh. 
</p>
<br />

<p>
<img src="https://i.imgur.com/KawZiql.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that we have demonstrated how tickets are created, we can now get into showing how they are read and resolved. To do this, we can go back into our browser with osTicket (localhost/osticket/scp/login.php). For now, I will log in as the admin account that I set up and I should see all the tickets that have been created. 
</p>
<br />

<p>
<img src="https://i.imgur.com/z37VSRY.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
This next step is something I really should have done earlier but I initially wanted to demonstrate resolving a ticket using the Jane Doe account that we created instead of logging in as the admin account. Since Jane Doe was not assigned a support role in the previous lab, I went into Admin Panel > Agents > Jane Doe > Access > Extended Access > Support > Supreme Admin. Click Add and save the changes. We can then log out of the admin account and try logging in as Jane Doe. 
</p>
<br />

<p>
<img src="https://i.imgur.com/Be74j6B.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/9FmKMHH.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
We should now be logged into the Jane Doe account and be able to see all the tickets that have been created just as we were able to do so from the admin account. 
</p>
<br />

<p>
<img src="https://i.imgur.com/N76MfN8.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/fc9FNAQ.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lets start off by clicking the first ticket we recived relating to the entire mobile online banking being down. If we click that We should be able to see all the details about the ticket. Everything from the description right down to who it was sent by will be displayed to us. In this case, we can see that it was sent to us by Karen. It is now up to Jane to proceed with hashing out all the details of the ticket. Jane knows that this issue sounds pretty serious as it it can impact business so she uses her discretion to analyze the severity of the problem. She can do this by clicking "normal" next to where it says "Priority" up ontop and changing the status to "Emergency", adding a note and clicking "update" . 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
