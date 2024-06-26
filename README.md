# C2-Attack-Defend
Welcome to my GitHub project! 

##### This is the free course from Blue Cape Security's 'C2 Attack & Defend DIY Course.' 
https://bluecapesecurity.com/courses/c2-attack-and-defend/

## Objective
I am practicing a realistic cyber attack scenario, utilising the Empire Command and Control (C2) framework to carry out an attack on a Windows target VM. This project reflects a true 'purple team' approach, where I learn from both the perspective of a red team operator and a blue team investigator.

### Skills Learned


### Tools Used
- Splunk
- Velociraptor

## Steps
- Downloaded and Installed Oracle VirtualBox 7.0
- Downloaded and Installed a Windows 10 VM
- Downloaded and Installed a Windows Server 2019 VM
- Installed Active Directory Services on Windows Server 2019
   - Active directory services has been installed on the windows Server 2019 and promoted this server to Domain controller. Created the domain name for the lab, appended by the toplevel domain label.local.

![image](https://github.com/shimsha24/C2-Attack-Defend/assets/151268669/4216383c-7159-490c-8d34-26b09c12286f)

- Created domain users 
  - Intially, there will be one admin account called Administrator. Added additional users for this domain.
  - To test the system, check the box for 'Password never expires'.
  - Assigned the user to domain administrators.

![image](https://github.com/shimsha24/C2-Attack-Defend/assets/151268669/f87d5616-80cb-40bc-908b-27cbeb96690b)

![image](https://github.com/shimsha24/C2-Attack-Defend/assets/151268669/5237e0f1-5dc3-4057-801a-1713522c97b8)


- Added the Windows 10 workstation to the domain.
  
  ###### Fixing duplicate IP address issue with Virtual Box
  
