# Logging into Azure Account - CLI

Azure CLI (or Command-Line Interface) is a utility developed and maintained by Microsoft to help Azure customers to create from simple to complex environment directly from the command-line like you probably do on MS-Dos or PowerShell to other activities in your server or local computer.

For each Azure service, there must be a bunch of commands and properties that put together can do marvelous things on top of Azure. This is helpful for a customer who would like to create automation on Azure, like DevOps pipelines, and so forth.

> Please, keep in mind that Azure provides two versions of Azure CLI; 1.0 and 2.0. The first one is still operational but will be deprecated soon, so I strongly recommend you start using the version 2.0, which is written in Python.

## Installing Azure CLI 2.0

You will need to install Azure CLI to get access to its resources. You'll find out such amazing tutorial in "how to install Azure CLI 2.0" for your operational system following-up that links:

* [Windows](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-windows?view=azure-cli-latest)
* [MacOS](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-macos?view=azure-cli-latest)
* Linux Subsystem for Windows
    * [Ubuntu or Debian](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-apt?view=azure-cli-latest)
    * [RHEL, Fedora or CentOS](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-yum?view=azure-cli-latest)
    * [OpenSUSE or SLE](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-zypper?view=azure-cli-latest)
    * [Installing from script](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-linux?view=azure-cli-latest)
* [Docker](https://docs.microsoft.com/en-us/cli/azure/run-azure-cli-docker?view=azure-cli-latest)

## Getting yourself authenticated through interactive login using Azure CLI

Azure CLI 2.0 uses the "az" sentence as primitive to advice the interpreter that this is a azure CLI application. This is, to get yourself authenticated on the Azure platform, type the following command in either your CMD, PowerShell, Linux Subsystem or Terminal (for Mac and Linux).

```shell
az login
```

By doing this, CLI utility will communicate with Azure Active Directory (AAD) and ask it for an new authentication process. Then you will see a message like that one shown by belows picture.

<img src="https://raw.githubusercontent.com/AzureForEducation/demo-azure101/master/images/azure-cli-interactive-login2.PNG">

This screen means that you must open up your prefered browser and type in there (address bar) the address "https://microsoft.com/devicelogin". By doing this a new web page asking for your access code will raise up. Just type that access code provided by the before's step into the proper field and click in "Continue". If requested, authenticate yourself with your Azure credential.



By doing this, you should be able to see a list of all the subscriptions tied to your account, as shown by the figure below.