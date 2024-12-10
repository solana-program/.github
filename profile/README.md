## Solana On-Chain Programs and Their Tooling

This organization contains all of the on-chain program tooling maintained by Anza.

There are multiple types of repositories that can be found in this group:
* On-chain BPF programs formerly from the [Solana Program Library](https://github.com/solana-labs/solana-program-library) (SPL).
  * [SPL Token](https://github.com/solana-program/token)
  * [SPL Memo](https://github.com/solana-program/memo)
  * ...
* On-chain Core BPF programs as a result of [SIMD 0088](https://github.com/solana-foundation/solana-improvement-documents/blob/main/proposals/0088-enable-core-bpf-programs.md).
  * [Address Lookup Table program](https://github.com/solana-program/address-lookup-table)
  * [Config program](https://github.com/solana-program/config)
  * ...
* Tooling for handling the migration of builtin programs to Core BPF.
  * [Core BPF Migration Test CLI](https://github.com/solana-program/core-bpf-migration-test-cli)
* Tooling for developing on-chain programs and their clients.
  * [Create-Solana-Program](https://github.com/solana-program/create-solana-program)
  * [Actions](https://github.com/solana-program/actions)
