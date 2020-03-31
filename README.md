# iac-terraform-azure

Infrastructure as code with Terraform in Azure

## Links

[Quickstart: Create a complete Linux virtual machine infrastructure in Azure with Terraform](https://docs.microsoft.com/en-us/azure/terraform/terraform-create-complete-vm)

[Creating the application Client ID and Client Secret from Microsoft Azure portal](https://community.microfocus.com/t5/Identity-Manager-Tips/Creating-the-application-Client-ID-and-Client-Secret-from/ta-p/1776619)

[Azure Provider](https://www.terraform.io/docs/providers/azurerm/)

[Azure Provider: Authenticating using a Service Principal with a Client Secret](https://www.terraform.io/docs/providers/azurerm/guides/service_principal_client_secret.html)

## Where to find the values to subscription id, client id, secret and tenant id

SubscriptionId and TenantId belongs to your azure subscription.

ClientId and Client Secret are related to the application registered where you will be providing access[role] to your application to perform certain functionality for you.

When you will register any application in your Azure Active Directory you can have all the details, after creating it- ClientId, Secret, Subscription Id and Tenant Id.

See more details on doing it from [Azure Portal](https://community.microfocus.com/t5/Identity-Manager-Tips/Creating-the-application-Client-ID-and-Client-Secret-from/ta-p/1776619).