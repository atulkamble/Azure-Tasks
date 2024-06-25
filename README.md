# Azure-Tasks
Azure Admin &amp; DevOps Technical Tasks and Solutions
Sure, here are detailed tasks and solutions for both Azure Admin and Azure DevOps roles. These tasks are designed to help you gain practical experience in managing Azure resources and implementing DevOps practices.

## Azure Admin Tasks

### Task 1: Create and Manage Azure Virtual Machines (VMs)
**Objective**: Learn to create, configure, and manage VMs in Azure.

**Steps**:
1. **Create a VM**:
   - Log in to the Azure Portal.
   - Navigate to "Virtual Machines" > "Create".
   - Choose the "Windows Server 2019 Datacenter" image.
   - Configure the VM size, username, and password.
   - Review and create the VM.
2. **Manage the VM**:
   - Connect to the VM using Remote Desktop (RDP).
   - Install IIS on the VM via PowerShell.
   - Verify the IIS installation by accessing the VM's public IP address in a browser.

**Deliverable**: Screenshots of the VM creation process and IIS running on the VM.

### Task 2: Configure Azure Virtual Network (VNet) and Subnets
**Objective**: Understand how to create and manage VNets and subnets.

**Steps**:
1. **Create a VNet**:
   - Navigate to "Virtual Networks" > "Create".
   - Define the address space (e.g., 10.0.0.0/16).
   - Create two subnets (e.g., 10.0.1.0/24 for front-end, 10.0.2.0/24 for back-end).
2. **Attach VM to VNet**:
   - Attach the previously created VM to the new VNet and subnet.
   - Create a Network Security Group (NSG) and associate it with the subnets.
   - Configure NSG rules to allow RDP traffic.

**Deliverable**: Diagram of the VNet configuration and screenshots of the subnets and NSG rules.

### Task 3: Implement Azure Storage Account and Blob Storage
**Objective**: Learn to create and manage Azure Storage accounts and blobs.

**Steps**:
1. **Create a Storage Account**:
   - Navigate to "Storage accounts" > "Create".
   - Choose "Standard" performance and "Hot" access tier.
2. **Create a Blob Container**:
   - Within the storage account, create a container named "sample-container".
   - Upload a file to the container and set its access level to "Blob (anonymous read access)".
   - Generate a SAS token for secure access.

**Deliverable**: Public URL of the uploaded file and a screenshot of the storage account and container settings.

### Task 4: Deploy and Configure Azure SQL Database
**Objective**: Set up and configure an Azure SQL Database.

**Steps**:
1. **Create SQL Database**:
   - Navigate to "SQL databases" > "Create".
   - Configure the database server, name, and pricing tier.
2. **Manage SQL Database**:
   - Use SQL Server Management Studio (SSMS) to connect to the database.
   - Create a table and insert sample data using T-SQL.

**Deliverable**: Screenshot of the database table with sample data and configuration settings.

### Task 5: Set Up Azure Monitor and Alerts
**Objective**: Learn to monitor Azure resources and set up alerts.

**Steps**:
1. **Create an Alert Rule**:
   - Navigate to "Monitor" > "Alerts" > "New alert rule".
   - Select a resource (e.g., the VM) and define the condition (e.g., CPU percentage > 80%).
   - Configure the action group to send an email notification.
2. **Trigger the Alert**:
   - Simulate high CPU usage on the VM to trigger the alert.
   - Verify the alert notification.

**Deliverable**: Screenshot of the alert rule configuration and email notification.

## Azure DevOps Tasks

### Task 1: Set Up a New Azure DevOps Project
**Objective**: Get familiar with Azure DevOps project setup.

**Steps**:
1. **Create a DevOps Project**:
   - Navigate to Azure DevOps and create a new project.
   - Configure repository settings (e.g., Git).
2. **Add Code to Repository**:
   - Clone the repository locally and add sample code.
   - Push the code to the Azure DevOps repository.

**Deliverable**: Link to the Azure DevOps project and screenshots of the repository with code.

### Task 2: Implement a CI/CD Pipeline
**Objective**: Automate the build and deployment process using pipelines.

**Steps**:
1. **Create a Build Pipeline**:
   - Navigate to "Pipelines" > "Create Pipeline".
   - Use the YAML file to define the build process (e.g., build and test a .NET application).
2. **Create a Release Pipeline**:
   - Navigate to "Releases" > "New pipeline".
   - Configure the pipeline to deploy the build artifact to an Azure App Service.
   - Define stages, tasks, and variables for deployment.

**Deliverable**: Screenshot of the build and release pipelines, and the URL of the deployed app.

### Task 3: Implement Infrastructure as Code (IaC) with ARM Templates
**Objective**: Use ARM templates to deploy Azure resources.

**Steps**:
1. **Create an ARM Template**:
   - Write an ARM template to deploy a storage account and a web app.
   - Validate the template using Azure CLI or Azure Portal.
2. **Deploy Using Pipeline**:
   - Create a pipeline in Azure DevOps to deploy the ARM template.
   - Configure the pipeline to use the ARM template stored in the repository.

**Deliverable**: ARM template file and screenshot of the deployed resources in Azure.

### Task 4: Configure Azure DevOps Boards for Agile Planning
**Objective**: Use Azure Boards to manage work items and plan sprints.

**Steps**:
1. **Create Work Items**:
   - Navigate to "Boards" > "Work items".
   - Create user stories, tasks, and bugs.
2. **Plan a Sprint**:
   - Set up a sprint in "Boards" > "Sprints".
   - Assign work items to the sprint and team members.
   - Track the progress using the sprint board.

**Deliverable**: Screenshot of the sprint board with assigned work items.

### Task 5: Set Up Continuous Monitoring with Azure DevOps
**Objective**: Implement continuous monitoring for deployed applications.

**Steps**:
1. **Integrate Application Insights**:
   - Add Application Insights to the deployed web app.
2. **Configure Monitoring**:
   - Set up telemetry collection and alert rules in Application Insights.
   - Create a dashboard in Azure DevOps to visualize application performance and metrics.

**Deliverable**: Screenshot of the Application Insights configuration and Azure DevOps dashboard.

These tasks should give you practical experience in both Azure Administration and Azure DevOps practices. Let me know if you need further details or step-by-step instructions for any specific task!
