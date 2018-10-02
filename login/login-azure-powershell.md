# Logging into Azure Account - PowerShell

The process to get yourself authenticated on Azure through Powershell is pretty similar to that one described for CLI meaning that you will need, first, install the Azure RM module into your computer. To do so, just follow up the steps described in [this link](https://docs.microsoft.com/en-us/powershell/azure/install-azurerm-ps?view=azurermps-6.9.0).

## Getting yourself authenticated interactively

The steps to get yourself authenticated through the PowerShell environment are listed below.

1) Open up your PowerShell utility
2) Once that, just type the following command:
    ```powershell
    Connect-AzureRmAccount
    ```

When run, this cmdlet will bring up a dialog box prompting you for your email address and password associated with your Azure account. This authentication lasts for the current PowerShell session.

You're all set.