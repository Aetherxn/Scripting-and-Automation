# Azure CLI Cheat Sheet

## Azure CLI Pattern

**Pattern**

```text
az <service> <verb>
```

**Memory trick:** **Azure → Service → Action**

Examples:

```bash
az vm create
az vm start
az vm stop

az group create
az group list
az group show
az group delete

az storage account create
az storage account list
```

### Common CLI Verbs

| Verb | Purpose |
|-------|---------|
| `create` | Create a resource |
| `show` | Show one resource |
| `list` | List multiple resources |
| `update` | Modify a resource |
| `delete` | Delete a resource |
| `start` | Start a resource |
| `stop` | Stop a resource |
| `restart` | Restart a resource |

---

# Example Comparison

| Task | Azure CLI | PowerShell |
|------|-----------|------------|
| Create VM | `az vm create` | `New-AzVM` |
| View VM | `az vm show` | `Get-AzVM` |
| List VMs | `az vm list` | `Get-AzVM` |
| Delete VM | `az vm delete` | `Remove-AzVM` |
| Start VM | `az vm start` | `Start-AzVM` |
| Stop VM | `az vm stop` | `Stop-AzVM` |
| Restart VM | `az vm restart` | `Restart-AzVM` |
