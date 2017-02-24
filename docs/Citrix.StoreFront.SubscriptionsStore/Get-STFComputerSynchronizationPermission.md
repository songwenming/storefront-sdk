#Get-STFComputerSynchronizationPermission
Get the computers with permission to synchronize
##Syntax
```
```
##Detailed Description
Get the Active Directory computer accounts with permission to synchronize subscriptions from this server.
##Related Commands
*[Add-STFSubscriptionSynchronizationSource](Add-STFSubscriptionSynchronizationSource)
*[Clear-STFSubscriptionSynchronizationSource](Clear-STFSubscriptionSynchronizationSource)
##Input Type
##Return Values
###String
The .NET 'System.String' reference type
##Examples
###EXAMPLE 1 Get permitted synchronization accounts
```
```
REMARKS
Get the Active Directory accounts of the StoreFront servers with permissions to synchronize.
OUTPUT
```
SFDomain\SFEUServer2
SFDomain\SFUSServer1
SFDomain\SFUSServer2
```