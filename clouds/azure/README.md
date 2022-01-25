
## Azure-related penetration testing scripts, tools and Cheatsheets

- [**`Azure Roles`**](https://github.com/mgeeky/Penetration-Testing-Tools/blob/master/clouds/azure/Azure%20Roles/README.md) - All Azure RBAC and Azure AD Role Definitions, along with their permissions associated listed in a handy markdown report.

- **`AzureRT`** - Powershell module implementing various cmdlets to interact with Azure and Azure AD from an offensive perspective. Helpful utilities dealing with access token based authentication, easily switching from `Az` to `AzureAD` and `az cli` interfaces, easy to use pre-made attacks such as Runbook-based command execution and more.

  Authentication & Token mechanics:

  - *`Get-ARTWhoami`*
  - *`Connect-ART`*
  - *`Connect-ARTAD`*
  - *`Connect-ARTADServicePrincipal`*
  - *`Get-ARTAccessTokenAzCli`*
  - *`Get-ARTAccessTokenAz`*
  - *`Get-ARTAccessTokenAzureAD`* 
  - *`Parse-JWTtokenRT`* 
  - *`Remove-ARTServicePrincipalKey`*

  Recon and Situational Awareness:

  - *`Get-ARTAccess`*
  - *`Get-ARTADAccess`*
  - *`Get-ARTDangerousPermissions`*
  - *`Get-ARTResource`*
  - *`Get-ARTRolePermissions`*
  - *`Get-ARTADRolePermissions`*
  - *`Get-ARTRoleAssignment`*
  - *`Get-ARTKeyVaultSecrets`*
  - *`Get-ARTAutomationRunbookCode`*
  - *`Get-ARTAzureVMPublicIP`*

  Privilege Escalation:

  - *`Add-ARTUserToGroup`*
  - *`Add-ARTUserToRole`*
  - *`Add-ARTADAppSecret`*

  Lateral Movement:

  - *`Invoke-ARTAutomationRunbook`*
  - *`Invoke-ARTRunCommand`*

  Misc:

  - *`Get-ARTUserId`*
  - *`Parse-JWTtokenRT`*
  - *`Invoke-ARTGETRequest`*