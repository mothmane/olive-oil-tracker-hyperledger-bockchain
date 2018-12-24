# Basic Sample Olive Oil Trade tracing  Block chain 

> This is Tracing Olive Oil history created by  Hyperledger Composer, it  demonstrates the core functionality of Hyperledger Composer by tracing the life of Olive Oil.

This business network defines:

**Participant**
`Organisation`  Grower or Buyer

**Asset**
`OliveOil`

**Transaction**
`SellOilTransaction`

**Event**
`SellOilEvent`

OliveOil are owned by a Organisation can be a grower or buyer , and the owener property on a OliveOil can be modified by submitting a SellOilTransaction. The SellOilTransaction emits a SellOilEvent that notifies applications of the old and new owner for each modified OliveOil.

