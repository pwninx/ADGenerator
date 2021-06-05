# Instructions

In order to generate a functional domain controller and active directory, the listed PowerShell scripts need to be executed in the following order:
- Invoke-ForestDeploy.ps1

```. .\Invoke-ForestDeploy.ps1```

```Invoke-ForestDeploy -DomainName <domain name>```

This will create you an AD domain controller. From here, you can run any other scripts but, remember your DC name.
