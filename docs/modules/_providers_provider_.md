

# Index

### Enumerations

* [FinalTransactionStatus](../enums/_providers_provider_.finaltransactionstatus.md)

### Classes

* [Provider](../classes/_providers_provider_.provider.md)

### Type aliases

* [FinalTransactionResult](_providers_provider_.md#finaltransactionresult)
* [TransactionLog](_providers_provider_.md#transactionlog)

### Functions

* [getTransactionLastResult](_providers_provider_.md#gettransactionlastresult)

---

# Type aliases

<a id="finaltransactionresult"></a>

##  FinalTransactionResult

**Ƭ FinalTransactionResult**: *`object`*

*Defined in [providers/provider.ts:20](https://github.com/nearprotocol/nearlib/blob/b1675ba/src.ts/providers/provider.ts#L20)*

#### Type declaration

 logs: [TransactionLog](_providers_provider_.md#transactionlog)[]

 status: [FinalTransactionStatus](../enums/_providers_provider_.finaltransactionstatus.md)

___
<a id="transactionlog"></a>

##  TransactionLog

**Ƭ TransactionLog**: *`object`*

*Defined in [providers/provider.ts:13](https://github.com/nearprotocol/nearlib/blob/b1675ba/src.ts/providers/provider.ts#L13)*

#### Type declaration

 hash: `string`

 lines: `Array`<`string`>

 receipts: `Array`<`number`[]>

`Optional`  result: `Uint8Array`

___

# Functions

<a id="gettransactionlastresult"></a>

##  getTransactionLastResult

▸ **getTransactionLastResult**(txResult: *[FinalTransactionResult](_providers_provider_.md#finaltransactionresult)*): `any`

*Defined in [providers/provider.ts:32](https://github.com/nearprotocol/nearlib/blob/b1675ba/src.ts/providers/provider.ts#L32)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| txResult | [FinalTransactionResult](_providers_provider_.md#finaltransactionresult) |

**Returns:** `any`

___
