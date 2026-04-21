# APIM Workshop — Public Materials

Public reference materials for the Azure API Management (APIM) workshop, covering APIM policy configuration and workload identity federation for Azure and GCP.

## Contents

### `openapi/`
OpenAPI specifications used as APIM API definitions.

### `policies/`
Azure APIM policy XML files:

- `service-policy.xml` — top-level service policy
- `generate-content.xml` — policy for the LLM generate content operation
- `stream-generate-content.xml` — policy for the LLM streaming generate content operation
- `fragments/gcp-wif-token-exchange.xml` — reusable policy fragment for GCP Workload Identity Federation token exchange

## Topics Covered

- Azure API Management policy authoring
- Routing and transformation policies
- Workload Identity Federation (WIF) for Azure and GCP
- Secure service-to-service authentication without long-lived credentials
