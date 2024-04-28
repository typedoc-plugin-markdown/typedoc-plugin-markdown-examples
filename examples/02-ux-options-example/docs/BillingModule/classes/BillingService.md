[typedoc-plugin-markdown-examples](../../README.md) • Docs

***

[Home](../../README.md) / [BillingModule](../README.md) / BillingService

# Class: BillingService

Service for managing billing transactions.
Provides functionality to process and retrieve billing transactions.

## Constructors

### new BillingService()

```ts
new BillingService(): BillingService
```

#### Returns

[`BillingService`](BillingService.md)

## Properties

| Property | Modifier | Type | Default value | Description |
| :------ | :------ | :------ | :------ | :------ |
| `transactions` | `private` | [`BillingTransaction`](../interfaces/BillingTransaction.md)[] | `[]` | Holds all processed transactions within the service. |

## Methods

### getAllTransactions()

```ts
getAllTransactions(): BillingTransaction[]
```

Retrieves all the billing transactions that have been processed.
Useful for audits and general transaction management.

#### Returns

[`BillingTransaction`](../interfaces/BillingTransaction.md)[]

An array of all billing transactions.

#### Source

[billing.ts:126](https://github.com/tgreyuk/typedoc-plugin-markdown-examples/blob/f6ee18b4865e847a5ae81e3c3d7c2ce83ab384d7/examples/src/billing.ts#L126)

***

### processTransaction()

```ts
processTransaction(transaction): BillingTransaction
```

Processes a billing transaction by adding it to the list of transactions.
This simulates the transaction execution and storage in a production environment.

#### Parameters

| Parameter | Type | Description |
| :------ | :------ | :------ |
| `transaction` | [`BillingTransaction`](../interfaces/BillingTransaction.md) | The billing transaction to be processed. |

#### Returns

[`BillingTransaction`](../interfaces/BillingTransaction.md)

The processed billing transaction, now stored in the service.

#### Source

[billing.ts:116](https://github.com/tgreyuk/typedoc-plugin-markdown-examples/blob/f6ee18b4865e847a5ae81e3c3d7c2ce83ab384d7/examples/src/billing.ts#L116)