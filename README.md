# Setting up VM in Azure

 Create new resourse group

  - In the search bar, type "Resource Groups" and click on "Create Resource Group".
  - Enter a name for your resource group.
  - Under "Resource Details," choose your desired region.
  - Click "Review + Create." After validation, click "Create" to set up the resource group.
  <img width="797" height="583" alt="image" src="https://github.com/user-attachments/assets/d4f2b967-4896-4d99-9a8d-caf2bb98f39a" /> <br>


---

Create Windows 10 VM
 - In the search bar, type "Virtual Machines."
 - Click "Create," then select "Azure Virtual Machine."
 - Select your Azure Subscription and the Resource Group you just created.
 - Name your Virtual Machine.
 - Choose the same region as your resource group.
 - Select your desired Operating System under "Image."(windows 10 pro)
 - Pick the desired Size for your virtual CPU.(Standard D2s_v3 - 2 vcpus, 8 GiB memory)
 - Create a username and password for the Administrator account.
 - on networking tab create new virutal network

   <img width="731" height="816" alt="image" src="https://github.com/user-attachments/assets/856610ba-85c8-4b6d-8a12-4a1f85b6d5f1" />

 - Check the licensing box. Click "Review + Create." After validation, click "Create." This may take a few minutes.

  <img width="792" height="583" alt="image" src="https://github.com/user-attachments/assets/56c57252-eccb-443e-a85a-f68532f5607e" /><br>

  
---
Create Linux(Ubuntu) VM

- Inn the search bar, type "Virtual Machines."
- Click "Create," then select "Azure Virtual Machine."
- Select your Azure Subscription and the Resource Group you just created.
- Name your Virtual Machine.
- Choose the same region as your resource group.
- Select your desired Operating System under "Image."(Ubuntu Server 24.4)
- Pick the desired Size for your virtual CPU.(Standard D2s_v3 - 2 vcpus, 8 GiB memory)
- Create a username and password for the Administrator account.
- On networking tab click on the same virtual network created for WIndow vm
- Check the licensing box. Click "Review + Create." After validation, click "Create." This may take a few minutes.


<img width="649" height="740" alt="image" src="https://github.com/user-attachments/assets/552c78c1-2f65-40d3-8b4f-441bddf821d4" />
