#Set-STFWebReceiverPluginAssistant
Set the WebReceiver Plug-in Assistant options
##Syntax
```
```
##Detailed Description
Set the WebReceiver Plug-in Assistant client options.
##Related Commands
*[Get-STFWebReceiverPluginAssistant](Get-STFWebReceiverPluginAssistant)
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.ReceiverForWeb.WebReceiverService
Parameter WebReceiverService: A .NET class representing the configuration of a StoreFront Web Receiver service
###System.Boolean
Parameter Enabled: The .NET 'System.Boolean' value type
###System.Boolean
Parameter UpgradeAtLogin: The .NET 'System.Boolean' value type
###System.String
Parameter Win32Path: The .NET 'System.String' reference type
###System.String
Parameter MacOSPath: The .NET 'System.String' reference type
###System.String
Parameter MacOSMinimumSupportedVersion: The .NET 'System.String' reference type
###Citrix.StoreFront.Model.ReceiverForWeb.Html5ClientMode
Parameter Html5Enabled: The .NET 'Citrix.StoreFront.Model.ReceiverForWeb.Html5ClientMode' value type
###System.String
Parameter Html5Platforms: The .NET 'System.String' reference type
###System.String
Parameter Html5Preferences: The .NET 'System.String' reference type
###System.Boolean
Parameter Html5SingleTabLaunch: The .NET 'System.Boolean' value type
###System.String
Parameter Html5ChromeAppOrigins: The .NET 'System.String' reference type
###System.String
Parameter Html5ChromeAppPreferences: The .NET 'System.String' reference type
###System.Boolean
Parameter ProtocolHandlerEnabled: The .NET 'System.Boolean' value type
###System.String
Parameter ProtocolHandlerPlatforms: The .NET 'System.String' reference type
###System.Boolean
Parameter ProtocolHandlerSkipDoubleHopCheckWhenDisabled: The .NET 'System.Boolean' value type
##Return Values
##Examples
###EXAMPLE 1 Set WebReceiver Plug-in Assistant options
```
Set-STFWebReceiverPluginAssistant -WebReceiverService $receiver -UpgradeAtLogin $true
```
REMARKS
Set the WebReceiver Plug-in Assistant client options to upgrade Receiver at
login.
