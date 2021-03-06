

# Hierarchy

**Near**

# Constructors

<a id="constructor"></a>

##  constructor

⊕ **new Near**(config: *`any`*): [Near](_near_.near.md)

*Defined in [near.ts:14](https://github.com/nearprotocol/nearlib/blob/4fd2642/src.ts/near.ts#L14)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| config | `any` |

**Returns:** [Near](_near_.near.md)

___

# Properties

<a id="accountcreator"></a>

##  accountCreator

**● accountCreator**: *[AccountCreator](_account_creator_.accountcreator.md)*

*Defined in [near.ts:14](https://github.com/nearprotocol/nearlib/blob/4fd2642/src.ts/near.ts#L14)*

___
<a id="config"></a>

##  config

**● config**: *`any`*

*Defined in [near.ts:12](https://github.com/nearprotocol/nearlib/blob/4fd2642/src.ts/near.ts#L12)*

___
<a id="connection"></a>

##  connection

**● connection**: *[Connection](_connection_.connection.md)*

*Defined in [near.ts:13](https://github.com/nearprotocol/nearlib/blob/4fd2642/src.ts/near.ts#L13)*

___

# Methods

<a id="account"></a>

##  account

▸ **account**(accountId: *`string`*): `Promise`<[Account](_account_.account.md)>

*Defined in [near.ts:33](https://github.com/nearprotocol/nearlib/blob/4fd2642/src.ts/near.ts#L33)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| accountId | `string` |

**Returns:** `Promise`<[Account](_account_.account.md)>

___
<a id="createaccount"></a>

##  createAccount

▸ **createAccount**(accountId: *`string`*, publicKey: *[PublicKey](_utils_key_pair_.publickey.md)*): `Promise`<[Account](_account_.account.md)>

*Defined in [near.ts:39](https://github.com/nearprotocol/nearlib/blob/4fd2642/src.ts/near.ts#L39)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| accountId | `string` |
| publicKey | [PublicKey](_utils_key_pair_.publickey.md) |

**Returns:** `Promise`<[Account](_account_.account.md)>

___
<a id="loadcontract"></a>

##  loadContract

▸ **loadContract**(contractId: *`string`*, options: *`object`*): `Promise`<[Contract](_contract_.contract.md)>

*Defined in [near.ts:52](https://github.com/nearprotocol/nearlib/blob/4fd2642/src.ts/near.ts#L52)*

Backwards compatibility method. Use `new nearlib.Contract(yourAccount, contractId, { viewMethods, changeMethods })` instead.

**Parameters:**

**contractId: `string`**

**options: `object`**

| Name | Type |
| ------ | ------ |
| changeMethods | `string`[] |
| sender | `string` |
| viewMethods | `string`[] |

**Returns:** `Promise`<[Contract](_contract_.contract.md)>

___
<a id="sendtokens"></a>

##  sendTokens

▸ **sendTokens**(amount: *`BN`*, originator: *`string`*, receiver: *`string`*): `Promise`<`string`>

*Defined in [near.ts:64](https://github.com/nearprotocol/nearlib/blob/4fd2642/src.ts/near.ts#L64)*

Backwards compatibility method. Use `yourAccount.sendMoney` instead.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| amount | `BN` |  \- |
| originator | `string` |  \- |
| receiver | `string` |   |

**Returns:** `Promise`<`string`>

___

