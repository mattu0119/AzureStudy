# AzureStudy
+ [デプロイ ボタンを使用して GitHub リポジトリからテンプレートをデプロイする](https://docs.microsoft.com/ja-jp/azure/azure-resource-manager/templates/deploy-to-azure-button)

```Powershell
$url = "https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/quickstarts/microsoft.storage/storage-account-create/azuredeploy.json"
[uri]::EscapeDataString($url)
```


  [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmattu0119%2FAzureStudy%2Fmain%2FAzureStudy-ARMtemplate.json)

    [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmattu0119%2FAzureStudy%2Fmain%2FAzureStudy-ARMtemplate.json)