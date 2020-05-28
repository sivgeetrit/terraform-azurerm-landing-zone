## Requirements

| Name | Version |
|------|---------|
| terraform | >= 0.12 |
| azurerm | >= 2.0.0 |

## Providers

No provider.

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| access\_key | access key for the storage account that contains the Remote Backend | `string` | n/a | yes |
| app\_id | The client ID for the Service Principal | `string` | n/a | yes |
| client\_secret | The secret for the Service Principal authentication | `string` | n/a | yes |
| environment | Development environment for resource; prod, non-prod, shared-services | `string` | n/a | yes |
| object\_id | The object ID for the Service Principal | `string` | n/a | yes |
| region | Geographic region resource will be deployed into | `string` | n/a | yes |
| shared\_services\_subscription\_id | subscription id of shared-services env | `string` | n/a | yes |
| state\_key | Key for the state file of the solution, e.g. pre-prod.tfstate | `string` | n/a | yes |
| storage\_account\_name | Storage account that contains Remote Backend, e.g. terraformdata24321 | `string` | n/a | yes |
| subscription\_id | The Id of the Subscription that should contain the created resources | `string` | n/a | yes |
| tags | A map of tags to add to all resources | `map` | `{}` | no |
| tenant\_id | The tenant ID for the Service Principal | `string` | n/a | yes |

## Outputs

No output.
