# CatalogService

Product data storage. Provides API for accessing shop product data.

Owner|Tier|Status|Contexts
---|---|---|---
CheckoutTeam|Tier1|Prod|Web,Catalog

##### Environments

Production:

- URL: https://...
- AWS account: 1234567890
- Logs: https://...
- Dashboard: https://...

Staging:

- URL: https://...
- AWS account: 1234567890
- Logs: https://...
- Dashboard: https://... 

##### Tech

- Golang 13.x: implementation
- AWS ECS: execution env
- AWS ALB: request routing
- AWS SNS: domain events transport

