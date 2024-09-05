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

 Create a couple of tickets as an external user (Customer):

  - Open your browser, and go to http://localhost/osticket/
  -  Click 'Open a New Ticket'
  -  Enter the customers Contact Information -> Email Address\ Full Name\ Help Topics (Choose from the ones created in post-installation or any)
  -  Fill out the 'Ticket Details' -> Issue Summary (create your own) -> Breif sentence in the empty detail box (create your own)
  - Click 'Create Ticket' 
  - Once the ticket is created you'll get an automatic thank you message from the Support Team


Work your Tickets!

- Close out your osTicket browser as an external user and log back in as an Agent (Help Desk Professional) -> http://localhost/osTicket/scp/login.php
  
   *Note: Log in is as Jane Doe or John Doe (Agents created from post-installation)

  ![image](https://github.com/user-attachments/assets/dc767bfb-2774-4006-9b25-0d6af780e931)
  
   *Note: If you do not see any tickets after logging in as an Agent, log back out and log back in with your admin credentials (the credentials created when installing osTicket)
           - Go to the Admin Panel -. Agents -> Select the Agent having trouble viewing tickets -> Go to the Access tab -> Add Extended Access -> Save Changes


Congratulations, your troubleshoot was sucessful! Back to working tickets!

- Log out and log back in with your Jane Doe credentials
- Open a ticket (select either of the ones created)
- Make sure the the priority settings, and the SLA's are set on the tickets
- Assign the ticket to an agent
- Enter a brief note in the empty reponse box
- Post Reply 
    *Note: Only assign a ticket to a different department if it cannot be solved by the default assigned department.
- Go back to 'Open Tickets' to view the ticket you made updates on
- Click on the ticket you recently worked and set the Ticket Status to 'Resolved' indicating something was actually done
    *Note: Enter a brief note in the emppty detail box explaining what was done
     -Post Reply
- To view 'Closed' tickets, simply click 'Closed' and you should see the ticket that was just resolved


Going back to Open Tickets: 

 - Select another ticket
 - Repeat the steps as needed and be sure to set the Priority and SLA appropriately
 - Assign to a different Agent, i.e John Doe
 - Enter a brief note in the empty reponse box
 - Post Reply
 - Click on Open Tickets and view that the ticket is now Assigned to John Doe
     *Note: If you need to delete a ticket, select the box next to the ticket number and click delete on the far righr (mini trash can


 
Work your last ticket:

- Select the ticket
- Repeat the steps as needed and be sure to set the Priority and SLA appropriately
- Assign to an Agent (either Jane or John)
- Enter a brief note in the empty reponse box
- Resolve the ticket if you are already signed in as the Agent assigned for the ticket


Log back in as John and resolve that ticket:
 - Select the ticket that was assigned
 - Look through the history of the ticket
 - Enter a brief note in the empty response box
 - Select the 'Ticket Status' as 'Resolved'
 - Post Reply

   Note: If you were unable to select 'Resolve' under John Doe, log out and log back in with your admin credentials (created when osTicket was installed), go to 'Admin Panel' -> Agents -> Agents -> Select John Doe -> click the Access tab -> Change the 'View Only' access to 'Supreme Admin' -> Save Changes


Congratulations, all tickets have been resolved and/or closed!


