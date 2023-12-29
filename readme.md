To create the current setup in the cloud enter
```
az deployment group create \
  --name Sheper \
  --resource-group MC_sheper_sheper_westeurope \
  --template-uri "https://github.com/sheper-notes/Azure-Deployment/blob/18d8335b712f6a4027c742d3b871604a5e05516e/Template.json" 
```