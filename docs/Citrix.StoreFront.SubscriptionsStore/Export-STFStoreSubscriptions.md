#Export-STFStoreSubscriptions
Export subscriptions from a given Store
##Syntax
```
Export-STFStoreSubscriptions [-UpdatedSince <DateTime>] [-StoreService] <StoreService> [-FilePath] <String> [-UpdatedSince <DateTime>] [-StoreService] <StoreService> [-FilePath] <String> [<CommonParameters>]
```
##Detailed Description
Export user subscriptions from a Store to a text file in csv format.
##Related Commands
*[Import-STFStoreSubscriptions](Import-STFStoreSubscriptions)
*[Restore-STFStoreSubscriptions](Restore-STFStoreSubscriptions)
##Parameters
|Name|Description|Required?|Pipeline Input|
###System.DateTime
Parameter UpdatedSince: The .NET 'System.DateTime' value type
###Citrix.StoreFront.Model.Store.StoreService
Parameter StoreService: A .NET class representing the configuration of a StoreFront Store service
###System.String
Parameter FilePath: The .NET 'System.String' reference type
###System.Int32
Parameter ChunkSize: The .NET 'System.Int32' value type
##Return Values
##Examples
###EXAMPLE 1 Export from Store by friendly name
```
Export-DSStoreSubscriptions -StoreName Store -FilePath "$env:userprofile\desktop\Export.txt"
$StopWatch.Stop()
Write-host "Total Elapsed Time: $($StopWatch.Elapsed.ToString())"
```
REMARKS
Exports the subscriptions from the Store named "Store" and outputs the total
time taken.
OUTPUT
```
```
###EXAMPLE 2 Export from Store by object
```
Export-STFStoreSubscriptions -Store $store -FilePath "$env:userprofile\desktop\Export.txt"
```
REMARKS
Exports all subscriptions from the only configured Store.
