#Set-STFWebReceiverDiscoveryService
Set the WebReceiver Discovery Service options
##Syntax
```
```
##Detailed Description
Set the WebReceiver Discovery Service options.
##Related Commands
*[Get-STFWebReceiverDiscoveryService](Get-STFWebReceiverDiscoveryService)
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.ReceiverForWeb.WebReceiverService
Parameter WebReceiverService: A .NET class representing the configuration of a StoreFront Web Receiver service
###System.Boolean
Parameter RunDiscoveryAtStart: The .NET 'System.Boolean' value type
##Return Values
##Examples
###EXAMPLE 1 Set WebReceiver Discovery service options
```
Set-STFWebReceiverAuthenticationManager -WebReceiverService $receiver -RunDiscoveryAtStart $false
```
REMARKS
Do not run discovery when the WebReceiver Application Pool starts.
