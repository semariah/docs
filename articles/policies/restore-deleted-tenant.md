---
description: This page details Auth0's deleted tenant restoration policy.
topics:
    - auth0-policies
    - tenants
    - tenant-restoration
contentType:
  - reference
useCase:
  - support
---

# Tenant Restoration Policy

The following policy governs requests for restoration of Auth0 tenants that were previously deleted.

::: note
If you are considering deleting your tenant, please see our [Resetting/Deleting Tenant](/tutorials/delete-reset-tenant) page for alternative options.
:::

A customer may request a tenant restoration if the tenant was deleted by human error and restoration is critical for the continuity of customer's operations. Please note that before deleting a tenant, from the Auth0 Dashboard, a warning explains that this cannot be undone. However, in some cases we might opt for support this kind of request.

## Considerations

* We support tenant restoration for all paying customers in our Cloud service.

* Tenant restoration is not supported for Appliance customers.

* Tenant restoration is not supported for non-paying customers.

* The restoration can take up to seven days, for paying customers.

* Tenant restoration is only possible if the request is made before 10 days have passed from the date the tenant was deleted.

* Warning: It's possible that not all data can be successfully recovered.

## How to request

* Customers must file a tenant restoration request in writing, via the [Auth0 support center](${env.DOMAIN_URL_SUPPORT}) or via email.

* Please specify the name that the deleted tenant had and the region where it belonged.

* A member of the Auth0 team will respond your request.
