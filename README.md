# Creating Resources Groups, Storage Account, and Containers
<p align="center">
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h1>Creating Resources Groups, Storage Account, and Containers in Azure</h1>
In this tutorial, we create a Resource Group in Azure then we will put a Storage Account in the RG. We will then create a container to upload a txt.file into while observing we can edit the txt.file. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Resoruce Groups / Storage Accounts / Containers)
- Remote Desktop 


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Create Resource Group
- Create Storage Account
- Create Container in Storage Account
- Upload txt.file in Container then edit it

<h2>Actions and Observations</h2>

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/1ffe1a94-47c8-4bb9-a522-93659d31eeb6"/>
</p>
<p>
First we need to type Resource Groups in the Azure search bar then click the create resource group tab.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/31e93328-833c-44df-b489-2e3a80465e17"/>
</p>
<p>
Once we are in the Resource Group make sure its under your subscription, the Resource Group name can be named RG-01, and your region US West US 3.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/88d85616-c992-49e6-a359-fa1b661365ac"/>
</p>
<p>
Next click on the Tags section of the Resource Group. Here we can create the names of people we want in the RG. 
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/39ec8d25-58ed-470e-b4f6-1e87851eaee6"/>
</p>
<p>
Then go to the Review and Create tab and click the create button at the bottom left.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/35103d44-1443-4c71-ae49-892e494b109b"/>
</p>
<p>
Click the search bar and type Storage Accounts then click on the icon.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/5ba2d37c-2a99-4beb-a223-a04a50698b33"/>
</p>
<p>
Next click the create Storage Account tab.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/6f8041e8-c82e-4825-8e70-8a6b0a872a5a"/>
</p>
<p>
In the Basics selection make sure the subsciption is the same as the Resource Group. In the Resource Group section click the one we made earlier (RG-01). The storage account name needs to be very unique and catn be already out in the network. Then for the region click US West US 3.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/d65e7a36-11e2-4606-b2cc-92a02a2e4fe1"/>
</p>
<p>
Go to the Review section of Storage Account. Then click the create tab at the bottom left.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/1f471bf9-aebe-4490-a08b-103b17c7a5af"/>
</p>
<p>
Once the Storage Account is created you will see Your Deployment Is Complete with a green check to the left.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/327c5901-2ece-4a75-b2f9-60779eae8115"/>
</p>
<p>
Now once we go back to Storage Accounts we can see the one we created will be on the list. Click the Storage Account you created.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/51eef2ce-3f91-4c84-b0cd-0b1fd60a0cb5"/>
</p>
<p>
From here click on containers under the Data Storage section.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/33c01319-c885-44a6-a4e9-c76dd415a7cc"/>
</p>
<p>
Click the + Container. Then in the right section a tab will open for you to name your container. Once you are done you can create the container by clicking the create tab on the bottom right. 
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/9418f0d7-6c15-4e59-aa49-e510219a8b29"/>
</p>
<p>
Next you can click the created container we made and upload a file by clicking the upload tab on the top left. Then a tab on the right side of your screen will appear and you may browse for your file to upload into Azure. (PLEASE NOTE) [For this example I created a txt.file in notepad from windows then you may upload the file in this section] 
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/0fbd6bb4-e98f-40a7-aa46-00c4d8635479"/>
</p>
<p>
Once the txt file is uploaded, refresh the page for you to see the file. Then click the file you uploaded.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/9f6c33d8-5460-4e4c-8914-de40858bf1cb"/>
</p>
<p>
Click the edit tab of the .txt file.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/7b818c0e-856b-4403-bc03-022d5216bafc"/>
</p>
<p>
You can edit the file by clicking enter on your keyboard to go to the next section. Then you can type anything you want then click the save button on the top left of the file.
</p>
<br />

<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/f9db87e1-75f3-49be-8536-4ef955ea348b"/>
</p>
<p>
Next we can delete the Resource Group by typing resource group in the search bar. Next click on the Resource Group you made, then click delete resource group and a tab will appear on the right side. Type the name of the resource group in the bottom section on the right side and click the delete tab.
</p>
<br />


<p>
<img src="https://github.com/Jacobsushi54/CreatingResourcesGroupsStorageAccountContainers/assets/142194385/c6c3773d-8c0b-4fb8-be2a-d953367b62e5"/>
</p>
<p>
The Resource will be delete as shown in the image above.
</p>
<br />
