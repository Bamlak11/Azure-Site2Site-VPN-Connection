<h1>Azure Site 2 Site VPN Connection</h1>

<h2>Description</h2> 

<b>Within this project I will provide a step by step tutoarial on how to set up a site-to-site VPN connection through Azure. You will be able to create a virtual network, create a VPN gateway, a local network gateway, a VPN connection, and at the end connect it to your virtual machine! </b>


<h2>Create a virtual network</h2>
<p> From the Azure portal you first neet to navigate to the virtual network set up. <br>When creating a virtual network fill out a resource group, a name for you virtual network, Region, ipv4 address, and a subnet.</p>

![vmm](https://github.com/Bamlak11/Azure-Site2Site-VPN-Connection/assets/77420100/eb54e256-bb64-4cf4-9797-cd2ade330473)





<h2>Create a VPN gateway</h2>
<p>Next a VPN gateway must be created. This process may take more then 40 minutes to deploy<br> The information needed to fill out this information is a name, region, gateway type: VPN, SKU that you prefer, generation, Virtual network: select the virtual network you created, Gateway subnet address range, and Public IP address.<br> Once this is created click Review + Create.</p>

![VPNgw](https://github.com/Bamlak11/Azure-Site2Site-VPN-Connection/assets/77420100/3b0258ff-480d-4389-a362-cb320844c2cb)



<h2>Create a local network gateway</h2>
<p>A local network gateway is what will represent your on-premisis location.<br> For this section you must name your site, connect it to your resource group, choose region, and select an endpoint such as an IP address or FDQN for the on-premisis device. <br> You are able to configure BGP in the advance tab if needed. Once completed review and create your local network gateway. </p>

![Local Network Gateway](https://github.com/Bamlak11/Azure-Site2Site-VPN-Connection/assets/77420100/835a83b9-101e-4fa5-851a-fe73c214f6f5)


<h2>Create a VPN connection</h2>
<p></p>

![Create Connection](https://github.com/Bamlak11/Azure-Site2Site-VPN-Connection/assets/77420100/64cdd6da-1e0e-45e0-b130-07affc1a0a95)


<h2>Connect to a virtual machine</h2>
<p></p>

![VM-1](https://github.com/Bamlak11/Azure-Site2Site-VPN-Connection/assets/77420100/3d946802-25cf-4e7f-b479-e8544424309c)



