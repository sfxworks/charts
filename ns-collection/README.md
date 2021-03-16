ns-collection
=============
Namespace creator and collection

Current chart version is `0.1.0`





## Chart Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| imageCredentials.email | string | `"someone@host.com"` |  |
| imageCredentials.password | string | `"sillyness"` |  |
| imageCredentials.registry | string | `"quay.io"` | Pull secret email |
| imageCredentials.username | string | `"someone"` |  |
| limitrange.limit.cpu | int | `250` | The maximum amount of cpu a container can use. |
| limitrange.limit.memory | int | `256` | The maximum amount of memory a container can use. |
| limitrange.request.cpu | int | `100` | The minimum amount of memory a container can request. New containers will default to this value. |
| limitrange.request.memory | int | `128` |  |
| namespace | string | `"small-non-prod-ns"` | The namespace to create |
| quota.limit.cpu | int | `1250` | The limit for the total sum of CPU to be used in mCPU for the namespace. |
| quota.limit.memory | int | `1280` | The limit for the total sum of memory to be used in Mi for the namespace. |
| quota.limit.pods | int | `10` | The limit for the total sum of pods that can be created for the namespace.. |
| quota.limit.services | int | `5` | The limit for the total sum of services that can be created for the namespace. |
| quota.request.cpu | int | `500` | The limit for the total sum of CPU request in mCPU for the namespace. |
| quota.request.memory | int | `640` | The limit for the tototaltoal sum of memory request in Mi for the namespace. |
