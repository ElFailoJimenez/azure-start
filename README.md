<p align="center">
<img src="https://i.imgur.com/1DDZ4Ui.png" height="50%" width="50%" alt="Microsoft Azure Logo"/>
</p>
<p align="justify">
<h1>Microsoft Azure</h1>

This demonstration will show how to do the following:
  - Setup a FREE* Azure account
  - Create a Resource Group
  - Create a Storage Account
  - Create a Virtual Machine (VM)
  - Connect to the VM using Remote Desktop

<h2>Requirements</h2>

- Computer w/ Internet Connection
- Credit Card (Required for free Azure credits)
- Remote Desktop Connection (Windows) / Microsoft Remote Desktop (Mac)
  
<h2>Step Process</h2>

<h3>&#9312; Create a FREE* Azure Account</h3>

Go to [https://azure.microsoft.com/en-us/free/](https://azure.microsoft.com/en-us/free/)
- Click "Start Free".
- Follow the prompt to create an account.
  - You WILL need to put in your credit card information to receive the free $200 worth of Azure credits!
    <div> It will not charge you, <b>but only lasts for 30 days!</b>
- Once completed, click on <a href="https://portal.azure.com/">Go to the Azure Portal (portal.azure.com)</a>.
<p align="center">
<img src="https://i.imgur.com/FklBT6F.jpg" height="64%" width="64%" alt="Azure Free Account"/>
</p><hr>

<h3>&#9313; Create a Resource Group</h3>

- In the Search Box at the top header, type and select "Resource groups".
  - If "Resource groups" is already listed on the front page, then you can simply click on it, rather than manually searching.
<p align="center">
<img src="https://i.imgur.com/gza489d.jpg" height="64%" width="64%" alt="Azure Step 2-1"/>
</p>

- Click "Create" on the top left menu, OR simply press "Create resource group" in the center box (assuming one doesn't exist yet).
<p align="center">
<img src="https://i.imgur.com/5Jo1cEg.jpg" height="64%" width="64%" alt="Azure Step 2-2"/>
</p>

- Name your "Resource group" to whatever you want (this example uses **RG-01**).
- Change the "Region" to a location that is closest to you (this example uses **(US) West US 3**).
- Skip everything else and click "Review + Create" on the lower left, which you should have "Validation passed" on the next page.
- Click "Create".
<p align="center">
<img src="https://i.imgur.com/BSiQM05.jpg" height="100%" width="100%" alt="Azure Step 2-3"/>
</p><hr>

<h3>&#9314; Create a Storage Account</h3>

- In the Search Box at the top header, type and select "Storage accounts".
  - If "Storage accounts" is already listed on the front page, then you can simply click on it, rather than manually searching.
<p align="center">
<img src="https://i.imgur.com/HMUaR98.jpg" height="70%" width="70%" alt="Azure Step 3-1"/>
</p>

- Same with Resource Groups, click on "Create Storage account".
<p align="center">
<img src="https://i.imgur.com/sGDY2Im.jpg" height="70%" width="70%" alt="Azure Step 3-2"/>
</p>

- Use the same resource group that was just created (this example uses **RG-01**).
- Create a unique name for the storage account that hasn't already been taken (this example uses **saname01**).
- Choose the same region (this example uses **(US) West US 3**).
- Skip everything else and click "Review", then "Create".
<p align="center">
<img src="https://i.imgur.com/07sG8Z6.jpg" height="100%" width="100%" alt="Azure Step 3-3"/>
</p><hr>

<h3>&#9315; Create a Virtual Machine</h3>
     
- In the Search Box at the top header, type and select "Virtual machines".
  - If "Virtual machines" is already listed on the front page, then you can simply click on it, rather than manually searching.
<p align="center">
<img src="https://i.imgur.com/6DdH3MD.jpg" height="70%" width="70%" alt="Azure Step 4-1"/>
</p>

- Click "Create", then select "Azure Virtual Machine"
<p align="center">
<img src="https://i.imgur.com/tiC5aA4.jpg" height="70%" width="70%" alt="Azure Step 4-2"/>
</p>

- Use the same resource group (this example uses **RG-01**)
- Name your virtual machine however you want (this example uses **virtualmachine01**)
- Use the same region (this example uses **(US) West US 3**)
- Choose your "Image" (this example uses **Windows 10 Pro, version 22H2 - x64 Gen2**)
- Choose a "Size" (this example uses **Standard_E2s_v3 - 2 vcpus, 16 GiB memory**)
- Create any username and password of your choice (this example uses the username: **vmuser**)
  - Make sure NOT to forget these credentials.
- Check the "Licensing" checkbox.
- Click "Review + create".
  - Once validation passed, click "Create".
<p align="center">
<img src="https://i.imgur.com/UaviYRo.jpg" height="70%" width="70%" alt="Azure Step 4-3"/>
<img src="https://i.imgur.com/mcix7TW.jpg" height="70%" width="70%" alt="Azure Step 4-4"/>
</p><hr>

<h3>&#9316; Connect to the Virtual Machine via Remote Desktop</h3>

- Go to your Virtual Machine that was just created and COPY the public IP address (located on the right side).
<p align="center">
<img src="https://i.imgur.com/Cr02uvs.jpg" height="100%" width="100%" alt="Azure Step 5-1"/>
</p>

- Press the Windows Key (or Start Button), type and select "Remote Desktop Connection".
- Input the virtual machine's Public IP Address and click Connect.
- Enter the username and password from Step 4 above, then click OK.
  
<p align="center">
<img src="https://i.imgur.com/rP1uKCe.jpg" height="64%" width="64%" alt="Azure Step 5-2"/>
</p>

- Macintosh users will have to take a different approach:
  - Download "Microsoft Remote Desktop", and Open it.
- Click Add PC", input the public IP address, then select "Add".
<p align="center">
<img src="https://i.imgur.com/ZhWBhLs.png" height="50%" width="50%" alt="Azure Step 5-2-1"/>
<img src="https://i.imgur.com/Mx1gHxa.png" height="50%" width="50%" alt="Azure Step 5-2-2"/>
</p>
  
- Double-click on the virtual machine, then enter the username and password from Step 4 above.
- Select "Continue".
- A prompt will appear about the identity cannot be verified; just press "YES".
<p align="center">
<img src="https://i.imgur.com/3YxlS2G.jpg" height="64%" width="64%" alt="Azure Step 5-3"/>
</p>

- Toggle any settings you want, then click "Accept".
<p align="center">
<img src="https://i.imgur.com/VlNH4O9.jpg" height="50%" width="50%" alt="Azure Step 5-4"/>
</p>

🎊 CONGRATULATIONS! You have created your first virtual machine within Azure! 🎊
<p align="center">
<img src="https://i.imgur.com/PpLmQO7.jpg" height="80%" width="80%" alt="Azure Step 5-5"/>
</p>
<hr>

<h3>BONUS: Delete All Resources In Azure</h3>

_To retain your free Azure credits as much as possible, we have to make sure we DELETE ALL resources after every project._
- From Azure, go to Resource Groups, select any Resource listed, then click "Delete resource group".
- Type the resource group name to confirm deletion (faster to copy/paste the name).
- Then click "Delete".
_Repeat these steps for each and every resource group listed until all are deleted_
<p align="center">
<img src="https://i.imgur.com/Yedg9Cl.jpg" height="80%" width="80%" alt="Azure Step 5-5"/>
</p>
  
_If you have any created virtual machines:_
- From Azure, go to "Virtual Machines", select any that are listed, the click "Delete".
- Checkmark the box "I have read and understand..."
- Then click "Delete".
_Repeat these steps until all listed are deleted._
<p align="center">
<img src="https://i.imgur.com/T8VFNCO.jpg" height="80%" width="80%" alt="Azure Step 5-5"/>
<img src="https://i.imgur.com/dkuz7TD.jpg" height="80%" width="80%" alt="Azure Step 5-5"/>
</p>

_Best way to check if all resources are gone is going to "All resources" from the Portal Home page to see if anything remains._
<p align="center">
<img src="https://i.imgur.com/gVnbWJS.jpg" height="80%" width="80%" alt="Azure Step 5-5"/>
</p>
  
<h1><p align=center>(ﾉ^ヮ^)ﾉ*:・ﾟ✧ COMPLETE! ✧ﾟ・:*╰(^ヮ^╰)</p></h1>

<h2><p align=center>Next Demonstration:<br><a href="https://github.com/JTYKolesar/configure-ad">Configuring On-premises Active Directory within Azure VMs</a></p></h2>
