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

<h2>Ticket Lifecycle Steps</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h3>1. Login as Admin/Analyst</h3>
<p>
Admin/Analyst Login Page: <code>http://localhost/osTicket/scp/login.php</code><br />
End-User Login Page: <code>http://localhost/osTicket</code>
</p><br />

<h3>2. Department Setup</h3>
<p>
- Change the "SysAdmins" department to a Top-Level Department<br />
- DELETE the "Maintenance" department (not archive)
</p>
<p>
<img src="https://i.imgur.com/uOSP1rv.png"/>
</p><br />

<h3>3. Create Ticket as End-User: Mobile Banking Down</h3>
<p>
- Login as end-user (Ken/Karen)<br />
- Submit a ticket: <strong>"Entire mobile/online banking system is down"</strong>
</p>
<p>
<img src="https://i.imgur.com/6Ba2OrH.png"/>
</p><br />

<h3>4. Respond as Agent (John)</h3>
<p>
- Observe ticket properties: Priority, Department, SLA, Assigned To<br />
- Set to: <strong>Sev-A (1 hour, 24/7)</strong>, Department: <strong>Online Banking</strong>
</p>
<p>
<img src="https://i.imgur.com/dcg0xVz.png"/>
</p>
<p>
<img src="https://i.imgur.com/T00XR0N.png"/>
</p>
<p>
<img src="https://i.imgur.com/fgyiNkO.png"/>
</p>
<p>
<img src="https://i.imgur.com/KGqjcPD.png"/>
</p>
<p>
<img src="https://i.imgur.com/KGqjcPD.png"/>
</p>
<p>
<img src="https://i.imgur.com/r51QSLY.png"/> 
</p>
<br />

<h3>5. Solve Ticket as Jane</h3>
<p>
- Login as Jane<br />
- Complete the mobile banking ticket resolution
</p>
<p>
<img src="https://i.imgur.com/bJP4UDM.png"/>
</p>
<p>
<img src="https://i.imgur.com/NoyKKu7.png"/>
</p>
<p>
<img src="https://i.imgur.com/sWmVhSk.png"/> 
</p>
<p>
<img src="https://i.imgur.com/WWwBmTD.png"/>  
</p>
<br />

<h3>6. Create Ticket as End-User: Adobe Reader Broken</h3>
<p>
- Ticket: <strong>"Accounting department needs Adobe upgrade, broken"</strong>
</p>
<p>
<img src="https://i.imgur.com/F5rt896.png"/>
</p>
<br />

<h3>7. Respond and Complete as John</h3>
<p>
- Set properties: <strong>Sev-B (4 hours, 24/7)</strong>, Department: <strong>Support</strong><br />
- Work to completion
</p>
<p>
<img src="https://i.imgur.com/aLBtusB.png"/>
</p>
<p>
<img src="https://i.imgur.com/9t4Worx.png"/>
</p>
<p>
<img src="https://i.imgur.com/BefUDKi.png"/>
</p>
<p>
<img src="https://i.imgur.com/xkYtNCK.png"/>
</p>
<p>
<img src="https://i.imgur.com/CQwkpom.png"/>
</p>
<br />

<h3>10. Create Ticket as End-User: CFO Laptop</h3>
<p>
- Ticket: <strong>"CFO’s laptop will no longer turn on"</strong>
</p>
<p>
<img src="https://i.imgur.com/pNWejzb.png"/>
</p>
<br />

<h3>9. Respond and Complete as John</h3>
<p>
- Set properties: <strong>Sev-B</strong>, Department: <strong>Support</strong><br />
- Resolve the ticket
</p>
<p>
<img src="https://i.imgur.com/FrE2LVb.png"/>
</p>
<p>
<img src="https://i.imgur.com/Kv0wQb3.png"/>
</p>
<p>
<img src="https://i.imgur.com/kyGkzho.png"/>
</p>
<p>
<img src="https://i.imgur.com/RkJFmIK.png"/>
</p>
<br />

<h3>10. Ticket Communications</h3>
<p>
Most ticketing systems (including osTicket) have email integration.<br />
When an agent updates a ticket, the end user is notified and can respond.
</p>
<br />

<h3>11. Real-World Ticket Intake</h3>
<p>
Tickets can originate from phone calls, emails, chat apps, web forms—or just someone asking for help in person.<br />
Even if you fix something quickly, it's best practice to create a ticket for everything. Metrics matter.
</p>
<br />
