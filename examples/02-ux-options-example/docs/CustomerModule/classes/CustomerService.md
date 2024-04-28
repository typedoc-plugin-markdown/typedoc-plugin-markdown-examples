[typedoc-plugin-markdown-examples](../../README.md) • Docs

***

[Home](../../README.md) / [CustomerModule](../README.md) / CustomerService

# Class: CustomerService

Service for managing customers.

## Constructors

### new CustomerService()

```ts
new CustomerService(): CustomerService
```

#### Returns

[`CustomerService`](CustomerService.md)

## Properties

| Property | Modifier | Type | Default value |
| :------ | :------ | :------ | :------ |
| `customers` | `private` | [`CustomerAccount`](CustomerAccount.md)[] | `[]` |

## Methods

### addCustomer()

```ts
addCustomer(
   customer, 
   contactInfo, 
   billingInfo): CustomerAccount
```

Add a new customer.

#### Parameters

| Parameter | Type | Description |
| :------ | :------ | :------ |
| `customer` | [`Customer`](../interfaces/Customer.md) | The customer to be added. |
| `contactInfo` | [`CustomerContact`](../interfaces/CustomerContact.md) | The contact information for the customer. |
| `billingInfo` | [`CustomerBilling`](../interfaces/CustomerBilling.md) | The billing information for the customer. |

#### Returns

[`CustomerAccount`](CustomerAccount.md)

The added customer account.

#### Source

[customer.ts:153](https://github.com/tgreyuk/typedoc-plugin-markdown-examples/blob/f6ee18b4865e847a5ae81e3c3d7c2ce83ab384d7/examples/src/customer.ts#L153)

***

### getAllCustomers()

```ts
getAllCustomers(): CustomerAccount[]
```

Get all customer accounts.

#### Returns

[`CustomerAccount`](CustomerAccount.md)[]

An array of all customer accounts.

#### Source

[customer.ts:171](https://github.com/tgreyuk/typedoc-plugin-markdown-examples/blob/f6ee18b4865e847a5ae81e3c3d7c2ce83ab384d7/examples/src/customer.ts#L171)

***

### getCustomerById()

```ts
getCustomerById(customerId): undefined | CustomerAccount
```

Get a customer account by ID.

#### Parameters

| Parameter | Type | Description |
| :------ | :------ | :------ |
| `customerId` | `string` | The ID of the customer. |

#### Returns

`undefined` \| [`CustomerAccount`](CustomerAccount.md)

The customer account with the specified ID.

#### Source

[customer.ts:180](https://github.com/tgreyuk/typedoc-plugin-markdown-examples/blob/f6ee18b4865e847a5ae81e3c3d7c2ce83ab384d7/examples/src/customer.ts#L180)