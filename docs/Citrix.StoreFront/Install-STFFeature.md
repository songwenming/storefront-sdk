#Install-STFFeature
Install a StoreFront feature
##Syntax
```
Install-STFFeature [-PackageName] <String[]> [[-PassThru] <SwitchParameter>] [<CommonParameters>]
```
##Detailed Description
Install a StoreFront feature that is not installed by default as part of a new deployment or when joining an existing server group.
##Related Commands
*[Uninstall-STFFeature](Uninstall-STFFeature)
##Parameters
|Name|Description|Required?|Pipeline Input|
###System.String[]
Parameter FileLocation: The .NET 'System.String' reference type
###System.String[]
Parameter PackageName: The .NET 'System.String' reference type
###System.Management.Automation.SwitchParameter
Parameter PassThru: The .NET 'System.Management.Automation.SwitchParameter' value type
##Return Values
##Examples
###EXAMPLE 1 Install a custom feature
```
```
REMARKS
Installs a custom feature named CustomAuthentication.zip.
