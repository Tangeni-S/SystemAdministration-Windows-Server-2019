# SystemAdministration-Windows-Server-2019
This repository consists of the documentation of setting up a Windows Server 2019 system and its management

## Objective
To demonstrate in a virtual enviroment the various configurations one can expect to administer in a real-world enviroment.

### Requirements
This lab required the following in order to attempt:
  1) Vmware Workstation (This is my preferred Hypervisor of choice, you can as well utilize VirtualBox)
  2) Windows Server 2019 ISO image for the installation( I will skip the installation portion )

### Configurations 
1) **Static IP on LAN facing interface** ==>  **10.10.1.0 /24**
2) **Computer name change**



### Procedure 

1) Assigning the LAN static IP address

With the windows server booted up, proceed to the network settings in order to configure the IP addressing of the server. The below image
shows the network interface available. 

![1_1](https://github.com/user-attachments/assets/dd26419f-86bb-4782-8e5b-0b2886673b61)

The unidentified network once configured will be our internal LAN. Proceed to configure static addressing to this interface

![1_2](https://github.com/user-attachments/assets/1cbab071-554e-4681-a1cb-9f90ea176433)

2) Renaming the Server Computer Name

For easier identification purposes , I would want to rename the device to make it more easily identifiable. It can be do done so as shown below:


https://github.com/user-attachments/assets/942af600-a4dc-4071-9345-6175b537cf42

Once the server has rebooted in order to apply the changes, the name change reflect should reflect and can be observed by going to the local server tab as shown

![1_3](https://github.com/user-attachments/assets/c4388b3a-83a1-4f23-921f-c66f18fd87e5)

Next we look at adding our first role/feature being the Active Directory Domain Services
>>> <a href="https://github.com/Tangeni-S/SystemAdministration-Windows-Server-2019/blob/77e98380b8fd83ec2d53567ed633a988cc06bb37/Roles-Features-ADDomainServices.md">Roles and Features - Active Directory Domain Services</a>





