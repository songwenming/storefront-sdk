#Get-STFWebReceiverCommunication
Get the WebReceiver communication settings
##Syntax
```
```
##Detailed Description
Get the WebReceiver communication settings.
##Related Commands
*[Set-STFWebReceiverCommunication](Set-STFWebReceiverCommunication)
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.ReceiverForWeb.WebReceiverService
Parameter WebReceiverService: A .NET class representing the configuration of a StoreFront Web Receiver service
##Return Values
###Communication
The .NET 'Citrix.StoreFront.Model.ReceiverForWeb.Communication' reference type
##Examples
###EXAMPLE 1 Get communication settings
```
Get-STFWebReceiverCommunication $webReceiver
```
REMARKS
Get the WebReceiver communication settings for /Citrix/StoreWeb.
OUTPUT
```
Timeout               : 00:03:00
Proxy                 : Enabled     : True
                        ProcessName : Fiddler
                        Port        : 8888
Loopback              : Off
LoopbackPortUsingHttp : 80
```