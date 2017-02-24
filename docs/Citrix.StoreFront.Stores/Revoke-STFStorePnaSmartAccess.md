#Revoke-STFStorePnaSmartAccess
Revoke a server PNA SmartAccess
##Syntax
```
Revoke-STFStorePnaSmartAccess [-CertificateThumbprint] <String> [-StoreService] <StoreService> [<CommonParameters>]
Revoke-STFStorePnaSmartAccess [-AccessConditionsTrust] <AccessConditionsTrust> [-StoreService] <StoreService> [<CommonParameters>]
Revoke-STFStorePnaSmartAccess [-All] <SwitchParameter> [-StoreService] <StoreService> [<CommonParameters>]
```
##Detailed Description
Removes the certificate to be used for the purpose of verifying signed data supplied in PNA SmartAccess headers. The server and certificate will no longer be able to use SmartAccess.
##Related Commands
*[Grant-STFStorePnaSmartAccess](Grant-STFStorePnaSmartAccess)
*[Get-STFStorePnaSmartAccess](Get-STFStorePnaSmartAccess)
*[Set-STFStorePnaSmartAccess](Set-STFStorePnaSmartAccess)
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.Store.StoreService
Parameter StoreService: A .NET class representing the configuration of a StoreFront Store service
###System.String
Parameter ServerName: The .NET 'System.String' reference type
###System.String
Parameter CertificateThumbprint: The .NET 'System.String' reference type
###Citrix.StoreFront.Model.Store.AccessConditionsTrust
Parameter AccessConditionsTrust: The .NET 'Citrix.StoreFront.Model.Store.AccessConditionsTrust' reference type
###System.Management.Automation.SwitchParameter
Parameter All: The .NET 'System.Management.Automation.SwitchParameter' value type
##Return Values
##Notes
Verifying the signed data of a PNA SmartAccess header ensures it was provided by a trusted source.
##Examples
###EXAMPLE 1 Revoke SmartAccess by server name
```
Revoke-STFStorePnaSmartAccess -StoreService $store -ServerName "XenMobile"
```
REMARKS
Revoke the server trust so it can no longer use SmartAccess.

```
Revoke-STFStorePnaSmartAccess -StoreService $store -CertificateThumbprint "DFD2952373DAF788B494A3BB4AD45108760D5156"
```
REMARKS
Revoke the server trust using the specified certificate so it can no longer use SmartAccess.
