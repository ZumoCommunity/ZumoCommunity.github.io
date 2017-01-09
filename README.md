# ZumoCommunity.github.io

## Shared infrastructure

* Azure App Service Plan (aka Web Farm) to host all microservices as Web Apps, Mobile Apps, Function Apps, etc.
* Azure Storage Account for storing all static unstructured content
* Azure Cdn Profile and Endpoint to deliver static unstructured content from storage account
* Azure Service Bus for introducing publisher-subscriber communication pattern between microservices
