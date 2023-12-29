To create the current setup in the cloud enter
```
az deployment group create \
  --name Sheper \
  --resource-group MC_sheper_sheper_westeurope \
  --template-uri "https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/quickstarts/microsoft.storage/storage-account-create/azuredeploy.json" 
```