<p align="center">
<img src="https://github.com/user-attachments/assets/7c11239a-f225-4a93-b4ac-7ba93e7c4f40" width="650" alt="Microsoft Active Directory Logo"/>
</p>



<h1>Adding a computer to the Domain</h1>
This project outlines adding computer(s) to the Domain Controller.<br />


<h2>Environments and Technologies Used</h2>

- VMware Workstation Pro (Virtual Machines/Compute)
- Active Directory Domain Services


<br>


<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 Pro


<br>


<h2>High-Level Deployment and Configuration Steps</h2>

- Go to: System Properties > Computer Name > Rename this PC (advanced)
- Select Domain, enter domain name
- Provide domain admin credentials when prompted
- Restart the computer


<br>


<h2>Deployment and Configuration Steps</h2>

## Adding the computer to the Domain
### Right-click on the Windows Start Menu, then choose System
<p>
<img src="https://github.com/user-attachments/assets/64eb9f22-6d74-450a-998b-516b4d4d6cb8" width="550" alt="Disk Sanitization Steps"/>
</p>

### Choose Rename this PC (advanced)
<p>
<img src="https://github.com/user-attachments/assets/b8beb547-dce7-4f54-8467-9503e16acc25" width="550" alt="Disk Sanitization Steps"/>
</p>

### Under the computer name tab, click on Change
<p>
<img src="https://github.com/user-attachments/assets/fd2ce8d7-51ce-49c0-8791-8a38b24d1e9e" width="550" alt="Disk Sanitization Steps"/>
</p>

### Once you are redirected to the Computer Name/Domain Changes screen, choose the Domain option, then enter in the Domain Name
<p>
<img src="https://github.com/user-attachments/assets/b9779ab1-2fd3-41c8-8ea8-dfa812c76b3b" width="550" alt="Disk Sanitization Steps"/>
</p>

### Provide the domain admin credentials
<p>
<img src="https://github.com/user-attachments/assets/05155499-0521-4536-b20f-efa3ca78f1ad" width="550" alt="Disk Sanitization Steps"/>
</p>

### The following message will appear after the admin credentials has been provided, click Ok
<p>
<img src="https://github.com/user-attachments/assets/982eb785-63de-4844-8e21-285fc2e244a7" width="550" alt="Disk Sanitization Steps"/>
</p>

### Click Ok
<p>
<img src="https://github.com/user-attachments/assets/bd3dca78-b7c3-4a02-92e4-c7e6d8eef44c" width="550" alt="Disk Sanitization Steps"/>
</p>

### Close the Computer Name/Domain Changes screen, then click Restart Now
<p>
<img src="https://github.com/user-attachments/assets/ed81b14f-1164-412f-90c4-2cae674516a7" width="550" alt="Disk Sanitization Steps"/>
</p>

<br>

## Verifying the changes
### When logging into the client machine, scroll down to view the instructions on how to log into the domain
<p>
<img src="https://github.com/user-attachments/assets/885e130b-14c1-4b5c-b251-4fdaff620013" width="550" alt="Disk Sanitization Steps"/>
</p>

### Log into the Server and verify that the following computer has been added
<p>
<img src="https://github.com/user-attachments/assets/a4a16977-059e-4c69-89ca-9cd9815aa8e3" width="550" alt="Disk Sanitization Steps"/>
</p>

### Open up File Explorer, right-click on This PC, then go to Properties
<p>
<img src="https://github.com/user-attachments/assets/44d1b1ea-71f0-4f5f-ab55-71aeedf60bdf" width="550" alt="Disk Sanitization Steps"/>
</p>

### The device name will match the name of the machine within Active Directory Users and Computers - Computers OU
<p>
<img src="https://github.com/user-attachments/assets/36a6a763-07a8-4af3-98dd-9719158b8ff4" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/f7fabd37-2b0a-4985-89b3-39ffbdb8f28b" width="550" alt="Disk Sanitization Steps"/>
</p>

### Within the client machine, request traffic from the domain by pinging the domain name, and the domain's IP address
<p>
<img src="https://github.com/user-attachments/assets/e2492b6f-580a-4076-aa66-6d7d79bc2759" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/9bb581c2-6d0b-4cb4-b934-b24db022e84c" width="550" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/ec076b2c-09b1-47d1-aede-6a8024f423c6" width="550" alt="Disk Sanitization Steps"/>
</p>

---

<br />


# End of Project
