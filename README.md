---
page_type: sample
languages:
- csharp
products:
- azure
extensions:
- services: MySQL
- platforms: dotnet
---

# Getting started on managing MySQL databases in C# #

Azure sample for managing MySQL Database -
  - Check name availability for the server creation.
  - Create a MySQL Server.
  - Update the server's properties.
  - Create a firewall rule.
  - Update a firewall rule.
  - List and delete the firewalls rules.
  - Get and update a configuration of the server.
  - Delete the server.


## Running this Sample ##

To run this sample:

Create an Azure service principal with the [Azure CLI][] command `az ad sp create-for-rbac --output json` and set the following environment variables per that command's 
output. 
`AZURE_TENANT_ID`, `AZURE_CLIENT_ID`, `AZURE_SECRET`, `AZURE_SUBSCRIPTION_ID`

    git clone https://github.com/Azure-Samples/mysql-dotnet.git

    cd mysql-dotnet

    dotnet run

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.