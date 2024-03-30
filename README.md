# 1.Azure virtual machines
Azure virtual machines (VMs) empower you to perform a wide range of tasks in the cloud, thanks to their flexibility and scalability. Here are some of the key functionalities they offer:

1. Run diverse applications

2. Development and testing

3. Scalability as needed

4. Cost-effective resource utilization

5.Extend on-premises infrastructure

![WhatsApp Image 2024-03-30 at 12 03 22_9606225b](https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/5a21a8fb-9020-4435-b038-fcbf19bda5ba)

## Azure virtual machine usage
Azure virtual machine usage translates to how you leverage these cloud-based computers and how Microsoft bills you for that usage.


#### 1.Billing based on consumption:
Azure uses a pay-as-you-go model for VMs. You are billed for the compute resources your VM consumes, measured in compute hours.
#### 2.Understanding usage meters:
When you look at your bill, you'll see terms like meter identifier and unit. The meter identifier specifies the VM size, operating system (Windows or non-Windows), and region. The unit is always "Compute Hours," which reflects how long your VM ran
#### 3.Factors affecting usage costs:
The cost of running an Azure VM depends on the VM size (resources allocated), OS type (Windows usually incurs a higher cost), and the region where the VM is located.

## Configuration

#### Subscription: 

<img width="830" alt="image" src="https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/7239333b-e5be-46a6-9da2-848bb1f92a6d">

The Azure subscription you'll use to pay for the VM.
#### Resource Group: 
An organizational unit within Azure to manage your VM along with related resources (storage, network).

<img width="959" alt="image" src="https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/8535e89c-b9fe-41e1-aef5-c8e8bdee6ef5">

#### VM Name:
A unique name to identify your virtual machine.

<img width="958" alt="image" src="https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/0798e2d6-5645-4c96-9ee8-2778c0dc8f39">

#### Region: 
The geographical location where your VM resides. Choose a region close to your target users for optimal performance.

<img width="953" alt="image" src="https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/bfe5e5a3-c1c3-4019-a224-0780f8b59613">

#### Instance Details:

  #### Virtual Machine Image (OS):
   Select the operating system you want to run on the VM, such as Windows Server, Linux distributions (Ubuntu, Red Hat, etc.), or custom images.
  #### VM size:
   This determines the compute resources allocated to your VM, including CPU cores, memory, and storage. Choose a size that balances performance needs with cost.
#### Networking:

   #### Virtual Network:
   A designated network within Azure where your VM resides. This allows VMs to communicate securely with each other and access other Azure services.
   
   <img width="561" alt="image" src="https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/9bbfb53f-b43b-4c73-ab84-ca3f13da80af">

  #### Subnet:
  A specific network segment within the virtual network for further resource organization.
  #### OtherS setup
Public IP Address (optional): Assigns a public IP to your VM for internet accessibility. You can restrict access with firewalls.

<img width="715" alt="image" src="https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/e8dd5139-33a9-4ec8-b3bb-5434ce08457b">

Security:

Username and Password: Create credentials for administrative access to your VM.
SSH Keys (for Linux): Alternatively, use SSH key pairs for secure login to your Linux VM.
Network Security Group (NSG): Define inbound and outbound traffic rules to control what kind of network traffic reaches your VM.
Management:

Boot diagnostics: Enable boot diagnostics to troubleshoot VM startup issues if needed.
Monitoring: Configure monitoring to track VM performance and resource utilization.
There are two main methods for configuring Azure VMs:

Azure portal: A web-based interface that provides a user-friendly way to configure VMs through a series of steps.
Azure CLI or PowerShell: Command-line tools offering more granular control and automation capabilities for VM configuration, especially for managing multiple VMs at once.

# 2.Azure Storage services
Azure Storage services empower you to perform a wide range of data storage and management tasks in the cloud. Here are some of the key functionalities they offer:

 1. Store diverse data types
 
 2. Facilitate application communication
 
 3. Store large amounts of structured NoSQL data
 
 4. Scale storage on-demand
 
 5. Securely access data from anywhere
    
## Azure Storage Usage

 ### Functionalities:

   #### 1. Blob storage (unstructured data)
   #### 2. File storage (shared files)
   #### 3. Disk storage (VM disks)
   #### 4. Queue storage (application communication)
   #### 5. Table storage (structured NoSQL data)
     
 ### Billing and Costs:

  #### 1. Pay-as-you-go model
  #### 2. Metered by resource type and tier (e.g., blob storage, Standard)
  #### 3. Storage tier (Standard vs. Premium)
  #### 4. Data replication
  #### 5. Data access (egress charges)
  #### 6. Optimizing Usage Costs:
  #### 7. Monitor storage usage with Azure Monitor


  ## Configuration
  
  #### Subscription:
  <img width="830" alt="image" src="https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/f92ce5de-e8cb-4989-ba88-ca7d2ba9a236">

  
  The Azure subscription that will pay for the storage account.

  #### Resource Group: 
  An organizational unit to manage your storage account along with related resources (security, networking).
  
  <img width="939" alt="image" src="https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/2cd91a14-ab67-4e01-adaf-03e8a48bebb1">

  #### Location: 
  The geographical region where your data resides. Choose a region close to your target users for optimal performance.

  <img width="554" alt="image" src="https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/14bd543d-903c-47ff-9463-f6fe7fb3a0b5">

  #### Account Name: 
  A unique name to identify your storage account

  <img width="514" alt="image" src="https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/8068a7ad-717e-45d1-9533-2f926d270c0d">


#### Storage Account Name:

<img width="829" alt="image" src="https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/dc287174-e9d3-46a0-949d-331d866775f3">

#### Create File Shares:

<img width="958" alt="image" src="https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/4b37da39-3962-444b-ad85-c7220fdd3c39">

#### Create Containers:

<img width="909" alt="image" src="https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/50d4ef8d-b1d3-4c7b-be0d-293dfc2c3aa3">

#### Create Queues:

<img width="920" alt="image" src="https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/89747454-0e77-43ff-81f8-392f9aa7e05e">

#### Create Tables:

<img width="953" alt="image" src="https://github.com/Alpha-Soumen/FRTPROJECT/assets/156820375/e933cf53-4fc1-4946-b19c-bbbe91ab95a6">











  

  

