# Fiori elements UI for RAP service

This RAP backend is meant to be consumed by a Fiori elements app generated from the service binding in SAP BTP ABAP Environment.

## Deployment flow

1. Create the RAP backend objects in ADT.
2. Create a service binding for `ZUI_TR_PUR_REQ_SRV`.
3. Use SAP Fiori tools to generate a List Report / Object Page app.
4. Connect the app to the bound OData service.

## Why no UI files here?

In RAP, the best-practice browser app is generated from the service binding and annotations. The UI is therefore described in docs instead of hardcoding a second implementation layer in this repo.
