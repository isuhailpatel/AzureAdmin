# AzureAdmin
My Preparation Notes on Azure Administrator AZ-103

Azure Main Services
    - Virtual machines IaaS
    - App Service PaaS
    - Azure Storage
    - Data Services
        - SQL DB
        - Cosmos DB
        - Azure Backup
        - Azure DB for MySQL
        - Azure DB for PostgresSQL
        - SQL Datawarehouse
    - Microservices
        - Azure Functions
        - Azure Logic Apps
        - Service Fabric
    - Networking
        - Virtual Network
        - Load Balacer
        - Azure Traffic Manager
        - Application Gateway
        - VPN
    - Chat Bot Service
    - ML
    - Media Services
    - Cognitive Services
    - IOT

//There is no Programming involved in Az-10 exam but there is Scripting involved

-> Three main way to access Azure
    - Azure Portal
    - Powershell Az
    - Bash/CLI
- Json for templates is used

Basic Azure Bash CLI commands:
- Virtual Machines
    az vm list
    az vm create
    az vm delete

- Keyvaults
    az keyvault list
    az keyvault create
    az keyvault delete

- Networking
    az network vnet subnet list
    az network vnet create
    az network vnet delete

Similar Powershell Commands
    Get-AzVM
    New-AzVM
    Remove-AzVM

    Get-AzKeyVault
    New-AzKeyVault
    Remove-AzKeyVault

Setup - Powershell
    -Install v6.2 from https://github.com/PowerShell/PowerShell/releases    
    - Run command: Install-Module -Name Az -AllowClobber
    - Run $ Get-AzVM to test module installations
    - Run $ Connect-AzAccount to connect to your Azure Account
    - HandsOn Lab: https://www.microsoft.com/handsonlabs/selfpacedlabs/details/SP-AZ100000




