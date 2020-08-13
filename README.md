# An EVM compatible smart contract for escrow services

## Blockchains supported:
Ethereum Virtual Machine(EVM) compatible blockchain


## Technologies used:
* Solidity

## How it works
 Contract to provide escrow services for transactions where transacting parties
 may not know/trust each other.
  
 1. The buyer sends Ether to this escrow contract
 2. The seller releases the agreed product/service upon getting notified by this cotract that
 the buyer has released the purchase price.
 3. The buyer confirms reciept of the product/service and releases funds held in this contract.
 4. The seller recieves the released funds
 5. Incase of a dispute arises (Should be before the buyer releases funds in 4) the buyer and seller identify an arbiter(escrow) to help in resolving a conflict incase
  the conflict is to be escaleted to another party.
 6. The arbiter deternines who is in the wrong and either refunds the buyer or releases the funds to the seller.
 7. The transaction is considered closed.

