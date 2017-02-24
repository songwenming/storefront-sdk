#Update-STFHmacKey
Update a named HMAC key stored in a web service.
##Syntax
```
```
##Detailed Description
Update an existing named HMAC key stored in a web service.
##Related Commands
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.StoreFrontWebService
Parameter WebService: The .NET 'Citrix.StoreFront.Model.StoreFrontWebService' reference type
###System.String
Parameter Name: The .NET 'System.String' reference type
###System.String
Parameter Key: The .NET 'System.String' reference type
##Return Values
##Examples
###EXAMPLE 1 Update the existing HMAC key named 'logoffTicket' in the specified Store service.
```
Update-STFHmacKey -WebService $store -Name 'logoffTicket' -Key '6UA064hC8Dx/5/s0irY3Vc+tYUh2d6TqPMjC4Qy1NTtCwusyA39mXJTXXPuLaLI7x2wDhFDrsk0rqSqzjlV5Pw=='
```
REMARKS
Update the existing HMAC key named 'logoffTicket' in the specified Store service.
