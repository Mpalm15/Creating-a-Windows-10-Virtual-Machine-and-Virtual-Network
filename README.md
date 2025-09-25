<h2>Creating-a-Windows-10-Virtual-Machine-and-Virtual-Network<h2>
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Azure - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of an Azure virtual machine and virtual network.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

1) Create an Azure subscription: https://azure.microsoft.com/en-us/free/
2) Log into the Azure Portal: https://portal.azure.com
3) Verify you have proper role assignments (Owner or Contributor).
4) Confirm billing is active on your subscription.
5) Use a supported web browser (Edge, Chrome, or Firefox).
6) Decide on resource names (VM, Resource Group, Virtual Network).
7) Choose your Azure region.
8) Prepare a username and password for the VM.
9) Ensure you have an eligible Windows 10/11 license with hosting rights.
10) Decide whether to use an existing Virtual Network or create a new one.

<h2>Installation Steps</h2>

<p>

<h2>Log into the Azure Portal</h2>
Step 1: Go to https://portal.azure.com and sign in with your Azure credentials.

<img width="1100" height="213" alt="sc1" src="https://github.com/user-attachments/assets/020eda54-a535-4830-b69a-82ace6935679" />

</p>
<p>
Step 2: Navigate to Virtual Machines.
  
From the Azure services section on the home page, click Virtual machines.
</p>
<br />

<p> <img width="1890" height="297" alt="Sc2" src="https://github.com/user-attachments/assets/88e3eb1e-3fb8-48ae-863a-99dfeb6fcdc4" </p>
<p>
Step 3: Create a New Virtual Machine.
  
On the Virtual Machines page, click Create at the top  
</p>
<br />

<p>
<img width="772" height="855" alt="Sc3" src="https://github.com/user-attachments/assets/5885f7fb-8b55-49dd-a174-22220eedeed5" />
  </p>
  <p>
Step 4: Configure Basics.
    
Select your subscription and resource group.
Enter a name for your virtual machine (e.g., windows-vm-demo).
Choose your region (e.g., East US). 
  </p>
<br />
<p>
<img width="773" height="476" alt="Sc5" src="https://github.com/user-attachments/assets/15a7ff0f-ee04-41ab-a4fe-6655321fd33f" />
 </p>
  <p>
 Step 5: Choose Image, Size, and Credentials.

Under Image, select Windows 10 Pro.
Choose a VM size with at least 2 vCPUs for performance.
Enter a username and password for the administrator account.
  </p>
<br />
<p>
<img width="773" height="641" alt="Sc5" src="https://github.com/user-attachments/assets/e7df2b77-4987-4785-95ce-ae58e2f75a3f" />
  </p>
  <p>
Step 6: Licensing.

Scroll to the bottom of the page. Under Licensing, check the box:
“I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights.”
Click Next: Disks.   
  </p>
  <br />
  <p>
<img width="839" height="874" alt="Sc7" src="https://github.com/user-attachments/assets/e14e0ee2-847b-4bab-a41d-cd09806750ea" />
 </p>
  
