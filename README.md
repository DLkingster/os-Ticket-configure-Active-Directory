<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create Azure Tennant (Organization) account.
- Create Resource group.
- Create Storage account.


<h2>Deployment and Configuration Steps</h2>

<p>
<![image](https://github.com/user-attachments/assets/ca64bf2b-2cc1-4810-b5de-29ce0edea300)

</p>
<p>
Sign in to the Azure portal. From the Azure portal menu, select Microsoft Entra ID. Navigate to Identity > Overview > Manage tenants. Select Create.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/ca64bf2b-2cc1-4810-b5de-29ce0edea300"/>
</p>
<p>
Sign in to the Azure portal. Select Resource groups. Select Create.
Enter the following values:
Subscription: Select your Azure subscription.
Resource group: Enter a new resource group name.
Region: Select an Azure location such as Central US.
Select Review + Create. Select Create. It takes a few seconds to create a resource group.To refresh the resource group list, select Refresh from the top menu. To open the newly created resource group, select it from the list. Or, select Notification (the bell icon) from the top, and then select Go to resource group to open the newly created resource group.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/acff2bef-fb19-44ba-ba8b-fe73b238aa90"/>
  
</p>
<p>
To create an Azure storage account with the Azure portal, follow these steps:
From the left portal menu, select Storage accounts to display a list of your storage accounts. If the portal menu isn't visible, select the menu button to toggle it on.
Options for your new storage account are organized into tabs in the Create a storage account page.
Basics tab, provide the essential information for your storage account.
Advanced tab, you can configure additional options and modify default settings for your new storage account.
Networking tab, you can configure network connectivity and routing preference settings for your new storage account. 
Data protection tab, you can configure data protection options for blob data in your new storage account. 
Encryption tab, you can configure options that relate to how your data is encrypted when it is persisted to the cloud. 
Tags tab, you can specify Resource Manager tags to help organize your Azure resources.
When you navigate to the Review + create tab, Azure runs validation on the storage account settings that you have chosen. If validation passes, you can proceed to create the storage account.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/c2ea8203-b02e-4298-a7c3-94728fa08a96)"/>
</p>
<br />
