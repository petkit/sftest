Access to the cluster is secured by a certificate stored in Azure Key Vault. 

The certificate must exist before the template is deployed. For more information about creating the certificate please see: 
https://azure.microsoft.com/documentation/articles/service-fabric-cluster-security/


KeyVaultRgName: sftest_keys_rg
KeyVaultName: sftestkeys

User: Test1234
Password: SfTest1234

Name  : CertificateThumbprint
Value : B333A014726CBB34A6D75D579332B129EE371615

Name  : SourceVault
Value : /subscriptions/a1e94c46-5bce-4161-a1bf-c8a784f2b489/resourceGroups/sftest_keys_rg/providers/Microsoft.KeyVault/vaults/sftestkeys

Name  : CertificateURL
Value : https://sftestkeys.vault.azure.net:443/secrets/sftestcert/90447bc98d7e4ffba65ce383d5fd488e
