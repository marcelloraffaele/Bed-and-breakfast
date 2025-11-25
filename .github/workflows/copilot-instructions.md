# GitHub Actions

## Secret available
The following secrets are available for use in this workflow:

| Secret name | Secret value |
|-------------|--------------|
| AZURE_CREDENTIALS | The entire JSON output from the az ad sp create-for-rbac command. |
| service_principal | The value of <clientId>. |
| service_principal_password | The value of <clientSecret>. |
| subscription | The value of <subscriptionId>. |
| tenant | The value of <tenantId>. |
| registry | The name of your registry. |
| repository | azuredocs |
| resource_group | The name of your resource group. |
| cluster_name | The name of your cluster. |