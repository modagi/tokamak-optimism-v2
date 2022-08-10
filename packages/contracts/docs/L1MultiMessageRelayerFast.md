# L1MultiMessageRelayerFast



> L1MultiMessageRelayerFast



*The L1 Multi-Message Relayer Fast contract is a gas efficiency optimization which enables the relayer to submit multiple messages in a single transaction to be relayed by the Fast L1 Cross Domain Message Sender. Compiler used: solc Runtime target: EVM*

## Methods

### batchRelayMessages

```solidity
function batchRelayMessages(L1MultiMessageRelayerFast.L2ToL1Message[] _messages, bytes32 _standardBridgeDepositHash, bytes32 _lpDepositHash) external nonpayable
```

Forwards multiple cross domain messages to the L1 Cross Domain Messenger Fast for relaying



#### Parameters

| Name | Type | Description |
|---|---|---|
| _messages | L1MultiMessageRelayerFast.L2ToL1Message[] | An array of L2 to L1 messages
| _standardBridgeDepositHash | bytes32 | current deposit hash of standard bridges
| _lpDepositHash | bytes32 | current deposit hash of LP1

### libAddressManager

```solidity
function libAddressManager() external view returns (contract Lib_AddressManager)
```






#### Returns

| Name | Type | Description |
|---|---|---|
| _0 | contract Lib_AddressManager | undefined

### resolve

```solidity
function resolve(string _name) external view returns (address)
```

Resolves the address associated with a given name.



#### Parameters

| Name | Type | Description |
|---|---|---|
| _name | string | Name to resolve an address for.

#### Returns

| Name | Type | Description |
|---|---|---|
| _0 | address | Address associated with the given name.




