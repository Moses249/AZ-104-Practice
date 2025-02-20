# Manage Azure Resources Using ARM Templates

## Overview
This lab provides hands-on experience in deploying and managing Azure resources using Azure Resource Manager (ARM) templates. You will learn how to create, modify, and deploy ARM templates and use Bicep to simplify deployments.

## Prerequisites
- An active Azure subscription
- Azure Cloud Shell (PowerShell and CLI)
- Basic knowledge of Azure Resource Manager

## Lab Tasks
### 1. Create an ARM Template
- Deploy a managed disk via the Azure portal.
- Export the ARM template for reuse.

### 2. Edit and Redeploy the Template
- Modify the exported template to deploy a new managed disk with different configurations.

### 3. Deploy the Template Using Azure PowerShell
- Utilize Azure Cloud Shell with PowerShell to deploy the ARM template.

### 4. Deploy the Template Using the Azure CLI
- Use the Azure CLI within Cloud Shell to deploy the template.

### 5. Deploy a Resource Using Azure Bicep
- Leverage a Bicep file to deploy a managed disk, demonstrating its concise syntax.

## Key Learnings
- Understanding ARM templates for infrastructure as code.
- Deployment automation using Azure CLI and PowerShell.
- Introduction to Bicep as an alternative to JSON ARM templates.

## Resources
- [Microsoft Learn: ARM Templates](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/overview)
- [Bicep Language](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/)

## License
This lab content is part of the Microsoft Learning AZ-104 course and follows its licensing guidelines.
