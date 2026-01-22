# Windows-Server-2022-Active-Directory-Lab
This lab demonstrates how to set up Active Directory (AD) on a Windows Server 2022 virtual machine using VirtualBox. The project covers installation, configuration, and AD setup, including Organizational Units (OUs), groups, users, and role assignments


🖥️ Active Directory Home Lab with VMware

📌 Project Overview

This lab demonstrates how to set up Active Directory (AD) on a Windows Server virtual machine using VirtualBox or VMware Workstation Pro.
The project covers installation, configuration, and AD setup, including Organizational Units (OUs), groups, users, and role assignments

🎯 Objectives

Install Windows Server in VirtualBox or VMware Workstation Pro



Set up and configure Active Directory Domain Services (AD DS)



Use Server Manager to install and assign roles/features
Create Organizational Units (OUs) to represent departments/regions
Add groups within OUs
Create and manage user accounts in AD
🛠️ Tech Stack
VMware Workstation
Windows Server (ISO image)
Active Directory Domain Services (AD DS)


📂 Lab Steps


VirtualBox/VMware Setup
Installed VM program of choice (VirtualBox/VMware) 

<img width="1389" height="984" alt="Screenshot 2026-01-20 115027" src="https://github.com/user-attachments/assets/6ccaacc8-6563-43fc-b072-fba091f38995" />


Created a new virtual machine (VM) Once VM is created, Upload the Windows Server 2022 ISO Image (right click on window server => Setting) 

<img width="1581" height="1361" alt="Screenshot 2026-01-22 130334" src="https://github.com/user-attachments/assets/1944558c-e306-48e9-9333-d7ad9dab2736" />



Installed Windows Server on the VM (select “Standard evaluation Desktop Experience”)

<img width="1300" height="1018" alt="Screenshot 2026-01-22 111415" src="https://github.com/user-attachments/assets/658f7f0c-1f08-47bf-8f43-b0e931fa2169" />
<img width="2099" height="1308" alt="Screenshot 2026-01-22 052414" src="https://github.com/user-attachments/assets/b9460d69-83c5-4b62-b7a8-0488d230d1d1" />


Select Custom Install

<img width="1329" height="1017" alt="Screenshot 2026-01-22 111535" src="https://github.com/user-attachments/assets/49729d72-b191-434c-b7c0-a9fd739866e0" />




In the Server Manager Dashboard, Select ----> Add roles and features.

   <img width="1302" height="1029" alt="Screenshot 2026-01-22 113057" src="https://github.com/user-attachments/assets/d7585434-1a3d-4667-a450-21ef4e1be15d" />


<img width="1346" height="1046" alt="Screenshot 2026-01-22 113147" src="https://github.com/user-attachments/assets/b3ddeff8-2749-4ba3-91f7-d02ac3b96c75" />


Active Directory (AD) Installation


<img width="1309" height="1109" alt="Screenshot 2026-01-22 113217" src="https://github.com/user-attachments/assets/42793a1e-ffea-4984-ab8b-029612640381" />

<img width="1279" height="1000" alt="Screenshot 2026-01-22 113314" src="https://github.com/user-attachments/assets/6de31471-0660-4a77-8709-14c2d2011cf2" />



Installed Active Directory Domain Services (AD DS) 

<img width="1241" height="1122" alt="Screenshot 2026-01-22 115252" src="https://github.com/user-attachments/assets/dc287529-b759-4b33-b008-2d02f6b12757" />

We have installed the Active directory role but now we need to promote it to a domain controller so click to add new forest and seta  root domain name. 


<img width="1261" height="1180" alt="Screenshot 2026-01-22 120652" src="https://github.com/user-attachments/assets/b53930a3-078b-4245-bb5a-87d18430f6d3" />

Set Password 

<img width="1410" height="1232" alt="Screenshot 2026-01-22 120750" src="https://github.com/user-attachments/assets/53397def-1cd7-4845-afdd-197412570741" />



Next

<img width="1260" height="1204" alt="Screenshot 2026-01-22 120905" src="https://github.com/user-attachments/assets/86293391-90ab-4dcb-ac8a-615324351dcb" />


Install when done restart

<img width="1280" height="1196" alt="Screenshot 2026-01-22 121407" src="https://github.com/user-attachments/assets/284f4e56-0d7b-4a06-8607-ca6f65077572" />


Creating Admin User Account In the start menu select active directory users and computers


<img width="1265" height="1164" alt="Screenshot 2026-01-22 123922" src="https://github.com/user-attachments/assets/54796ad1-fbca-4d74-bdf4-19f17a783041" />




Created Groups within OUs 

<img width="1268" height="1179" alt="Screenshot 2026-01-22 124204" src="https://github.com/user-attachments/assets/0edaa765-96a0-4cfd-a594-9bbe92e48805" />


Added Users and assigned them to groups  

<img width="1251" height="1137" alt="Screenshot 2026-01-22 124320" src="https://github.com/user-attachments/assets/09696045-0e47-4dc0-b5dd-098e0c1fd9f5" />

<img width="1170" height="1277" alt="Screenshot 2026-01-22 124349" src="https://github.com/user-attachments/assets/7d0c6b21-e18f-45b7-ad95-8e724a65b08e" />




📜 Key Learnings
Hands-on experience with VirtualBox
Installing and configuring Windows Server
Using Server Manager to assign roles and features
Setting up Active Directory Domain Services (AD DS)
Managing users, groups, and OUs in AD
Role-based access control and permissions management
Understanding enterprise Identity & Access Management (IAM)
