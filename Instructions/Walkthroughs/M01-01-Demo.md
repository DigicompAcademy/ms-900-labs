# ---
wts:
    title: '01 - Demo M365 Fundamentals (10 min)'   
    module: '01 - Core'
---
# 01 - Create a ms teams group (10 min)

In this walkthrough, we will create a ms teams group. 

**Note**: Take time during this walk-through to click and read the Informational icons. 

# Task 1: Bli Bla
1. Sign-in to the Azure portal: **https://portal.azure.com**

2. Test bli Bla

3. On the **Basics** tab, fill in the following information (leave the defaults for everything else):

    | Settings | Values |
    |  -- | -- |
    | Subscription | **Use default supplied** |
    | Resource group | Click on **Create new** <br /> Name: **01-myVM** |
    | Virtual machine name | **myVM** |
    | Region | **(US) East US**|
    | Availability options | No infrastructure redundancy options required|
    | Image | **Windows Server 2025 Datacenter - x64 Gen2**|
    | Size | **Standard D2s v3**|
    | Administrator account username | **azureuser** |
    | Administrator account password (type in carefully!) | **Pa$$w0rd1234**|
    | Inbound port rules - | **Allow select ports **|
    | Select inbound ports | **RDP (3389)** and **HTTP (80)**| 

    ![Demo File.](../images/M01-demo.png)


**Note**: To avoid additional costs, you can optionally remove this resource group. Search for resource groups, click your resource group, and then click **Delete resource group**. Verify the name of the resource group and then click **Delete**. Monitor the **Notifications** to see verify that the deletion completed successfully. 
