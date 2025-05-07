# AZ-IAM-Rbac
A simple, hands-on implementation of Azure Identity and Access Management (IAM) using Role-Based Access Control (RBAC) to demonstrate how to manage and assign roles to users in Azure and also it covers basic and intermediate Azure IAM concepts, including creating custom roles, assigning permissions,and managing access control for users in azure environment
# key concepts 
Role , Assignment , Permission , Scope , principles

Role : 
- A Role is a collection of permissions that determines what a user, group or service principle can do.
- Roles are 3 types
  1. Entra ID Roles  2. Azure Roles  3. Custom Roles
  1. Entra ID Roles: These are higher level or administrative level roles and can be assigned using RBAC
  2. Azure Roles : These are built-in roles. Ex: Owner (owner) , Contributor (can edit but can't give permissions), Reader (only read access) etc..
  3. Custom Role : These roles we can create and add specific permissions that are needed to a particular user to ciómplete the task.
     why Custom role is ?  if the built in roles doesnt satisfy the need. we can create custom role and add whatever permistions we need and assign to user,group or application.
 
Permission : 
A permission defines a specific action that can be performed on resource. common permissions are read,write,delete and update.

Assignment : 
A role assignment is a process in which you can assign a role to user,group or application at a specific scope 
Scope is a range from subscription -> resourse groups -> resourses 

Scope : 
A scope is a level at which a role is applied 
- Management groups 
- Subscriptions
- Resource groups
- Resourse

principles : 
principle is a user,group or application(service principles) to whom a role is assigned.


# RBAC (Role Based Access Control) : 
Azure RBAC is a powerful tool for managing access to Azure resources, allowing you to control who can access what and what they can do. 
Understanding the key concepts, role definitions, scopes, and best practices is essential for securing your Azure environment

# How to assign a roles in Azure ? 
Roles can be assigned using the Azure Portal, Azure CLI, Azure PowerShell, or ARM templates. Below are steps for assigning roles in the Azure Portal:

Navigate to the Azure Resource:
Go to the Azure Portal (https://portal.azure.com).
Find the resource, resource group, or subscription to which you want to assign a role.

Go to IAM (Identity and Access Management):
In the left-hand menu of the resource, find Access Control (IAM).
Click on + Add → Add role assignment.

Select Role and Assignee:
Choose the role you want to assign from the available list.
Select the user, group, or service principal to assign the role to.
Specify the scope for the role assignment (e.g., resource group or resource).

Review and Assign:
Review the details and click Save to assign the role.






