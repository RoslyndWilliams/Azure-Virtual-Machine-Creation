<p align="center">
  <img src="https://i.imgur.com/4wqxHID.png" alt="Microsoft Azure Logo" width="60%">
</p>

# Azure Virtual Machine Setup for Small Business IT

This project demonstrates how a small business—like a dental clinic or startup—can deploy a cloud-based IT environment using Microsoft Azure. You'll learn how to spin up a virtual machine to support remote access, centralized resources, and secure admin controls.

---

## 📌 Use Case

A 10-person dental office is opening a second location and needs access to its scheduling and billing software. Instead of buying new physical servers, the office deploys a Windows virtual machine using Azure to enable remote access for all staff.

---

## ✨ Key Features

- Fully cloud-based deployment using Microsoft Azure
- Secure, RDP-enabled access for remote staff
- Scalable setup for file storage, application hosting, or Active Directory
- Step-by-step screenshots included

---

## ⚙️ Requirements

- Computer with internet connection
- Microsoft account
- Credit card (required for Azure’s free $200 credit)

---

## 🛠️ Configuration Steps

### 1. Create an Azure Account
[Sign up here](https://azure.microsoft.com/en-us/free/) and claim your free credit.

1. Click **Start Free**
2. Enter your info and verify with a credit card (you won’t be charged)
3. Access the portal at [portal.azure.com](https://portal.azure.com)

### 2. Create a Resource Group
- Search **“Resource group”** and select **Create**
- Name it (e.g., `RG-Lab-1`) and choose a region (e.g., `West US 3`)
- Click **Review + Create**

![Create Resource Group](https://i.imgur.com/Afnk87u.png)

---

### 3. Create a Storage Account
- Search **“Storage Account”** and click **Create**
- Use the same resource group and region
- Name it something like `rglab1`
- Click **Review + Create**

![Create Storage Account](https://i.imgur.com/zhb3GHZ.png)

---

### 4. Create a Virtual Machine
- Search **“Virtual Machine”** and select **Create**
- Use the same resource group and region
- Choose:
  - **Name**: `VirtualMachine`
  - **Image**: Windows 10 Pro
  - **Size**: Standard D2as_v4
  - **Username**: `labuser` + your password

- Accept licensing terms and click **Review + Create**

![VM Setup](https://i.imgur.com/p9UJXND.png)

---

### 5. Connect to the VM

#### Windows:
- Open **Remote Desktop**
- Enter the **public IP** from your Azure portal
- Log in with your username/password

#### Mac:
- Download **Microsoft Remote Desktop** from the App Store
- Click **Add PC**, paste in the IP
- Log in and connect

![RDP Login](https://i.imgur.com/T4Oc2RX.png)

---

### 🎉 Congratulations!
You've successfully deployed and accessed a virtual machine in Azure.

<p align="center">
  <img src="https://i.imgur.com/rEBpL8Y.png" alt="Azure Portal" width="70%">
</p>

---

## 🧹 Cleanup Tip

Delete your resource group after the lab to avoid charges:
- Go to **Resource Groups**
- Click **Delete** to remove all associated resources

---

## 🔗 Bonus

Want to build a ticketing system on your new VM?  
Check out [Part 1 of my osTicket lab](https://github.com/RoslyndWilliams/osTicket--Prerequisites-and-Installation)

---

*Created by Roslynd Williams – bridging tech fluency with customer-centered sales insight.*

