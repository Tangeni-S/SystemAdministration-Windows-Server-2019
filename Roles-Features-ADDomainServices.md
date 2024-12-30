# Roles and Features - Active Directory Domain Services

## Objective
The objective of this section is to add the Active Directory Domain Services feature on the Windows Server and as well do the initial configuration necessary

## Procedure

Whilst on the Server Dashboard, you would select the Manage option on the top right of the window which would display a drop down menu.  From the menu select **Add Roles and Features**.

https://github.com/user-attachments/assets/2c64a93f-6760-4ee8-8748-8a77c83a6f65

From the above window you can proceed by pressing Next. This will take you to the Server Selection. At this window we will have the option **Select a server from the server pool** selected and below have our created server selected
as shown below.

![1](https://github.com/user-attachments/assets/0d3d016a-902a-43e6-beb1-cfbd11721ca1)

Proceeding to the next window, we now have to select the specific roles we want to add to our Server. In this case , we select only **Active Directory Domain Services**

![2](https://github.com/user-attachments/assets/21652b2c-77b7-4776-a7bc-324fb5c40998)

We proceed next to the selection of features. This we skip for now because there is no additional features we need for now. We proceed next again until we reach confirmation.

![3](https://github.com/user-attachments/assets/a9a23b17-770c-428b-8a21-be592f9ab0c0)

Proceed with starting the installation by pressing install and wait for the install to complete.

![4](https://github.com/user-attachments/assets/4232b570-42ac-4aaa-a340-ccb40780d69b)

Once installation is complete you can close the installation dialog box. 

![5](https://github.com/user-attachments/assets/ce1aef1e-9b32-42c0-818c-3a0a5e640f93)

The next step would be to promote our server to a Domain Controller. This is done by clicking on the Notifications flag in the top right of the window and selecting
**promote this server to a Domain Contrroller** as shown in the video below

https://github.com/user-attachments/assets/6af0c314-a0df-412a-a71d-5b2b0765060a

In the preceeding window, a dialog displays that prompts you to make a selection. We will select **Add a new forest** since we are creating a new domain.
Below you would enter your domain name in the **root domain name** input box as shown and proceed to the next part of the configuration

![a](https://github.com/user-attachments/assets/bec2e570-055d-4801-a460-02a8f0cc4bc3)

In the next part you are required to enter a recovery password for the Domain Controller. Do so accordingly and proceed to the next part

![b](https://github.com/user-attachments/assets/d27384ad-968e-4085-9570-4446f0219747)

You can press next again to skip DNS delegation for now

Verify the NetBIOS name and proceed to the next step

![c](https://github.com/user-attachments/assets/0a28ef48-6ad0-454f-b0fc-651a35aa3785)

You can leave the Paths configured as is and move to the next part which is the review options section. After reviewing your configurations and being satisfied, you can select next to 
proceed to the prequisites check and begin installation process

![d](https://github.com/user-attachments/assets/029fde0f-55d0-4fde-a129-ead93484c777)

Once installation is complete , server will force a restart to complete its configuration

![e](https://github.com/user-attachments/assets/d6684a65-68eb-40dd-82b2-cb6cf1e4b66c)

After the reboot, and logging in , you can confirm that the domain is running from the server dashboard

![f](https://github.com/user-attachments/assets/698988d3-d3f0-411d-92e6-ff99930625f0)

#### NOTE
After promoting DC, return to your network settings to re-set your DNS settings which will have been changed during the process. Very important not to forget changing it moving forwards to the nexts steps

![g](https://github.com/user-attachments/assets/16619f95-0538-4952-967a-0ee2bffc14bb)







