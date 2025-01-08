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

## Stage 1 - Intake
1. A ticket is created by user **Karen** in the **End User Portal** at:  
   [http://localhost/osTicket](http://localhost/osTicket)  
   ![End User Portal](https://i.imgur.com/Y3STDyU.png)

2. To open a ticket, Karen fills out her contact information and selects the **Help Topic**.  
   ![Filling Contact Information](https://i.imgur.com/1rWNuDa.png)

3. Karen provides the details of her issue and clicks **Create Ticket**.  
   ![Ticket Details](https://i.imgur.com/LZPaBQE.png)

## Stage 2 - Assignment and Communication
1. Agent **John** views the ticket at:  
   [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)  
   ![Admin Login](https://i.imgur.com/zTuYJ9e.png)

2. John notes the issue's severity:  
   ![Ticket Review](https://i.imgur.com/ZfZncjm.png)

3. John assigns the SLA, department, and help topic, then escalates to **Jane** and informs Karen:  
   ![SLA Assignment](https://i.imgur.com/aykdgCZ.png)  
   ![Department Setting](https://i.imgur.com/gwdcTbS.png)  
   ![User Communication](https://i.imgur.com/yAN8XY1.png)

## Stages 3 and 4 - Working and Resolving the Issue
1. Agent **Jane** reviews the ticket:  
   [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)  
   ![Admin Login - Jane](https://i.imgur.com/ky5pRNt.png)

2. Jane resolves the operating system issue and updates the app. She communicates the fix to Karen and marks the ticket as resolved:  
   ![Resolution Status](https://i.imgur.com/3Kycogt.png)

