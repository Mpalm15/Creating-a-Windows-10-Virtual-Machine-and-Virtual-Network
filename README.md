<h2>Creating a Windows 10 Virtual Machine and Virtual Network<h2>
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

<img width="1100" height="213" alt="sc1" src="https://github.com/user-attachments/assets/020eda54-a535-4830-b69a-82ace6935679" />

</p>
<hr>
<p>
^Step 1: Go to https://portal.azure.com and sign in with your Azure credentials. 
  
^Step 2: Navigate to Virtual Machines.
  
From the Azure services section on the home page, click Virtual machines.
</p>
<br />

<hr>
<p> <img width="1890" height="297" alt="Sc2" src="https://github.com/user-attachments/assets/88e3eb1e-3fb8-48ae-863a-99dfeb6fcdc4" </p>
<p>
<hr>
^Step 3: Create a New Virtual Machine.
  
On the Virtual Machines page, click Create at the top  
</p>
<br />

<hr>
<p>
<img width="772" height="855" alt="Sc3" src="https://github.com/user-attachments/assets/5885f7fb-8b55-49dd-a174-22220eedeed5" />
  </p>
  <hr>
  <p>
^Step 4: Configure Basics.
    
Select your subscription and resource group.
Enter a name for your virtual machine (e.g., windows-vm-demo).
Choose your region (e.g., East US). 
  </p>
<br />

<hr>
<p>
<img width="781" height="655" alt="Sc4" src="https://github.com/user-attachments/assets/26815b64-b97c-4792-8e4e-5bd350915604" />
 </p>
 <hr>
  <p>
 ^Step 5: Choose Image, Size, and Credentials.

Under Image, select Windows 10 Pro.
Choose a VM size with at least 2 vCPUs for performance.
Enter a username and password for the administrator account.
  </p>
<br />

<hr>
<p>
<img width="773" height="476" alt="Sc5" src="https://github.com/user-attachments/assets/fc201638-ff65-4811-9471-3fb010dea4f6" />
</p>
<hr>
  <p>
^Step 6: Licensing.

Scroll to the bottom of the page. Under Licensing, check the box:
“I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights.”
Click Next: Disks.   
  </p>
  <br />

  <hr>
  <p>
<img width="799" height="826" alt="Sc6" src="https://github.com/user-attachments/assets/c06a9f7b-5e71-45eb-86bb-c4867e0a3a14" />
 </p>
 <hr>
  <p>
^Step 7: Configure Networking.

Leave the Disks section at default. Move to Networking and under Virtual network, click Create new. 
  </p>
<br />

<hr>
<p>
 <img width="839" height="874" alt="Sc7" src="https://github.com/user-attachments/assets/250929f3-cda3-4800-b400-caf90d3727cc" />
</p>
<hr>
<p>
^Step 8: Create Virtual Network.

In the pop-up, rename the network (e.g., project1-vnet).
Leave the rest of the defaults as-is, then click OK. 
</p>
<br />

<hr>
<p>
 <img width="849" height="864" alt="Sc8" src="https://github.com/user-attachments/assets/c6d0d660-067e-4eca-85a4-aca65d15f557" />
</p>
<hr>
<p>
 ^Step 9: Review and Create.

Click Review + create. Double-check your settings, then click Create at the bottom.
</p>
<br />

<hr>
<p>
 <img width="1232" height="544" alt="Sc9" src="https://github.com/user-attachments/assets/0ca765d5-4928-4790-8778-9f56273fd5ef" /> 
</p>
<hr>
<p>
^Step 10: Deployment Complete.

Wait for deployment to finish. When it shows Your deployment is complete, click Go to resource.  
</p>
<br />

<hr>
<p>
<img width="1898" height="467" alt="Sc10" src="https://github.com/user-attachments/assets/900f9019-021c-4c6e-94a6-c20aad74f342" />
  </p>
  <hr>
  <p>
 ^Step 11: Verify Your VM.

Search for Virtual machines again in the top search bar. Your new VM (e.g., windows-vm-demo) should now appear in the list with a Running status.  
  </p>
  <br />
  
