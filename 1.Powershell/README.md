# Azure PowerShell Cheat Sheet

## Azure PowerShell Pattern

**Pattern**

```text
<Verb>-Az<Service>
```

**Memory trick:** **Action → Azure Service**

Examples:

```powershell
New-AzVM
Get-AzVM
Start-AzVM
Stop-AzVM
Restart-AzVM
Remove-AzVM

New-AzResourceGroup
Get-AzResourceGroup
Remove-AzResourceGroup

New-AzStorageAccount
Get-AzStorageAccount
Remove-AzStorageAccount
```

### Common PowerShell Verbs

| Verb | Purpose |
|------|---------|
| `Get` | Read/View |
| `New` | Create |
| `Set` | Change configuration |
| `Remove` | Delete |
| `Start` | Start |
| `Stop` | Stop |
| `Restart` | Restart |
| `Update` | Update |
| `Test` | Validate/Check |
| `Invoke` | Execute |

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
