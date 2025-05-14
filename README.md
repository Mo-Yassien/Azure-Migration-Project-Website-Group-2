# Azure Website Migration Project

This project simulates the process of migrating a website from an on-premises environment (IIS on a virtual machine) to Azure App Service. The project is divided into four main phases over four weeks, simulating a full cloud migration scenario.

---

## Project Objective

To demonstrate a full migration process of a website:
- From an IIS server hosted on an Azure VM
- To Azure App Service
- With support for authentication, database integration, and production readiness

---

## Weekly Plan and Implementation

---

### Week 1: Create Source Environment on Azure

**Tasks:**
- Create a Virtual Machine (Windows Server 2022)
- Install and configure IIS
- Host a sample website and bind it to a custom domain and subdomains

**Deliverables:**
- VM with IIS running and accessible

**Tools:**
- Azure Student Account
- Remote Desktop
- IIS

---

### Week 2: Build Landing Zone in Azure App Service

**Tasks:**
- Create an App Service with Standard S1 plan
- Use ASP.NET 4.8 framework to create a staging slot
- Enable Microsoft authentication (Azure AD)
- Set manual scaling to 3 instances
- Verify public access to the App Service from external machines

**Deliverables:**
- App Service (Standard S1) with Microsoft authentication and 3 scaled instances

**Tools:**
- Azure Portal
- Azure AD
- Browser

---

### Week 3: Import Website into IIS Server (Source Server)

**Tasks:**
- Instead of downloading a sample website, a custom website was built from scratch. It includes:
  - Project overview
  - Timeline
  - Team members
- Developed using HTML/CSS and ASP.NET Core
- Published from Visual Studio Code using `Self-contained` deployment
- Deployed to the `wwwroot` directory on the IIS server

**Publishing Settings:**
- Configuration: Release
- Target Framework: .NET 8
- Deployment Mode: Self-contained

**Deliverables:**
- Custom website hosted on IIS inside the VM

**Tools:**
- Visual Studio Code
- IIS
- Remote Desktop

---

### Week 4: Migrate from On-Premises to Cloud

**Tasks:**
- Use Azure Migrate to assess the on-premises environment
- Create an Azure migration project
- Migrate the IIS-hosted website to Azure App Service
- Validate the results and test authentication and database connectivity

**Deliverables:**
- Website fully functional on Azure App Service
- Azure Migrate assessment reports

**Tools:**
- Azure Migrate
- Azure App Service Migration Assistant
- Azure Portal

---

## Technologies Used

- Microsoft Azure
- IIS Server
- ASP.NET Core 8
- HTML / CSS
- Azure App Service
- Visual Studio Code
- Azure Active Directory
- Windows Server 2022

---

## Final Outcome

- Website hosted and tested on IIS (Azure VM)
- Successfully migrated to Azure App Service
- Authentication integrated using Microsoft login
- Scalable and production-ready cloud environment

---

## License

This project was developed as part of a graduation project under the supervision of DEPI, using Microsoft Azure for Students resources.
