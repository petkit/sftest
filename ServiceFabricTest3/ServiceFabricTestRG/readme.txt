Access to the cluster is secured by a certificate stored in Azure Key Vault. 

The certificate must exist before the template is deployed. For more information about creating the certificate please see: 
https://azure.microsoft.com/documentation/articles/service-fabric-cluster-security/


KeyVaultRgName: sftest_keys_rg
KeyVaultName: sftestkeys
key thumbprint: BE4B689BF2939F7495FDA98A0AF9B43BD15ECCD0

User: Test1234
Password: SfTest1234
CertDNSName: clusterzzcshmgfcdjcu.westeurope.cloudapp.azure.com