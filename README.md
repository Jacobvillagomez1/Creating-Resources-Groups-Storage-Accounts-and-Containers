# Creating Resources Groups, Storage Account, and Containers
<p align="center">
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/76848602-0ddb-4e2d-8ad3-cc987b43c172"/>
</p>

<h1>Creating Resources Groups, Storage Account, and Containers in Azure</h1>
In this tutorial, we create a Resource Group in Azure then we will put a Storage Account in the RG. We will then create a container to upload a txt.file into while observing we can edit the txt.file. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Lab 1 : Creating Resources Groups Storage Accounts and Containers](https://youtu.be/CRi-_34rD-Y)

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
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/7d4b9bf6-474d-41e8-b189-c3e6d017f5f2"/>
</p>
<p>
First we need to type Resource Groups in the Azure search bar then click the create resource group tab.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/45b556ff-eb52-43aa-a484-b3dc796f29a8"/>
</p>
<p>
Once we are in the Resource Group make sure its under your subscription, the Resource Group name can be named RG-01, and your region US West US 3.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/352f0dbe-1a39-40bb-9264-4bd99432aa86"/>
</p>
<p>
Next click on the Tags section of the Resource Group. Here we can create the names of people we want in the RG. 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/4d4a9eda-e189-4c8a-81d9-b3dded1ced44"/>
</p>
<p>
Then go to the Review and Create tab and click the create button at the bottom left.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/5ff5bb34-8167-4c6b-85aa-11aaa589882e"/>
</p>
<p>
Click the search bar and type Storage Accounts then click on the icon.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/80f877fc-308b-48ae-a200-c845e4c346a9"/>
</p>
<p>
Next click the create Storage Account tab.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/524d9fd4-5c08-4709-8ede-4010d911ffbc"/>
</p>
<p>
In the Basics selection make sure the subsciption is the same as the Resource Group. In the Resource Group section click the one we made earlier (RG-01). The storage account name needs to be very unique and catn be already out in the network. Then for the region click US West US 3.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/6ebd205e-8395-45c7-8b5f-a682dcfff312"/>
</p>
<p>
Go to the Review section of Storage Account. Then click the create tab at the bottom left.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/3f56d4aa-ab13-48aa-b9d8-7a1e061b808f"/>
</p>
<p>
Once the Storage Account is created you will see Your Deployment Is Complete with a green check to the left.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/4f631413-64be-4ad8-8cb1-0f7778c19bfb"/>
</p>
<p>
Now once we go back to Storage Accounts we can see the one we created will be on the list. Click the Storage Account you created.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/9e388bf4-46f4-416c-b0e0-83be04670c08"/>
</p>
<p>
From here click on containers under the Data Storage section.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/b17e88e9-e5cc-467a-992c-af691f38c649"/>
</p>
<p>
Click the + Container. Then in the right section a tab will open for you to name your container. Once you are done you can create the container by clicking the create tab on the bottom right. 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/7a2428c8-8b5c-4f85-be50-de3c25094259"/>
</p>
<p>
Next you can click the created container we made and upload a file by clicking the upload tab on the top left. Then a tab on the right side of your screen will appear and you may browse for your file to upload into Azure. (PLEASE NOTE) [For this example I created a txt.file in notepad from windows then you may upload the file in this section] 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/291f4601-4e5c-4658-8fec-1dcfa10da14e"/>
</p>
<p>
Once the txt file is uploaded, refresh the page for you to see the file. Then click the file you uploaded.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/91f7d0e3-89a4-46ac-8908-e9a87156f82f"/>
</p>
<p>
Click the edit tab of the .txt file.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/655bb25d-0cd5-4916-9524-718a0ece1554"/>
</p>
<p>
You can edit the file by clicking enter on your keyboard to go to the next section. Then you can type anything you want then click the save button on the top left of the file.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/5a35c182-0403-4c12-abf5-2ba32a8ee9ab"/>
</p>
<p>
Next we can delete the Resource Group by typing resource group in the search bar. Next click on the Resource Group you made, then click delete resource group and a tab will appear on the right side. Type the name of the resource group in the bottom section on the right side and click the delete tab.
</p>
<br />


<p>
<img src="https://github.com/Jacobvillagomez1/Creating-Resources-Groups-Storage-Accounts-and-Containers/assets/143027686/842b7c28-d10d-4400-b3ef-abccb9e2082f"/>
</p>
<p>
The Resource will be delete as shown in the image above.
</p>
<br />
