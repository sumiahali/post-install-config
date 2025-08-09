<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11</b> (24H2)

<h2>Post-Install Configuration Objectives</h2>

- Access and understand the Admin and Agent Panels
- Configure Roles, Departments, and Teams for ticket management
- Set ticket creation permissions and requirements
- Add Agents (support staff) and Users (customers)
- Create SLA Plans and Help Topics for ticket categorization

<h2>Configuration Steps</h2>

<h3>1. Access the Login Pages</h3>
- Admin/Analyst Login Page: <a href="http://localhost/osTicket/scp/login.php">http://localhost/osTicket/scp/login.php</a><br>
- End Users osTicket URL: <a href="http://localhost/osTicket">http://localhost/osTicket</a><br><br>
<p>
<img width="1840" height="1646" alt="image" src="https://github.com/user-attachments/assets/efc1879b-c862-4184-a86d-869684a9bc21" />
<img width="1838" height="1642" alt="image" src="https://github.com/user-attachments/assets/d2f8b943-6526-403c-bfb6-556aa26535d0" />
</p>
<br />

<h3>2. Understand the Panels</h3>
- Agent Panel – Used by support staff to manage and respond to tickets<br>
- Admin Panel – Used by administrators to configure system settings<br><br>

<h3>3. Configure Roles (Group Permissions)</h3>
- Go to: Admin Panel → Agents → Roles<br>
- Create a role (example: Supreme Admin – full permissions)<br><br>
<p>
<img width="1916" height="772" alt="image" src="https://github.com/user-attachments/assets/6dd1615f-fe77-4169-94e5-11a974c82887" />
<img width="1918" height="596" alt="image" src="https://github.com/user-attachments/assets/084949a5-2a98-4344-95e0-b99a0b0f37cb" />
<img width="1920" height="1096" alt="image" src="https://github.com/user-attachments/assets/90702c5d-68aa-4fab-b9a8-883eafb08015" />
<img width="1920" height="818" alt="image" src="https://github.com/user-attachments/assets/d8753c95-e811-4e61-a06e-7dac0095250a" />
<img width="1918" height="486" alt="image" src="https://github.com/user-attachments/assets/ca1f35d8-e2bc-4e40-b7e1-505cd4bb32bd" />
<img width="1918" height="622" alt="image" src="https://github.com/user-attachments/assets/fade63b2-5c9b-434b-8883-5c33774efa3d" />
</p>

<h3>4. Configure Departments (Ticket Visibility)</h3>
- Go to: Admin Panel → Agents → Departments<br>
- Create departments (examples: SysAdmins, Help Desk, Networking)<br><br>
<p>
<img width="1916" height="662" alt="image" src="https://github.com/user-attachments/assets/752b860b-61df-4d90-b755-a8de2bbdcbde" />
<img width="1920" height="508" alt="image" src="https://github.com/user-attachments/assets/6ee3910e-4f32-4ee6-adc3-f8e43bb8bdfd" />
<img width="1916" height="518" alt="image" src="https://github.com/user-attachments/assets/bd11f371-5b98-4429-9e4a-94eff9dbe4e4" />
</p>

<h3>5. Configure Teams</h3>
- Go to: Admin Panel → Agents → Teams<br>
- Create a team to group agents from different departments (example: Online Banking)<br><br>
<p>
<img width="1918" height="604" alt="image" src="https://github.com/user-attachments/assets/7ca938bc-8771-4fd0-8780-669c8850e285" />
<img width="1920" height="532" alt="image" src="https://github.com/user-attachments/assets/a6a23801-8e76-43e2-9ea6-b34e2022512c" />
<img width="1914" height="382" alt="image" src="https://github.com/user-attachments/assets/b32d322f-b18f-4380-9ae3-e24cb12aa8d6" />
</p>

<h3>6. Set Ticket Creation Rules</h3>
- Go to: Admin Panel → Settings → User Settings<br>
- Decide ticket creation policy:<br>
  - Uncheck “Require registration and login to create tickets” → allows anyone to create tickets<br>
  - Or check it to require registration<br><br>
<p>
<img width="1918" height="1378" alt="image" src="https://github.com/user-attachments/assets/079c06a8-7866-4ea9-9719-c19a163f869f" />
<img width="1198" height="114" alt="image" src="https://github.com/user-attachments/assets/b4d67a13-bff7-44f8-b0f1-621b38b0131c" />
</p>

<h3>7. Add Agents (Support Staff)</h3>
- Go to: Admin Panel → Agents → Add New<br>
- Example agents: Jane (Dept: SysAdmins), John (Dept: Support)<br><br>
<p>
<img width="1448" height="940" alt="image" src="https://github.com/user-attachments/assets/bc2673e3-3ffe-4542-8949-b6d89e4d1503" />
<img width="1292" height="778" alt="image" src="https://github.com/user-attachments/assets/d443469c-b0b6-4bda-bae4-5b8830638771" />
<img width="1596" height="652" alt="image" src="https://github.com/user-attachments/assets/65d7ebf5-5d3e-4b11-add4-691351ca3152" />
<img width="1202" height="570" alt="image" src="https://github.com/user-attachments/assets/ff28267b-aa40-4a9e-8050-bc6f25c680c1" />
<img width="1918" height="538" alt="image" src="https://github.com/user-attachments/assets/db414ad5-484b-479e-be6b-9fef4e7e5878" />
<img width="1882" height="68" alt="image" src="https://github.com/user-attachments/assets/6a1d5560-21be-4ca2-8fcb-fe4578e515ee" />
<img width="1922" height="438" alt="image" src="https://github.com/user-attachments/assets/9fc53f16-3481-4bef-8854-c44527269753" />
</p>

<h3>8. Add Users (Customers)</h3>
- Go to: Agent Panel → Users → Add New<br>
- Example users: Karen, Ken<br><br>
<p>

</p>

<h3>9. Configure SLA Plans</h3>
- Go to: Admin Panel → Manage → SLA<br>
- Example SLAs:<br>
  - Sev-A: 1 hour grace period, 24/7<br>
  - Sev-B: 4 hour grace period, 24/7<br>
  - Sev-C: 8 hour grace period, Business Hours<br><br>

<h3>10. Configure Help Topics</h3>
- Go to: Admin Panel → Manage → Help Topics<br>
- Example topics: Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, Other<br><br>
