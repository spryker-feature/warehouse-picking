# Spryker Feature: Warehouse picking

The Fulfillment App's Warehouse picking feature enhances order efficiency by updating to a picking list system, enabling the division of complex orders into singular pick lists. It enables warehouse product assignment at checkout and warehouse picking process. Enhanced by a robust back-end API, the feature offers improved performance and scalability.

## Installation

```
composer require spryker-feature/warehouse-picking
```

## Recommended feature dependencies
- [spryker-feature/spryker-core](https://github.com/spryker-feature/spryker-core)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [PickingListExtension ^1.0.0](https://github.com/spryker/picking-list-extension) (Extension)
- [PickingListsBackendApi ^1.0.0](https://github.com/spryker/picking-lists-backend-api) (Glue Backend)
- [PickingListsBackendApiExtension ^1.0.0](https://github.com/spryker/picking-lists-backend-api-extension) (Extension)
- [PickingListsUsersBackendApi ^1.0.0](https://github.com/spryker/picking-lists-users-backend-api) (Glue Backend)
- [PickingListsWarehousesBackendApi ^1.0.0](https://github.com/spryker/picking-lists-warehouses-backend-api) (Glue Backend)
