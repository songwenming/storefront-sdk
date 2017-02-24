#Get-STFWebReceiverResourcesService
Get the WebReceiver Resources Service settings
##Syntax
```
```
##Detailed Description
Get the WebReceiver Resources Service settings.
##Related Commands
*[Set-STFWebReceiverResourcesService](Set-STFWebReceiverResourcesService)
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.ReceiverForWeb.WebReceiverService
Parameter WebReceiverService: A .NET class representing the configuration of a StoreFront Web Receiver service
##Return Values
###ResourcesService
The .NET 'Citrix.StoreFront.Model.ReceiverForWeb.ResourcesService' reference type
##Examples
###EXAMPLE 1 Get WebReceiver Resources settings
```
Get-STFWebReceiverResourcesService -WebReceiverService $receiver
```
REMARKS
Get the WebReceiver Resources service settings of the only configured WebReceiver.
OUTPUT
```
IcaFileCacheExpiry         : 90
IconSize                   : 128
ShowDesktopViewer          : True
```