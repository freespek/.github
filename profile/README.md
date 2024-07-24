# FreeSpek

We are a loose collective of Formal Methods & Security Researchers in the blockchain space.

This org hosts current & past projects that we've worked on, including:

## Solarkraft

Solarkraft is a tool for runtime monitoring of [Soroban smart contracts][Soroban]. It tests whether a smart contract conforms to its specification during contract development, testing, and after contract deployment on the [Stellar blockchain][Stellar]. The contract specification is written as an ensemble of [TLA+][] specifications, each capturing a property of the contract’s expected behavior. We use the [Apalache][] model checker as a backend to verify the observed contract behavior.

[learn more »](https://github.com/freespek/solarkraft)

## Exploring Automatic Model-Checking of the Ethereum specification

Together with Consensys R&D, this exploratory research project seeks to develop methods for automated verification of Ethereum Consensus Layer Specifications.
Our goal is to improve the trust guarantees for these specifications by statically verifying protocol properties. We propose to establish translation rules from executable Python specifications to the [TLA+ specification language][TLA+], thus making the specifications amenable to model checking with [Apalache][].

[learn more »](https://github.com/freespek/ssf-mc)


[Stellar]: https://stellar.org/
[Soroban]: https://developers.stellar.org/docs/smart-contracts/getting-started/setup
[TLA+]: https://lamport.azurewebsites.net/tla/tla.html
[Apalache]: https://github.com/informalsystems/apalache