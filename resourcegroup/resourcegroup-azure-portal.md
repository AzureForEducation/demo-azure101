# Resource Group - Portal

Resource Groups are logical unities designed to group up workloads on Azure. Ideally, resource groups should be built in such a way that all the resources inside of it would be turned off at the same time with no or minimal impact to the application being deployed.

A resource group is all about management and governance. By correctly grouping the things, you'll be able to control cost, access, and so forth. This is why Microsoft Azure requires you to create every single service/resource inside a resource group.

## Creating a new Resource Group through the Portal

As everything on top of the Azure Portal, creating a new resource group is pretty simple and straightforward, as follows.

1) In your Azure dashboard, navigate to the main menu on the left side on top and do click in "+ Create a resource". On the search box, type "Resource group".

2) A new window will be shown describing what a resource group is. Just click on "Create", as you can see below.

    <img src="https://raw.githubusercontent.com/AzureForEducation/demo-azure101/master/images/rg-create-description.PNG" width="400" />

3) By clicking on "Create" a new screen will be shown. Inform the resource group name, the Azure subscription in which the resource group will be tied to, and the location where this resource group is going to seat up. The figure below shows this process.

    <img src="https://raw.githubusercontent.com/AzureForEducation/demo-azure101/master/images/rg-create-form.PNG" width="250" />

Done. In a few seconds, you will have a new resource group up and running and ready to receive workloads inside of it.