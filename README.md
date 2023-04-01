<p align="center">
<img src="https://user-images.githubusercontent.com/129001903/229301406-5e3950c2-d027-4726-bd5a-866e2cce1f13.png"
</p>

<h1>Creating A Virtual Networks and Subnets in Azure</h1>

<h2>Description</h2>

In this Project I will show you how to use Azure Services to create two virtual networks using Windows and Linux. Services i will use, resource group, virtual machine, and network watcher. I will provide pictures as well as step by step detail on the process.  <br />

<h2>Services Used</h2>

- Microsoft Azure
- Virtual Network
- Resource Group
- Network Watcher

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>Microsoft Azure</h2>

<p align="center">
<img src="https://imgur.com/HL6umIg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Azure Network Services perform networking operations within Azure and between Azure and on-premises infrastructure. These include Azure Virtual Network, Azure Resource group, Azure Network Watcher, and Azure Security Groups.</p>



<h2>Resource Group</h2>
<p align="center">
<img src="https://user-images.githubusercontent.com/129001903/229301222-92ed0781-3d9f-4147-8c18-980569abae0b.png">

</p>

- Subscription: Select your Azure Subscription 
- Resource groups: Enter a new Resource Group name
- Region: Select an Azure location
- Create: Select Review + Create and in seconds your resource group is complete.

</p>
<br />



<h2>Virtual Network</h2>
<p align="center">
<img src="https://user-images.githubusercontent.com/129001903/229301256-3f62c583-434c-4e4a-993f-91a76ee88e94.png">

<p>
                                                                          
- Select Virtual Machine                                                  
- Subscription: Select your Azure Subscription                            
- Create a name for your Virtual Network 
- Resource groups: Enter a new Resource Group name you created            - 
- Add a Region: Any is region is fine
- Select Image: Windows or Ubuntu Server
- Select a Size: D4s-4vcups
- Create a Username and Password
- Review and Create once validation passed

</p>
<br />



<h2>Network Watcher</h2>
<p align="center">
<img src="https://imgur.com/zt9cASI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

- Select Networker Watcher
- Select Topology
- Subscription: Select your Azure Subscription
- Resource groups: Select Resource Group
- Virtual Network: Select VM name

<p>

</p>
<br />
