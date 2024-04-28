[typedoc-plugin-markdown-examples](../../README.md) • [Readme](../../README.md) \| Docs

***

[typedoc-plugin-markdown-examples](../../modules.md) / [ShippingModule](../README.md) / ShippingService

# Class: ShippingService

Service for managing shipping records.
Provides methods to handle the logistics of order shipments, including recording and tracking shipments.

## Constructors

### new ShippingService()

> **new ShippingService**(): [`ShippingService`](ShippingService.md)

#### Returns

[`ShippingService`](ShippingService.md)

## Properties

### shipments

> `private` **shipments**: [`ShippingRecord`](../interfaces/ShippingRecord.md)[] = `[]`

Stores all shipment records. This array acts as a database to keep track of all shipments handled by the service.

#### Source

[shipping.ts:42](https://github.com/tgreyuk/typedoc-plugin-markdown-examples/blob/f6ee18b4865e847a5ae81e3c3d7c2ce83ab384d7/examples/src/shipping.ts#L42)

## Methods

### getAllShipments()

> **getAllShipments**(): [`ShippingRecord`](../interfaces/ShippingRecord.md)[]

Retrieves all shipping records managed by the service.
Useful for tracking, auditing, and providing customers with updates on their shipment statuses.

#### Returns

[`ShippingRecord`](../interfaces/ShippingRecord.md)[]

An array of all shipping records.

#### Source

[shipping.ts:60](https://github.com/tgreyuk/typedoc-plugin-markdown-examples/blob/f6ee18b4865e847a5ae81e3c3d7c2ce83ab384d7/examples/src/shipping.ts#L60)

***

### shipOrder()

> **shipOrder**(`shipment`): [`ShippingRecord`](../interfaces/ShippingRecord.md)

Ships an order by creating a shipping record and adding it to the list of shipments.
This method simulates the action of shipping an order in a real-world scenario.

#### Parameters

• **shipment**: [`ShippingRecord`](../interfaces/ShippingRecord.md)

The shipment record to be added.

#### Returns

[`ShippingRecord`](../interfaces/ShippingRecord.md)

The shipment record that was added to the shipments list.

#### Source

[shipping.ts:50](https://github.com/tgreyuk/typedoc-plugin-markdown-examples/blob/f6ee18b4865e847a5ae81e3c3d7c2ce83ab384d7/examples/src/shipping.ts#L50)