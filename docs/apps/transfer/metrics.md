<!--
order: 6
-->

# Metrics

The IBC transfer application module exposes the following set of [metrics](https://github.com/cosmos/cosmos-sdk/blob/main/docs/develop/advanced/09-telemetry.md).

| Metric                          | Description                                                                               | Unit            | Type    |
|:--------------------------------|:------------------------------------------------------------------------------------------|:----------------|:--------|
| `tx_msg_ibc_transfer`           | The total amount of tokens transferred via IBC in a `MsgTransfer` (source or sink chain)  | token           | gauge   |
| `ibc_transfer_packet_receive`   | The total amount of tokens received in a `FungibleTokenPacketData` (source or sink chain) | token           | gauge   |
| `ibc_transfer_send`             | Total number of IBC transfers sent from a chain (source or sink)                          | transfer        | counter |
| `ibc_transfer_receive`          | Total number of IBC transfers received to a chain (source or sink)                        | transfer        | counter |
