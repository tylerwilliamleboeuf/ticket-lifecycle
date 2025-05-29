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
<img src="https://i.imgur.com/NXAiNZW.png" width="80%" alt="Department Management"/>
</p><br />

<h3>3. Create Ticket as End-User: Mobile Banking Down</h3>
<p>
- Login as end-user (Ken/Karen)<br />
- Submit a ticket: <strong>"Entire mobile/online banking system is down"</strong>
</p>
<p>
<img src="https://i.imgur.com/5KPVjwi.png" width="80%" alt="Create Ticket Mobile Banking Down"/>
</p><br />

<h3>4. Respond as Agent (John)</h3>
<p>
- Observe ticket properties: Priority, Department, SLA, Assigned To<br />
- Set to: <strong>Sev-A (1 hour, 24/7)</strong>, Department: <strong>Online Banking</strong>
</p>
<p>
<img src="https://i.imgur.com/YrlDoJt.png" width="80%" alt="Agent View of Ticket"/>
</p><br />

<h3>5. Re-observe Ticket as John</h3>
<p>
- Attempt to access the escalated ticket as John<br />
- Ticket should now be inaccessible
</p>
<p>
<img src="https://i.imgur.com/z9V4XfA.png" width="80%" alt="Inaccessible Ticket"/>
</p><br />

<h3>6. Solve Ticket as Jane</h3>
<p>
- Login as Jane<br />
- Complete the mobile banking ticket resolution
</p>
<p>
<img src="https://i.imgur.com/I1nBfKh.png" width="80%" alt="Resolve Ticket as Jane"/>
</p><br />

<h3>7. Create Ticket as End-User: Adobe Upgrade</h3>
<p>
- Ticket: <strong>"Accounting department needs Adobe upgrade, broken"</strong>
</p>
<p>
<img src="https://i.imgur.com/HqzQ4Jm.png" width="80%" alt="Adobe Upgrade Ticket"/>
</p><br />

<h3>8. Respond and Complete as John</h3>
<p>
- Set properties: <strong>Sev-B (4 hours, 24/7)</strong>, Department: <strong>Support</strong><br />
- Work to completion
</p>
<p>
<img src="https://i.imgur.com/M3RGezU.png" width="80%" alt="Complete Ticket as John"/>
</p><br />

<h3>9. Create Ticket as End-User: CFO Laptop</h3>
<p>
- Ticket: <strong>"CFO’s laptop will no longer turn on"</strong>
</p>
<p>
<img src="https://i.imgur.com/Wc4r56O.png" width="80%" alt="CFO Laptop Ticket"/>
</p><br />

<h3>10. Respond and Complete as John</h3>
<p>
- Set properties: <strong>Sev-B</strong>, Department: <strong>Support</strong><br />
- Resolve the ticket
</p>
<p>
<img src="https://i.imgur.com/s8OwJkD.png" width="80%" alt="Complete CFO Laptop Ticket"/>
</p><br />

<h3>11. Escalate SysAdmins Ticket</h3>
<p>
- Set all tickets' priority to SEV-A<br />
- Observe that John can no longer access SysAdmins ticket
</p>
<p>
<img src="https://i.imgur.com/LK8Uc8z.png" width="80%" alt="Escalation and Inaccessibility"/>
</p><br />

<h3>12. Assign John Access to SysAdmins</h3>
<p>
- Switch to Admin Panel -> Modify John's team or role to view SysAdmins<br />
- Switch back to Agent Panel and verify view-only access to ticket
</p>
<p>
<img src="https://i.imgur.com/3Mx9vDp.png" width="80%" alt="Assign View Access"/>
</p><br />

<h3>13. Ticket Communications</h3>
<p>
Most ticketing systems (including osTicket) have email integration.<br />
When an agent updates a ticket, the end user is notified and can respond.
</p>
<p>
<img src="https://i.imgur.com/6mTtqQu.png" width="80%" alt="Email Updates"/>
</p><br />

<h3>14. Real-World Ticket Intake</h3>
<p>
Tickets can originate from phone calls, emails, chat apps, web forms—or just someone asking for help in person.<br />
Even if you fix something quickly, it's best practice to create a ticket for everything. Metrics matter.
</p>
<p>
<img src="https://i.imgur.com/kN3oJ0m.png" width="80%" alt="Real-World Ticket Intake"/>
</p><br />

<h3>15. Wrapping Up</h3>
<p>
This lab barely scratches the surface of osTicket’s capabilities.<br />
Explore the email feature. Re-do the lab multiple times until it becomes second nature.<br />
This builds your confidence and supports the <strong>technical skills pillar</strong> that employers value.
</p>
<p>
<img src="https://i.imgur.com/BJRGNcl.png" width="80%" alt="Technical Skills"/>
</p>
