# Installing Active Directory Domain Services (AD DS), Adding Users and Computers on Windows Server 2022

This project demonstrates the installation and configuration of **Active Directory Domain Services (AD DS)**, adding users and computers on **Active Directory Users and Computers (ADUC)** on **Windows Server 2022** to create a new domain environment for IT support lab practice.

---

##  Environment
- **Server OS:** Windows Server 2022  
- **Role Installed:** Active Directory Domain Services  
- **Root Domain Name:** minsithu.com  
 

---

##  Step-by-Step Implementation

### Step 1: Rename the Computer
The server was renamed to follow a standard enterprise naming convention.

- Opened **Server Manager**
- Rename the computer: **SG-DC-01**

<img src="https://imgur.com/r7rhEOq.png" height="50%" width="50%"/>

---

### Step 2: Open Add Roles and Features Wizard

- Selected **Add Roles and Features**


<img src="https://imgur.com/vfsqupy.png" height="50%" width="50%"/>

---

### Step 3: Select Active Directory Domain Services
- Selected **Active Directory Domain Services (AD DS)**

<img src="https://imgur.com/FgVkukP.png" height="50%" width="50%"/>



---

### Step 4: Add Required Features
- Clicked **Add Features** 


<img src="https://imgur.com/Qu8tUM0.png" height="50%" width="50%"/>

---

### Step 5: Install the AD DS Role
- Reviewed installation selections
- Clicked **Install**
- Waited for installation to complete

<img src="https://imgur.com/hTPpm0g.png" height="50%" width="50%"/>

---

### Step 6: Deployment Configuration
- Selected **Add a new forest**
- Entered root domain name: **minsithu.com**

<img src="https://imgur.com/nyfbEAo.png" height="50%" width="50%"/>

---

### Step 7: Set Directory Services Restore Mode (DSRM) Password
- Configured the DSRM password for recovery purposes

<img src="https://imgur.com/rdewMyE.png" height="50%" width="50%"/>

---

### Step 8: Configure NETBIOS Domain Name
- NETBIOS domain name: **MINSITHU**

<img src="https://imgur.com/4LmjBNF.png" height="50%" width="50%"/>

---

### Step 9: Install Active Directory Domain Services
- Verified configuration summary
- Proceeded with AD DS installation
- Server rebooted automatically after installation

<img src="https://imgur.com/9voDjxL.png" height="50%" width="50%"/>

---

### Step 10: Installation Complete

- Confirmed the domain name: **minsithu.com**


<img src="https://imgur.com/v82pSFj.png" height="50%" width="50%"/>

---

#  Adding User and Computer in Active Directory Users and Computers (ADUC)

This section demonstrates how a new domain user and a domain-joined computer were created in **Active Directory Users and Computers (ADUC)**.

---

##  Step-by-Step Implementation

### Step 1: Create a New Domain User
- Opened **Active Directory Users and Computers**
- Right-clicked on **Users**  
- Selected **New → User**

<img src="https://imgur.com/b55yXu2.png" height="50%" width="50%"/>

---

### Step 2: Enter User Details
- Entered first name, last name, and user logon name

User details:
- **Full Name:** Kaung Myat  
- **User logon name:** Kaung 

<img src="https://imgur.com/9CRAYoG.png" height="50%" width="50%"/>

---

### Step 3: Create the User Account

- User account successfully created

<img src="https://imgur.com/MHkLMs9.png" height="50%" width="50%"/>

---

### Step 4: Verify User in Active Directory
- Confirmed the new user **Kaung Myat** appears in the Users container

<img src="https://imgur.com/Y2QOvbb.png" height="50%" width="50%"/>

---

### Step 5: Join a Computer to the Domain
- Joined a Windows client computer to the **minsithu.com** domain


<img src="https://imgur.com/q1rZ1bX.png" height="50%" width="50%"/>

---

### Step 6: Enter Domain Credentials
- Entered the domain administrator username and password to authorize domain join

<img src="https://imgur.com/KuCWLWA.png" height="50%" width="50%"/>

---

### Step 7: Confirm Successful Domain Join
- Received confirmation message indicating the computer was successfully joined to the domain

<img src="https://imgur.com/C62qorS.png" height="50%" width="50%"/>

---

### Step 8: Verify Computer in Active Directory
- Opened **Active Directory Users and Computers**
- Verified the domain-joined computer appears in the domain

Computer details:
- **Computer Name:** Desktop-1  


<img src="https://imgur.com/oZ0K6zE.png" height="50%" width="50%"/>

---



##  Result
- Active Directory Domain Services installed successfully
- New domain created: **minsithu.com**
- Domain user **Kaung Myat** created successfully
- Client computer **Desktop-1** joined to the domain and visible in ADUC



  
