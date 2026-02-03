Commando Clave 
terraform plan -out=tfplan
terraform show -json tfplan > tfplan.json


----------------
Estado actual (check rápido)

✔ Service Principal creado
✔ Rol: Contributor
✔ Scope: Subscription
✔ Credenciales listas (JSON)
✔ Azure CLI funcionando
{
  "clientId": "64a98e53-02f0-4ed2-a746-a3f9391b244e",
  "clientSecret": "Azq8Q~zFRhvagXNzYwKg3Zn3tLIlGGUGhRudWbYP",
  "subscriptionId": "13e2334e-57b6-4d03-87a2-4f5c166a8130",
  "tenantId": "c64cd622-d66f-4b87-ad03-cbcf6f0dfdfc",
  "activeDirectoryEndpointUrl": "https://login.microsoftonline.com",
  "resourceManagerEndpointUrl": "https://management.azure.com/",
  "activeDirectoryGraphResourceId": "https://graph.windows.net/",
  "sqlManagementEndpointUrl": "https://management.core.windows.net:8443/",
  "galleryEndpointUrl": "https://gallery.azure.com/",
  "managementEndpointUrl": "https://management.core.windows.net/"
}
