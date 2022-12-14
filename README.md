## AzureStudy
+ [デプロイ ボタンを使用して GitHub リポジトリからテンプレートをデプロイする](https://docs.microsoft.com/ja-jp/azure/azure-resource-manager/templates/deploy-to-azure-button)

```Powershell
$url = "https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/quickstarts/microsoft.storage/storage-account-create/azuredeploy.json"
[uri]::EscapeDataString($url)
```


+ AzureStudy-ARMtemplate.json

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmattu0119%2FAzureStudy%2Fmain%2FAzureStudy-ARMtemplate.json)

+ AzureStudy-ARMtemplate_autoshutdown.json

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmattu0119%2FAzureStudy%2Fmain%2FAzureStudy-ARMtemplate_autoshutdown.json)

+ asc-regulatoryCompliance-send-notification-email

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https%3A%2F%2Fraw.githubusercontent.com%2Fmattu0119%2FAzureStudy%2Fmain%2Fasc-regulatoryCompliance-send-notification-email.json)


## eicar テストファイルのダウンロード
Invoke-WebRequest -uri https://secure.eicar.org/eicar.com -outfile c:\eicar.com

```Powershell
echo "X5O!P%@AP[4\PZX54(P^)7CC)7}$EICAR-STANDARD-ANTIVIRUS-TEST-FILE!$H+H*" > c:\test.txt
```
