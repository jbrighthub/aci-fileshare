# aci-fileshare

az group create --name upk --location westeurope

Deploy with YAML template
az container create --resource-group upk --file deployments.yaml
