# SystemAdministration-Windows-Server-2019
This repository consists of the documentation of setting up a Windows Server 2019 system and its management

## Objective
To demonstrate in a virtual enviroment the various configurations one can expect to administer in a real-world enviroment.

### Requirements
This lab required the following in order to attempt:
  1) Vmware Workstation (This is my preferred Hypervisor of choice, you can as well utilize VirtualBox)
  2) Windows Server 2019 ISO image for the installation( I will skip the installation portion )

### Configurations 
1) **Static IP on LAN facing interface** ==>  
2) **Static IP on WAN facing interface ( Will add a firewall later between this connection)** ==> 


### Procedure 

1) Assigning the LAN static IP address

With the windows server booted up, proceed to the network settings in order to configure the IP addressing of the server. The below image
shows 2 network interfaces available. 

![1_1](https://github.com/user-attachments/assets/ff5d891a-8b6d-4b21-9b52-dc17c6d42462)

The unidentified network once configured will be our internal LAN and the Network 2 will be our WAN connection to the internet.
Proceed to open up the properties window *Ethernet0* to configure the IPv4 settings as follows:

![1_2](https://github.com/user-attachments/assets/38853560-7834-48a0-a563-fb8adb67b968)

Close the dialog once done , ensuring the configurations are correct. I proceed to do the same with the 2nd interface for the WAN
as shown below:




