#Add-STFDesktopApplianceService
Create a new Desktop Appliance service
##Syntax
```
```
##Detailed Description
Create a new Desktop Appliance site that provides a user experience that is similar to logging on to a local desktop.
##Related Commands
*[Set-STFDesktopApplianceService](Set-STFDesktopApplianceService)
*[Remove-STFDesktopApplianceService](Remove-STFDesktopApplianceService)
##Parameters
|Name|Description|Required?|Pipeline Input|
###System.String
Parameter VirtualPath: The .NET 'System.String' reference type
###System.Int64
Parameter SiteId: The .NET 'System.Int64' value type
###Citrix.StoreFront.Model.Store.StoreService
Parameter StoreService: A .NET class representing the configuration of a StoreFront Store service
###System.Management.Automation.SwitchParameter
Parameter MultiDesktop: The .NET 'System.Management.Automation.SwitchParameter' value type
###System.Management.Automation.SwitchParameter
Parameter EnableExplicit: The .NET 'System.Management.Automation.SwitchParameter' value type
###System.Management.Automation.SwitchParameter
Parameter EnableSmartCard: The .NET 'System.Management.Automation.SwitchParameter' value type
###System.Management.Automation.SwitchParameter
Parameter EnableEmbeddedSmartcardSSO: The .NET 'System.Management.Automation.SwitchParameter' value type
###System.Management.Automation.SwitchParameter
Parameter UseHttps: The .NET 'System.Management.Automation.SwitchParameter' value type
###System.String
Parameter FriendlyName: The .NET 'System.String' reference type
##Return Values
###DesktopApplianceService
A .NET class representing the configuration of a StoreFront Desktop Appliance service
##Examples
###EXAMPLE 1 Create new Desktop Appliance service
```
Add-STFDesktopApplianceService -VirtualPath $desktopApplianceVirtualPath -StoreService $storeService -MultiDesktop -EnableExplicit
```
REMARKS
Create a new Desktop Appliance service supporting multi desktops and explicit authentication using the only Store
service.
