#New-STFSamlIdPCertificate
Create a new signing certificate to be used by a SAML Identity Provider
##Syntax
```
```
##Detailed Description
Create a new signing certificate that is suitable to be used by a SAML Identity Provider.
##Related Commands
##Parameters
|Name|Description|Required?|Pipeline Input|
###System.String
Parameter SubjectName: The .NET 'System.String' reference type
###System.String
Parameter FilePath: The .NET 'System.String' reference type
###System.String
Parameter Password: The .NET 'System.String' reference type
##Return Values
###X509Certificate2
The .NET 'System.Security.Cryptography.X509Certificates.X509Certificate2' reference type
##Examples
###EXAMPLE 1 Create a new signing certificate to be used by a SAML Identity Provider.
```
```
REMARKS
Create a new signing certificate, with subject name 'Identity Provider Signing', to be used by a SAML Identity
Provider in the specified authentication service, exported to the specified path with the specified password
protecting the private key.
