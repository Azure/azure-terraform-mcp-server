# Azure Terraform MCP Server

> **⚠️ DEPRECATED — This project is no longer maintained.**
>
> The functionality previously provided by this project has been consolidated into the **[Azure MCP Server](https://github.com/microsoft/mcp/blob/main/servers/Azure.Mcp.Server/README.md)**, which now ships a built‑in **Azure Terraform** tool area covering Terraform provider documentation (AzureRM and AzAPI), Azure Verified Modules (AVM), resource export, and policy validation.
>
> Please migrate to the Azure MCP Server. This repository will not receive further updates, bug fixes, or security patches.

## 👉 Migrate to Azure MCP Server

| Resource | Link |
| --- | --- |
| Azure MCP Server README | <https://github.com/microsoft/mcp/blob/main/servers/Azure.Mcp.Server/README.md> |
| Documentation | <https://learn.microsoft.com/azure/developer/azure-mcp-server/> |
| Install in VS Code | [Azure MCP Server extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azure-mcp-server) |
| Releases | <https://github.com/microsoft/mcp/releases?q=Azure.Mcp.Server-> |
| Short link | <https://aka.ms/azmcp> |

### What replaces this project?

The Azure MCP Server's **Azure Terraform** tools support prompts such as:

- "Get the documentation for `azurerm_virtual_network`"
- "Show me the arguments for `azurerm_storage_account`"
- "Get AzAPI documentation for `Microsoft.Storage/storageAccounts`"
- "List all available Azure Verified Modules"
- "Export all resources in resource group `my-rg` to Terraform"
- "Validate Terraform files in `./my-terraform-folder` against Azure security policies"

For the full command reference, see [Azure MCP Commands](https://github.com/microsoft/mcp/blob/main/servers/Azure.Mcp.Server/docs/azmcp-commands.md).

### Quick install

```bash
# .NET tool
dotnet tool install Azure.Mcp

# npm
npm install @azure/mcp@latest

# pip
pip install msmcp-azure
```

See the [Azure MCP Server README](https://github.com/microsoft/mcp/blob/main/servers/Azure.Mcp.Server/README.md) for IDE extensions, Docker, and other setup options.

### Questions or feedback?

Open an issue at <https://github.com/microsoft/mcp/issues>.

---

## Related references

- [Conftest](https://www.conftest.dev/)
- [Terraform AzureRM Provider](https://registry.terraform.io/providers/hashicorp/azurerm/latest)
- [Terraform AzAPI Provider](https://registry.terraform.io/providers/Azure/azapi/latest)
- [Azure Verified Modules](https://aka.ms/avm)
- [aztfexport](https://github.com/Azure/aztfexport)
