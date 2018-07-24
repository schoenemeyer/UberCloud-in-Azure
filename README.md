# UberCloud-in-Azure <img src="https://github.com/schoenemeyer/UberCloud-in-Azure/blob/master/Ubercloud.jpg" width="252">
Guide how to get an UberCloud account and to run HPC in Azure with UberCloud

You will need an Azure account (subscription) for using Microsoft Azure. For this project you can use an existing account or you can also register for a free trial account on Azure, which is valid for 30 days. 

Once you have the subscription, login to the Azure portal azure.microsoft.com 

## Step 1 (Azure Portal)

The  UberCloud Service can be purchased through the Azure Marketplace. In Search the Marketplace enter the keyword Ubercloud
Click on the type of service you would like to select, for example STAR-CCM+ v12 as an example.

 <img src="https://github.com/schoenemeyer/UberCloud-in-Azure/blob/master/ubercloudserv.JPG" width="225">

Also Support for Power on Demand (PoD) licensing is provided.

## Step 2 (Azure Portal)

Create and configure VM where you want to run the UberCloud Service

## Step 3 (Access UberCloud Service)

To access the UberCloud service, find the “Public IP Address” of the VM on the “Running Virtual Machine” page. Copy this IP Address in full and paste the IP Address into your browser in a new tab and go to this IP Address. You will land on the management page for the UberCloud service. Enter your email address and click on the “Submit” button to receive instructions on how to access the UberCloud service through your browser.
Check your email inbox for instructions on how to use the UberCloud service. Keep this email for future reference and do not share it with others for the privacy of your data. Look for the password and copy it. Right below the password is the “Login” button, which will enable you to connect to the UberCloud service running in your new VM.
With the click on the Login button you will land on the login page of the remote desktop connection to the UberCloud service. Look for the password box and paste the password you’ve received with the instructions email. You will see the desktop of the UberCloud service using a remote desktop connection through your browser.

## Step 4 (Getting familiar with UberCloud Service)

UberCloud services contain an “Examples” desktop shortcut. Tutorials provide a great opportunity to discover how the UberCloud service works. Double click on the “Examples” shortcut to access sample data files and instructions on how to run them.

## Step 5 (Shutdown or delete)

If your simulation is finished, you can shutdown the VM. A stopped VM’s preserve the files which have been saved and incur storage charges, however, you will not be charged for compute usage. Before deleting the VM make sure you copy all your data files. Please remember that this step cannot be reversed and all the data you have in the VM and the UberCloud service will be deleted.

## Questions
please write to 
thomas.schoenemeyer@microsoft.com

More news
https://community.theubercloud.com/microsoft-azure-ubercloud-exchange-marketplace-products-start-trainings/


<img src="https://github.com/schoenemeyer/UberCloud-in-Azure/blob/master/OpenFOAM-on-Azure.png" width="225">

