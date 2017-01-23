#Set-STFPasswordManagerAccountSelfService
Sets Password Manager as the account self-service method
##Syntax
```
```
##Detailed Description
Sets the Password Manager as the account self-service method (Password Reset).
##Related Commands
*[Get-STFPasswordManagerAccountSelfService](Get-STFPasswordManagerAccountSelfService)
*[Get-STFAccountSelfService](Get-STFAccountSelfService)
*[Set-STFAccountSelfService](Set-STFAccountSelfService)
##Parameters
|Name|Description|Required?|Pipeline Input|
###Citrix.StoreFront.Model.Authentication.AuthenticationService
Parameter AuthenticationService: A .NET class representing the configuration of a StoreFront Authentication service
###System.Uri
Parameter PasswordManagerServiceUrl: The .NET 'System.Uri' reference type
##Return Values
##Examples
###EXAMPLE 1 Enable Password Manager
```
Set-STFAuthenticationServicePasswordManagerAccountSelfService -AuthenticationService $auth
```
REMARKS
Configure the single authentication service to use Password Manager for
account self-service.
