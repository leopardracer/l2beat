Generated with discovered.json: 0x64ab6887390487b6249dc7e7781de4a348253a25

# Diff at Mon, 07 Jul 2025 14:54:42 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@7d0fdd1242b42b3e5413cd39140cefe4c5d9eb10 block: 22865552
- current block number: 22867011

## Description

Provide description of changes. This section will be preserved.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 22865552 (main branch discovery), not current.

```diff
    contract Zora_Adapter (0x024F2fC31CBDD8de17194b1892c834f98Ef5169b) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract Soneium_Adapter (0x0c9d064523177dBB55CFE52b9D0c485FBFc35FD2) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract Arbitrum_Adapter (0x100EDfCf3af2B4625Fca4EaF6C533703e71F7210) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract Redstone_Adapter (0x188F8C95B7cfB7993B53a4F643efa687916f73fA) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract HubPoolStore (0x1Ace3BbD69b63063F859514Eca29C9BDd8310E61) {
    +++ description: Simple data store used by the Universal_Adapter to store message calldata hashes. The content of this calldata can be proven by Ethereum zk light clients on remote chains and then executed to relay root bundles or arbitrary messages.
      description:
-        "Simple data store used by the Universal_Adapter to store message calldata hashes."
+        "Simple data store used by the Universal_Adapter to store message calldata hashes. The content of this calldata can be proven by Ethereum zk light clients on remote chains and then executed to relay root bundles or arbitrary messages."
      category:
+        {"name":"Local Infrastructure","priority":5}
    }
```

```diff
    contract Universal_Adapter (0x22001f37B586792F25Ef9d19d99537C6446e0833) {
    +++ description: This adapter can be used to send messages / root bundles to chains that do not have a canonical adapter. It stores calldata in the 0x1Ace3BbD69b63063F859514Eca29C9BDd8310E61 on Ethereum, which can then be zk proven on a remote chain.
      template:
-        "acrossv3/adapter"
+        "acrossv3/universalAdapter"
      description:
-        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
+        "This adapter can be used to send messages / root bundles to chains that do not have a canonical adapter. It stores calldata in the 0x1Ace3BbD69b63063F859514Eca29C9BDd8310E61 on Ethereum, which can then be zk proven on a remote chain."
      category.name:
-        "External Bridges"
+        "Local Infrastructure"
      category.priority:
-        1
+        5
    }
```

```diff
    contract Scroll_Adapter (0x2DA799c2223c6ffB595e578903AE6b95839160d8) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract Boba_Adapter (0x33B0Ec794c15D6Cc705818E70d4CaCe7bCfB5Af3) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract Ethereum_Adapter (0x527E872a5c3f0C7c24Fe33F2593cFB890a285084) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract Linea_Adapter (0x5A44A32c13e2C43416bFDE5dDF5DCb3880c42787) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract ZkStack_CustomGasToken_Adapter (0x5e0B7e20a77BDf11812837D30F1326068Bcf24Cf) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract Alephzero_Adapter (0x6F4083304C2cA99B077ACE06a5DcF670615915Af) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract Ink_Adapter (0x7e90A40c7519b041A7DF6498fBf5662e8cFC61d2) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract WorldChain_Adapter (0x8bbdD67102D743b8533c1277a4ffdA04Dea158D1) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract Solana_Adapter (0x9F788694934fD2Ed34D5340B9a76EB34f2bFD7B3) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract ZkStack_Adapter (0xA374585E6062517Ee367ee5044946A6fBe17724f) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract Polygon_Adapter (0xb4AeF0178f5725392A26eE18684C2aB62adc912e) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract Base_Adapter (0xE1421233BF7158A19f89F17c9735F9cbd3D9529c) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract Optimism_Adapter (0xE1e74B3D6A8E2A479B62958D4E4E6eEaea5B612b) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract Lisk_Adapter (0xF039AdCC74936F90fE175e8b3FE0FdC8b8E0c73b) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract Mode_Adapter (0xf1B59868697f3925b72889ede818B9E7ba0316d0) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract Blast_Adapter (0xF2bEf5E905AAE0295003ab14872F811E914EdD81) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

```diff
    contract DoctorWho_Adapter (0xFADcC43096756e1527306FD92982FEbBe3c629Fa) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      template:
-        "acrossv3/adapter"
+        "acrossv3/Adapter"
    }
```

Generated with discovered.json: 0x4de0b28750bf8d639de102e7af84feb054207e56

# Diff at Mon, 07 Jul 2025 06:37:18 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@1a6f89d35120c5c65bf077ab92a9ca72da48080d block: 22823774
- current block number: 22865552

## Description

Solana adapter (via circle CCTP) added.

## Watched changes

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: The central L1 contract (hub) that manages liquidity from LPs and coordinates cross-chain settlements. It receives and secures settlement proposals (root bundles) using the UMA Optimistic Oracle, with a challenge period of 1h and a bond amount of 0.45 ABT.
      values.Adapters.34268394551451:
+        "0x9F788694934fD2Ed34D5340B9a76EB34f2bFD7B3"
      values.CrossChainContracts.34268394551451:
+        "0x5b162F2c7EC8795BD0800C1462949E2328D1DD5a"
    }
```

```diff
+   Status: CREATED
    contract Solana_Adapter (0x9F788694934fD2Ed34D5340B9a76EB34f2bFD7B3)
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
```

## Source code changes

```diff
.../across-v3/ethereum/.flat/Solana_Adapter.sol    | 695 +++++++++++++++++++++
 1 file changed, 695 insertions(+)
```

Generated with discovered.json: 0xd69a5e30f623dd65a12e45a3f26f870da47a03bd

# Diff at Fri, 04 Jul 2025 12:18:50 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@1f56dc47fe915564d4555300304da4d3bcbc087f block: 22823774
- current block number: 22823774

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 22823774 (main branch discovery), not current.

```diff
    EOA  (0x2bAaA41d155ad8a4126184950B31F50A1513cE25) {
    +++ description: None
      receivedPermissions.0.from:
-        "ethereum:0x54f44eA3D2e7aA0ac089c4d8F7C93C27844057BF"
+        "eth:0x54f44eA3D2e7aA0ac089c4d8F7C93C27844057BF"
    }
```

```diff
    contract ProposerV2 (0x50efaC9619225d7fB4703C5872da978849B6E7cC) {
    +++ description: Token governance contract allowing anyone to create a UMA governance proposal for a bond of 5,000 UMA tokens.
      receivedPermissions.0.from:
-        "ethereum:0x7b292034084A41B9D441B71b6E3557Edd0463fa8"
+        "eth:0x7b292034084A41B9D441B71b6E3557Edd0463fa8"
    }
```

```diff
    contract GovernorV2 (0x7b292034084A41B9D441B71b6E3557Edd0463fa8) {
    +++ description: Central UMA governance contract. It executes administrative proposals that have been passed by UMA token holder votes.
      receivedPermissions.0.from:
-        "ethereum:0x004395edb43EFca9885CEdad51EC9fAf93Bd34ac"
+        "eth:0x004395edb43EFca9885CEdad51EC9fAf93Bd34ac"
      receivedPermissions.1.from:
-        "ethereum:0x3e532e6222afe9Bcf02DCB87216802c75D5113aE"
+        "eth:0x3e532e6222afe9Bcf02DCB87216802c75D5113aE"
      receivedPermissions.2.from:
-        "ethereum:0x40f941E48A552bF496B154Af6bf55725f18D77c3"
+        "eth:0x40f941E48A552bF496B154Af6bf55725f18D77c3"
      receivedPermissions.3.from:
-        "ethereum:0x50efaC9619225d7fB4703C5872da978849B6E7cC"
+        "eth:0x50efaC9619225d7fB4703C5872da978849B6E7cC"
      receivedPermissions.4.from:
-        "ethereum:0x54f44eA3D2e7aA0ac089c4d8F7C93C27844057BF"
+        "eth:0x54f44eA3D2e7aA0ac089c4d8F7C93C27844057BF"
      receivedPermissions.5.from:
-        "ethereum:0x7b292034084A41B9D441B71b6E3557Edd0463fa8"
+        "eth:0x7b292034084A41B9D441B71b6E3557Edd0463fa8"
      receivedPermissions.6.from:
-        "ethereum:0x91F1804aCaf87C2D34A34A70be1bb16bB85D6748"
+        "eth:0x91F1804aCaf87C2D34A34A70be1bb16bB85D6748"
      receivedPermissions.7.from:
-        "ethereum:0xcF649d9Da4D1362C4DAEa67573430Bd6f945e570"
+        "eth:0xcF649d9Da4D1362C4DAEa67573430Bd6f945e570"
      receivedPermissions.8.from:
-        "ethereum:0xdBF90434dF0B98219f87d112F37d74B1D90758c7"
+        "eth:0xdBF90434dF0B98219f87d112F37d74B1D90758c7"
      receivedPermissions.9.from:
-        "ethereum:0xfb55F43fB9F48F63f9269DB7Dde3BbBe1ebDC0dE"
+        "eth:0xfb55F43fB9F48F63f9269DB7Dde3BbBe1ebDC0dE"
    }
```

```diff
    contract UMA Multisig (0x8180D59b7175d4064bDFA8138A58e9baBFFdA44a) {
    +++ description: None
      receivedPermissions.0.from:
-        "ethereum:0x91F1804aCaf87C2D34A34A70be1bb16bB85D6748"
+        "eth:0x91F1804aCaf87C2D34A34A70be1bb16bB85D6748"
    }
```

```diff
    contract OptimisticGovernor (0x8692B776d1Ff0664177c90465038056Dc64f8991) {
    +++ description: Optimistic Governance module allowing for proposals by anyone with a bond of 2 WETH. They become executable if not challenged within 2d. The rules for proposals can be read directly from the contract values.
      receivedPermissions.0.via.0.address:
-        "ethereum:0xB524735356985D2f267FA010D681f061DfF03715"
+        "eth:0xB524735356985D2f267FA010D681f061DfF03715"
      receivedPermissions.0.from:
-        "ethereum:0x3B03509645713718B78951126E0A6de6f10043f5"
+        "eth:0x3B03509645713718B78951126E0A6de6f10043f5"
      receivedPermissions.1.via.0.address:
-        "ethereum:0xB524735356985D2f267FA010D681f061DfF03715"
+        "eth:0xB524735356985D2f267FA010D681f061DfF03715"
      receivedPermissions.1.from:
-        "ethereum:0x8692B776d1Ff0664177c90465038056Dc64f8991"
+        "eth:0x8692B776d1Ff0664177c90465038056Dc64f8991"
      receivedPermissions.2.via.0.address:
-        "ethereum:0xB524735356985D2f267FA010D681f061DfF03715"
+        "eth:0xB524735356985D2f267FA010D681f061DfF03715"
      receivedPermissions.2.from:
-        "ethereum:0xc186fA914353c44b2E33eBE05f21846F1048bEda"
+        "eth:0xc186fA914353c44b2E33eBE05f21846F1048bEda"
      receivedPermissions.3.via.0.address:
-        "ethereum:0xB524735356985D2f267FA010D681f061DfF03715"
+        "eth:0xB524735356985D2f267FA010D681f061DfF03715"
      receivedPermissions.3.from:
-        "ethereum:0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea"
+        "eth:0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea"
      directlyReceivedPermissions.0.from:
-        "ethereum:0xB524735356985D2f267FA010D681f061DfF03715"
+        "eth:0xB524735356985D2f267FA010D681f061DfF03715"
    }
```

```diff
    contract EmergencyProposer (0x91F1804aCaf87C2D34A34A70be1bb16bB85D6748) {
    +++ description: Token governance contract allowing anyone to create a UMA governance proposal for a bond of 5,000,000 UMA tokens. This circumvents the UMA optimistic oracle but can only be executed or removed after 10d, and only by 0x8180D59b7175d4064bDFA8138A58e9baBFFdA44a.
      receivedPermissions.0.from:
-        "ethereum:0x7b292034084A41B9D441B71b6E3557Edd0463fa8"
+        "eth:0x7b292034084A41B9D441B71b6E3557Edd0463fa8"
    }
```

```diff
    contract Across Multisig (0xB524735356985D2f267FA010D681f061DfF03715) {
    +++ description: None
      receivedPermissions.0.from:
-        "ethereum:0x3B03509645713718B78951126E0A6de6f10043f5"
+        "eth:0x3B03509645713718B78951126E0A6de6f10043f5"
      receivedPermissions.1.from:
-        "ethereum:0x8692B776d1Ff0664177c90465038056Dc64f8991"
+        "eth:0x8692B776d1Ff0664177c90465038056Dc64f8991"
      receivedPermissions.2.from:
-        "ethereum:0xc186fA914353c44b2E33eBE05f21846F1048bEda"
+        "eth:0xc186fA914353c44b2E33eBE05f21846F1048bEda"
      receivedPermissions.3.from:
-        "ethereum:0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea"
+        "eth:0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea"
    }
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: The central L1 contract (hub) that manages liquidity from LPs and coordinates cross-chain settlements. It receives and secures settlement proposals (root bundles) using the UMA Optimistic Oracle, with a challenge period of 1h and a bond amount of 0.45 ABT.
      directlyReceivedPermissions.0.from:
-        "ethereum:0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5"
+        "eth:0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5"
      directlyReceivedPermissions.1.from:
-        "ethereum:0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5"
+        "eth:0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5"
    }
```

```diff
    EOA  (0xf7bAc63fc7CEaCf0589F25454Ecf5C2ce904997c) {
    +++ description: None
      receivedPermissions.0.from:
-        "ethereum:0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea"
+        "eth:0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea"
      receivedPermissions.1.from:
-        "ethereum:0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea"
+        "eth:0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea"
    }
```

Generated with discovered.json: 0x823833e03f6b9fd54c07f5c52ec01fcdeaa6d181

# Diff at Tue, 01 Jul 2025 10:30:49 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@6dae2e2c6da3c994ad2a4e3a50e7430960cb763e block: 22816998
- current block number: 22823774

## Description

Spokepool upgrade: minor fixes and [7702 delegation detection](https://disco.l2beat.com/diff/eth:0x0190a2328e072Fc5a7fA00F6C9ae2a16c7F4E32a/eth:0xFBc81a18EcDa8E6A91275cFDF5FC6d91A7C5AE80?lines=R5649).

## Watched changes

```diff
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5) {
    +++ description: The user-facing contract on each connected chain where funds are deposited to initiate a bridge transfer. It also receives settlement data from the HubPool to process refunds for the relayers who fulfilled those transfers.
      sourceHashes.1:
-        "0x10d81ccfd26fbcb9926942a46436a7bedd3946646911a43f3f0e13dc7eb81517"
+        "0x40060e8b2904995f3cb0149fcbf73924c9b1e2e164a823a7957d703a9f7c6fe5"
      values.$implementation:
-        "0x0190a2328e072Fc5a7fA00F6C9ae2a16c7F4E32a"
+        "0xFBc81a18EcDa8E6A91275cFDF5FC6d91A7C5AE80"
      values.$pastUpgrades.9:
+        ["2025-06-30T17:21:23.000Z","0xa4cfc9525849a8a3052a587a29006303e9b16ce08fa096460bb6fe2017b1a3ef",["0xFBc81a18EcDa8E6A91275cFDF5FC6d91A7C5AE80"]]
      values.$upgradeCount:
-        9
+        10
      values.UPDATE_ADDRESS_DEPOSIT_DETAILS_HASH:
-        "0x9c6dfd61d811b9950a4f2b9adf46357b717c816d22c420d0bde8f2360148f7cd"
      implementationNames.0x0190a2328e072Fc5a7fA00F6C9ae2a16c7F4E32a:
-        "Ethereum_SpokePool"
      implementationNames.0xFBc81a18EcDa8E6A91275cFDF5FC6d91A7C5AE80:
+        "Ethereum_SpokePool"
    }
```

## Source code changes

```diff
.../Ethereum_SpokePool/Ethereum_SpokePool.sol      | 65 ++++++++--------------
 1 file changed, 24 insertions(+), 41 deletions(-)
```

Generated with discovered.json: 0xa0b40952153894e314adca8c863e0d39a3eda492

# Diff at Mon, 30 Jun 2025 11:41:15 GMT:

- author: Luca Donno (<donnoh99@gmail.com>)
- comparing to: main@8d994c18c6e642449f421c7342cea0f0650835d8 block: 22665827
- current block number: 22816998

## Description

discodrive, add UMA disco config.

## Watched changes

```diff
    contract VotingV2 (0x004395edb43EFca9885CEdad51EC9fAf93Bd34ac) {
    +++ description: Core smart contract for UMA's Data Verification Mechanism (DVM), serving as source of truth for disputed claims. UMA token holders collectively resolve price requests and earn rewards for correct participation. Commit- and reveal phases for the voting take 1d each.
      values.rewardPerToken:
-        "627473210166767069"
+        "637167053348045646"
      values.rewardPerTokenStored:
-        "627389365474219770"
+        "637142462765695709"
    }
```

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 22665827 (main branch discovery), not current.

```diff
    contract Zora_Adapter (0x024F2fC31CBDD8de17194b1892c834f98Ef5169b) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
-   Status: DELETED
    contract VotingToken (0x04Fa0d235C4abf4BcF4787aF4CF447DE572eF828)
    +++ description: None
```

```diff
    contract Soneium_Adapter (0x0c9d064523177dBB55CFE52b9D0c485FBFc35FD2) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract Arbitrum_Adapter (0x100EDfCf3af2B4625Fca4EaF6C533703e71F7210) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract Redstone_Adapter (0x188F8C95B7cfB7993B53a4F643efa687916f73fA) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract HubPoolStore (0x1Ace3BbD69b63063F859514Eca29C9BDd8310E61) {
    +++ description: Simple data store used by the Universal_Adapter to store message calldata hashes.
      template:
+        "acrossv3/HubPoolStore"
      description:
+        "Simple data store used by the Universal_Adapter to store message calldata hashes."
    }
```

```diff
    contract Universal_Adapter (0x22001f37B586792F25Ef9d19d99537C6446e0833) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract Scroll_Adapter (0x2DA799c2223c6ffB595e578903AE6b95839160d8) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract Boba_Adapter (0x33B0Ec794c15D6Cc705818E70d4CaCe7bCfB5Af3) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract AcrossConfigStore (0x3B03509645713718B78951126E0A6de6f10043f5) {
    +++ description: Simple, owner-controlled contract for storing protocol-wide, token-specific configuration data.
      template:
+        "acrossv3/AcrossConfigStore"
      description:
+        "Simple, owner-controlled contract for storing protocol-wide, token-specific configuration data."
    }
```

```diff
    contract Finder (0x40f941E48A552bF496B154Af6bf55725f18D77c3) {
    +++ description: Maps interface names to contract addresses (UMA protocol contracts).
      values.namedAddresses:
+        [{"name":"Oracle","address":"0x004395edb43EFca9885CEdad51EC9fAf93Bd34ac"},{"name":"Registry","address":"0x3e532e6222afe9Bcf02DCB87216802c75D5113aE"},{"name":"FinancialContractsAdmin","address":"0x4E6CCB1dA3C7844887F9A5aF4e8450d9fd90317A"},{"name":"Store","address":"0x54f44eA3D2e7aA0ac089c4d8F7C93C27844057BF"},{"name":"IdentifierWhitelist","address":"0xcF649d9Da4D1362C4DAEa67573430Bd6f945e570"},{"name":"CollateralWhitelist","address":"0xdBF90434dF0B98219f87d112F37d74B1D90758c7"},{"name":"OptimisticOracle","address":"0xC43767F4592DF265B4a9F1a398B97fF24F38C6A6"},{"name":"SkinnyOptimisticOracle","address":"0xeE3Afe347D5C74317041E2618C49534dAf887c24"},{"name":"OptimisticOracleV2","address":"0xA0Ae6609447e57a42c51B50EAe921D701823FFAe"},{"name":"OptimisticAsserter","address":"0x0000000000000000000000000000000000000000"},{"name":"OptimisticOracleV3","address":"0xfb55F43fB9F48F63f9269DB7Dde3BbBe1ebDC0dE"}]
      template:
+        "uma/Finder"
      description:
+        "Maps interface names to contract addresses (UMA protocol contracts)."
      usedTypes:
+        [{"typeCaster":"Mapping","arg":{"0x4f7261636c650000000000000000000000000000000000000000000000000000":"Oracle","0x5265676973747279000000000000000000000000000000000000000000000000":"Registry","0x46696e616e6369616c436f6e74726163747341646d696e000000000000000000":"FinancialContractsAdmin","0x53746f7265000000000000000000000000000000000000000000000000000000":"Store","0x4964656e74696669657257686974656c69737400000000000000000000000000":"IdentifierWhitelist","0x436f6c6c61746572616c57686974656c69737400000000000000000000000000":"CollateralWhitelist","0x4f7074696d69737469634f7261636c6500000000000000000000000000000000":"OptimisticOracle","0x536b696e6e794f7074696d69737469634f7261636c6500000000000000000000":"SkinnyOptimisticOracle","0x4f7074696d69737469634f7261636c6556320000000000000000000000000000":"OptimisticOracleV2","0x4f7074696d697374696341737365727465720000000000000000000000000000":"OptimisticAsserter","0x4f7074696d69737469634f7261636c6556330000000000000000000000000000":"OptimisticOracleV3"}}]
    }
```

```diff
-   Status: DELETED
    contract PolygonTokenBridger (0x48d990AbDA20afa1fD1da713AbC041B60a922c65)
    +++ description: None
```

```diff
    contract ProposerV2 (0x50efaC9619225d7fB4703C5872da978849B6E7cC) {
    +++ description: Token governance contract allowing anyone to create a UMA governance proposal for a bond of 5,000 UMA tokens.
      template:
+        "uma/ProposerV2"
      description:
+        "Token governance contract allowing anyone to create a UMA governance proposal for a bond of 5,000 UMA tokens."
      usedTypes:
+        [{"typeCaster":"Undecimal","arg":{"decimals":18}}]
      category:
+        {"name":"Shared Infrastructure","priority":4}
      receivedPermissions:
+        [{"permission":"interact","from":"ethereum:0x7b292034084A41B9D441B71b6E3557Edd0463fa8","description":"propose governance actions.","role":".proposer"}]
    }
```

```diff
    contract Ethereum_Adapter (0x527E872a5c3f0C7c24Fe33F2593cFB890a285084) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract Linea_Adapter (0x5A44A32c13e2C43416bFDE5dDF5DCb3880c42787) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5) {
    +++ description: The user-facing contract on each connected chain where funds are deposited to initiate a bridge transfer. It also receives settlement data from the HubPool to process refunds for the relayers who fulfilled those transfers.
      values.proxiableUUID:
-        "EXPECT_REVERT"
      template:
+        "acrossv3/SpokePool"
      description:
+        "The user-facing contract on each connected chain where funds are deposited to initiate a bridge transfer. It also receives settlement data from the HubPool to process refunds for the relayers who fulfilled those transfers."
      fieldMeta:
+        {"owner":{"severity":"HIGH"}}
      category:
+        {"name":"Local Infrastructure","priority":5}
    }
```

```diff
    contract ZkStack_CustomGasToken_Adapter (0x5e0B7e20a77BDf11812837D30F1326068Bcf24Cf) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract Alephzero_Adapter (0x6F4083304C2cA99B077ACE06a5DcF670615915Af) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract GovernorV2 (0x7b292034084A41B9D441B71b6E3557Edd0463fa8) {
    +++ description: Central UMA governance contract. It executes administrative proposals that have been passed by UMA token holder votes.
      values.emergencyProposer:
+        "0x91F1804aCaf87C2D34A34A70be1bb16bB85D6748"
      values.owner:
+        "0x7b292034084A41B9D441B71b6E3557Edd0463fa8"
      values.proposer:
+        "0x50efaC9619225d7fB4703C5872da978849B6E7cC"
      template:
+        "uma/GovernorV2"
      description:
+        "Central UMA governance contract. It executes administrative proposals that have been passed by UMA token holder votes."
      category:
+        {"name":"Shared Infrastructure","priority":4}
      receivedPermissions:
+        [{"permission":"interact","from":"ethereum:0x004395edb43EFca9885CEdad51EC9fAf93Bd34ac","description":"set critical administrative parameters like migrating to a new contract and requesting governance actions (`requestPrice()`) directly.","role":".owner"},{"permission":"interact","from":"ethereum:0x3e532e6222afe9Bcf02DCB87216802c75D5113aE","description":"manage registered contracts.","role":".owner"},{"permission":"interact","from":"ethereum:0x40f941E48A552bF496B154Af6bf55725f18D77c3","description":"manage address mappings.","role":".owner"},{"permission":"interact","from":"ethereum:0x50efaC9619225d7fB4703C5872da978849B6E7cC","description":"set the bond amount.","role":".owner"},{"permission":"interact","from":"ethereum:0x54f44eA3D2e7aA0ac089c4d8F7C93C27844057BF","description":"set fees for disputes and manage all roles in the contract.","role":".owner"},{"permission":"interact","from":"ethereum:0x7b292034084A41B9D441B71b6E3557Edd0463fa8","description":"manage all roles in the contract.","role":".owner"},{"permission":"interact","from":"ethereum:0x91F1804aCaf87C2D34A34A70be1bb16bB85D6748","description":"remove and slash proposals, set the bond amount and the expiry time, manage the executor address.","role":".owner"},{"permission":"interact","from":"ethereum:0xcF649d9Da4D1362C4DAEa67573430Bd6f945e570","description":"manage the whitelist.","role":".owner"},{"permission":"interact","from":"ethereum:0xdBF90434dF0B98219f87d112F37d74B1D90758c7","description":"manage the addresses on the whitelist.","role":".owner"},{"permission":"interact","from":"ethereum:0xfb55F43fB9F48F63f9269DB7Dde3BbBe1ebDC0dE","description":"set critical administrative parameters like default bonds, bond token, fees.","role":".owner"}]
    }
```

```diff
-   Status: DELETED
    contract LpTokenFactory (0x7dB69eb9F52eD773E9b03f5068A1ea0275b2fD9d)
    +++ description: None
```

```diff
    contract Ink_Adapter (0x7e90A40c7519b041A7DF6498fBf5662e8cFC61d2) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract UMA Multisig (0x8180D59b7175d4064bDFA8138A58e9baBFFdA44a) {
    +++ description: None
      name:
-        "EmergencyProposalExecutor"
+        "UMA Multisig"
      receivedPermissions:
+        [{"permission":"interact","from":"ethereum:0x91F1804aCaf87C2D34A34A70be1bb16bB85D6748","description":"remove proposals, execute emergency proposals.","role":".executor"}]
    }
```

```diff
    contract OptimisticGovernor (0x8692B776d1Ff0664177c90465038056Dc64f8991) {
    +++ description: Optimistic Governance module allowing for proposals by anyone with a bond of 2 WETH. They become executable if not challenged within 2d. The rules for proposals can be read directly from the contract values.
      values.bondFmt:
+        "2"
      values.delayFmt:
+        "2d"
      template:
+        "uma/OptimisticGovernor"
      description:
+        "Optimistic Governance module allowing for proposals by anyone with a bond of 2 WETH. They become executable if not challenged within 2d. The rules for proposals can be read directly from the contract values."
      fieldMeta:
+        {"rules":{"description":"string of rules that a proposer is accepting when posting a proposal with a bond."}}
      usedTypes:
+        [{"typeCaster":"Undecimal","arg":{"decimals":18}}]
      receivedPermissions:
+        [{"permission":"interact","from":"ethereum:0x3B03509645713718B78951126E0A6de6f10043f5","description":"update configuration values.","role":".owner","via":[{"address":"ethereum:0xB524735356985D2f267FA010D681f061DfF03715"}]},{"permission":"interact","from":"ethereum:0x8692B776d1Ff0664177c90465038056Dc64f8991","description":"set guard, avatar, target, delay, identifier, escalationManager, bond token and amount.","role":".owner","via":[{"address":"ethereum:0xB524735356985D2f267FA010D681f061DfF03715"}]},{"permission":"interact","from":"ethereum:0xc186fA914353c44b2E33eBE05f21846F1048bEda","description":"pause the system, manage all fees, bonds and security parameters, manage tokens and chain support, and critical emergency actions like admin functions on remote SpokePools or deleting proposals (can steal funds).","role":".owner","via":[{"address":"ethereum:0xB524735356985D2f267FA010D681f061DfF03715"}]},{"permission":"interact","from":"ethereum:0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea","description":"manage the proposer role.","role":".owner","via":[{"address":"ethereum:0xB524735356985D2f267FA010D681f061DfF03715"}]}]
    }
```

```diff
    contract WorldChain_Adapter (0x8bbdD67102D743b8533c1277a4ffdA04Dea158D1) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract EmergencyProposer (0x91F1804aCaf87C2D34A34A70be1bb16bB85D6748) {
    +++ description: Token governance contract allowing anyone to create a UMA governance proposal for a bond of 5,000,000 UMA tokens. This circumvents the UMA optimistic oracle but can only be executed or removed after 10d, and only by 0x8180D59b7175d4064bDFA8138A58e9baBFFdA44a.
      values.bondFmt:
+        "5,000,000"
      values.delayFmt:
+        "10d"
      template:
+        "uma/EmergencyProposer"
      description:
+        "Token governance contract allowing anyone to create a UMA governance proposal for a bond of 5,000,000 UMA tokens. This circumvents the UMA optimistic oracle but can only be executed or removed after 10d, and only by 0x8180D59b7175d4064bDFA8138A58e9baBFFdA44a."
      usedTypes:
+        [{"typeCaster":"Undecimal","arg":{"decimals":18}}]
      receivedPermissions:
+        [{"permission":"interact","from":"ethereum:0x7b292034084A41B9D441B71b6E3557Edd0463fa8","description":"can bypass the voting system and execute proposals immediately.","role":".emergencyProposer"}]
    }
```

```diff
    contract ZkStack_Adapter (0xA374585E6062517Ee367ee5044946A6fBe17724f) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract Polygon_Adapter (0xb4AeF0178f5725392A26eE18684C2aB62adc912e) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract Across Multisig (0xB524735356985D2f267FA010D681f061DfF03715) {
    +++ description: None
      name:
-        "HubPool Multisig"
+        "Across Multisig"
      receivedPermissions:
+        [{"permission":"interact","from":"ethereum:0x3B03509645713718B78951126E0A6de6f10043f5","description":"update configuration values.","role":".owner"},{"permission":"interact","from":"ethereum:0x8692B776d1Ff0664177c90465038056Dc64f8991","description":"set guard, avatar, target, delay, identifier, escalationManager, bond token and amount.","role":".owner"},{"permission":"interact","from":"ethereum:0xc186fA914353c44b2E33eBE05f21846F1048bEda","description":"pause the system, manage all fees, bonds and security parameters, manage tokens and chain support, and critical emergency actions like admin functions on remote SpokePools or deleting proposals (can steal funds).","role":".owner"},{"permission":"interact","from":"ethereum:0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea","description":"manage the proposer role.","role":".owner"}]
    }
```

```diff
-   Status: DELETED
    contract CoveredCallFinancialProductLibrary (0xBbc6009fEfFc27ce705322832Cb2068F8C1e0A58)
    +++ description: None
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: The central L1 contract (hub) that manages liquidity from LPs and coordinates cross-chain settlements. It receives and secures settlement proposals (root bundles) using the UMA Optimistic Oracle, with a challenge period of 1h and a bond amount of 0.45 ABT.
      receivedPermissions:
-        [{"permission":"upgrade","from":"ethereum:0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5","role":"admin"}]
      values.bondAmountFmt:
+        "0.45"
      values.finalizationDelayFmt:
+        "1h"
      values.spokePool:
+        "0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5"
      template:
+        "acrossv3/HubPool"
      description:
+        "The central L1 contract (hub) that manages liquidity from LPs and coordinates cross-chain settlements. It receives and secures settlement proposals (root bundles) using the UMA Optimistic Oracle, with a challenge period of 1h and a bond amount of 0.45 ABT."
      fieldMeta:
+        {"owner":{"severity":"HIGH"},"paused":{"severity":"HIGH"}}
      usedTypes:
+        [{"typeCaster":"Undecimal","arg":{"decimals":18}}]
      category:
+        {"name":"Local Infrastructure","priority":5}
      directlyReceivedPermissions:
+        [{"permission":"interact","from":"ethereum:0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5","description":"relay and delete root bundles, pause the contract, manage routes, set the withdrawal recipient (crosschain rebalancing target).","role":".owner"},{"permission":"upgrade","from":"ethereum:0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5","role":"admin"}]
    }
```

```diff
    contract Base_Adapter (0xE1421233BF7158A19f89F17c9735F9cbd3D9529c) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract Optimism_Adapter (0xE1e74B3D6A8E2A479B62958D4E4E6eEaea5B612b) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract AcrossBondToken (ABT) (0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea) {
    +++ description: A bond token wrapping ETH for usage in the Across protocol. Implements modified ERC20 logic to only allow permissioned proposers to use it as a bond for root bundle proposals.
      name:
-        "BondToken"
+        "AcrossBondToken (ABT)"
      template:
+        "acrossv3/BondToken"
      description:
+        "A bond token wrapping ETH for usage in the Across protocol. Implements modified ERC20 logic to only allow permissioned proposers to use it as a bond for root bundle proposals."
      fieldMeta:
+        {"proposers":{"severity":"HIGH"}}
    }
```

```diff
    contract SkinnyOptimisticOracle (0xeE3Afe347D5C74317041E2618C49534dAf887c24) {
    +++ description: Validates bridge messages by allowing proposers to make bonded assertions about crosschain events. It enforces a challenge period during which any invalid claims can be disputed and escalated to UMA's Data Verification Mechanism (DVM) for resolution.
      name:
-        "UMAOptimisticOracle"
+        "SkinnyOptimisticOracle"
      template:
+        "uma/SkinnyOptimisticOracle"
      description:
+        "Validates bridge messages by allowing proposers to make bonded assertions about crosschain events. It enforces a challenge period during which any invalid claims can be disputed and escalated to UMA's Data Verification Mechanism (DVM) for resolution."
    }
```

```diff
    contract Lisk_Adapter (0xF039AdCC74936F90fE175e8b3FE0FdC8b8E0c73b) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract Mode_Adapter (0xf1B59868697f3925b72889ede818B9E7ba0316d0) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract Blast_Adapter (0xF2bEf5E905AAE0295003ab14872F811E914EdD81) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    EOA  (0xf7bAc63fc7CEaCf0589F25454Ecf5C2ce904997c) {
    +++ description: None
      receivedPermissions:
+        [{"permission":"acrossPropose","from":"ethereum:0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea","role":".proposers"},{"permission":"interact","from":"ethereum:0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea","description":"use ABT as a bond to the HubPool contract for root bundle proposals.","role":".proposers"}]
    }
```

```diff
    contract DoctorWho_Adapter (0xFADcC43096756e1527306FD92982FEbBe3c629Fa) {
    +++ description: Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges.
      description:
+        "Modular, chain-specific contract that abstracts the communication logic for settlement between the HubPool and various SpokePools and their Relayers, often via canonical bridges."
      category:
+        {"name":"External Bridges","priority":1}
    }
```

```diff
    contract OptimisticOracleV3 (0xfb55F43fB9F48F63f9269DB7Dde3BbBe1ebDC0dE) {
    +++ description: Standard UMA optimistic oracle contract that allows anyone to make an arbitrary claim by posting a bond. The claim is considered true unless it is successfully disputed within a challenge window, with UMA's DVM acting as the final arbiter for disputes.
      template:
+        "uma/OptimisticOracleV3"
      description:
+        "Standard UMA optimistic oracle contract that allows anyone to make an arbitrary claim by posting a bond. The claim is considered true unless it is successfully disputed within a challenge window, with UMA's DVM acting as the final arbiter for disputes."
    }
```

```diff
+   Status: CREATED
    contract VotingV2 (0x004395edb43EFca9885CEdad51EC9fAf93Bd34ac)
    +++ description: Core smart contract for UMA's Data Verification Mechanism (DVM), serving as source of truth for disputed claims. UMA token holders collectively resolve price requests and earn rewards for correct participation. Commit- and reveal phases for the voting take 1d each.
```

```diff
+   Status: CREATED
    contract Registry (0x3e532e6222afe9Bcf02DCB87216802c75D5113aE)
    +++ description: Registry for contracts that are allowed to call `requestPrice()` in the UMA voting contracts (ie. request dispute resolution by the UMA DVM).
```

```diff
+   Status: CREATED
    contract Store (0x54f44eA3D2e7aA0ac089c4d8F7C93C27844057BF)
    +++ description: UMA protocol contract responsible for calculating and collecting regular and final fees for using the DVM.
```

```diff
+   Status: CREATED
    contract FixedSlashSlashingLibrary (0x9a406ba5a99983250Fd663947b3c968D387ce5cd)
    +++ description: Stores slashing parameters and calculates slashing amounts based on that (UMA protocol).
```

```diff
+   Status: CREATED
    contract IdentifierWhitelist (0xcF649d9Da4D1362C4DAEa67573430Bd6f945e570)
    +++ description: Keeps a list of whitelisted identifiers that are accepted by the UMA v3 protocol. Across uses the identifier `ACROSS-V2` for its disputes.
```

```diff
+   Status: CREATED
    contract AddressWhitelist (0xdBF90434dF0B98219f87d112F37d74B1D90758c7)
    +++ description: Implements a simple address whitelist for tokens that can be used as bonds and fees.
```

Generated with discovered.json: 0xf8b87edd4b99da687644e18a2aa77d2e0e28dbcd

# Diff at Mon, 09 Jun 2025 08:29:11 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@7cc006dadcc55e6cce3be3eb03d491835943fb43 block: 22517852
- current block number: 22665827

## Description

Upgrade worldchain adapter to support CCTPv2.

## Watched changes

```diff
-   Status: DELETED
    contract WorldChain_Adapter (0xA8399e221a583A57F54Abb5bA22f31b5D6C09f32)
    +++ description: None
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.480:
-        "0xA8399e221a583A57F54Abb5bA22f31b5D6C09f32"
+        "0x8bbdD67102D743b8533c1277a4ffdA04Dea158D1"
    }
```

```diff
+   Status: CREATED
    contract WorldChain_Adapter (0x8bbdD67102D743b8533c1277a4ffdA04Dea158D1)
    +++ description: None
```

## Source code changes

```diff
.../WorldChain_Adapter.sol                         | 121 ++++++++++++++-------
 1 file changed, 84 insertions(+), 37 deletions(-)
```

Generated with discovered.json: 0x6a374b7269092d9f4856136eb52f9a7cb8c8efbc

# Diff at Fri, 23 May 2025 09:40:52 GMT:

- author: Adrian Adamiak (<adrian@adamiak.net>)
- comparing to: main@69cd181abbc3c830a6caf2f4429b37cae72ffdb8 block: 22517852
- current block number: 22517852

## Description

Introduced .role field on each permission, defaulting to field name on which it was defined (with '.' prefix)

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 22517852 (main branch discovery), not current.

```diff
    contract OptimisticGovernor (0x8692B776d1Ff0664177c90465038056Dc64f8991) {
    +++ description: None
      directlyReceivedPermissions.0.role:
+        ".GnosisSafe_modules"
    }
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      receivedPermissions.0.role:
+        "admin"
    }
```

Generated with discovered.json: 0x6e39042f4aa91f926d93b33e393ed4a07a6a61c0

# Diff at Mon, 19 May 2025 15:19:07 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@2ba4be7822b161a6616bac837b3f7f03225f5cb9 block: 22494917
- current block number: 22517852

## Description

Upgrade to the Linea_Adapter to use the general CCTP adapter.

## Watched changes

```diff
-   Status: DELETED
    contract Linea_Adapter (0x7Ea0D1882D610095A45E512B0113f79cA98a8EfE)
    +++ description: None
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.59144:
-        "0x7Ea0D1882D610095A45E512B0113f79cA98a8EfE"
+        "0x5A44A32c13e2C43416bFDE5dDF5DCb3880c42787"
    }
```

```diff
+   Status: CREATED
    contract Linea_Adapter (0x5A44A32c13e2C43416bFDE5dDF5DCb3880c42787)
    +++ description: None
```

## Source code changes

```diff
.../{.flat@22494917 => .flat}/Linea_Adapter.sol    | 157 +++++++++++++++++++--
 1 file changed, 145 insertions(+), 12 deletions(-)
```

Generated with discovered.json: 0x037991be57e22885eb3db5d1e8fde2b0dfbc9871

# Diff at Fri, 16 May 2025 10:03:06 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@9912083f7b773804513e08ee765f8ba71a92980b block: 22397496
- current block number: 22494917

## Description

New Lisk adapter, based on generic OP adapter.

## Watched changes

```diff
-   Status: DELETED
    contract Lisk_Adapter (0x8229E812f20537caA1e8Fb41749b4887B8a75C3B)
    +++ description: None
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.1135:
-        "0x8229E812f20537caA1e8Fb41749b4887B8a75C3B"
+        "0xF039AdCC74936F90fE175e8b3FE0FdC8b8E0c73b"
    }
```

```diff
+   Status: CREATED
    contract Lisk_Adapter (0xF039AdCC74936F90fE175e8b3FE0FdC8b8E0c73b)
    +++ description: None
```

## Source code changes

```diff
.../{.flat@22397496 => .flat}/Lisk_Adapter.sol     | 114 ++++++++++++++++-----
 1 file changed, 87 insertions(+), 27 deletions(-)
```

Generated with discovered.json: 0xfc797ebe64af145b771a746c4334eff6db524485

# Diff at Fri, 02 May 2025 17:23:07 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@c598e33a0c469175b7abbd6c2a13b47b63d6b6a4 block: 22337715
- current block number: 22397496

## Description

ZkStack_CustomGasToken_Adapter upgraded to use native CCTP if enabled.

New Universal_Adapter added with CCTP support, currently not used.

## Watched changes

```diff
-   Status: DELETED
    contract ZkStack_CustomGasToken_Adapter (0x63AC22131eD457aeCbD63e6c4C7eeC7BBC74fF1F)
    +++ description: None
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.232:
-        "0x63AC22131eD457aeCbD63e6c4C7eeC7BBC74fF1F"
+        "0x5e0B7e20a77BDf11812837D30F1326068Bcf24Cf"
      values.Adapters.56:
+        "0x22001f37B586792F25Ef9d19d99537C6446e0833"
      values.CrossChainContracts.56:
+        "0x4e8E101924eDE233C13e2D8622DC8aED2872d505"
    }
```

```diff
+   Status: CREATED
    contract HubPoolStore (0x1Ace3BbD69b63063F859514Eca29C9BDd8310E61)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Universal_Adapter (0x22001f37B586792F25Ef9d19d99537C6446e0833)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ZkStack_CustomGasToken_Adapter (0x5e0B7e20a77BDf11812837D30F1326068Bcf24Cf)
    +++ description: None
```

## Source code changes

```diff
.../across-v3/ethereum/.flat/HubPoolStore.sol      |  72 +++
 .../across-v3/ethereum/.flat/Universal_Adapter.sol | 597 +++++++++++++++++++++
 .../ZkStack_CustomGasToken_Adapter.sol             | 214 +++++++-
 3 files changed, 865 insertions(+), 18 deletions(-)
```

Generated with discovered.json: 0x7f3357bc67f9b24314960dee3b35bbaedcd7e9a4

# Diff at Tue, 29 Apr 2025 08:18:58 GMT:

- author: Adrian Adamiak (<adrian@adamiak.net>)
- comparing to: main@ef7477af00fe0b57a2f7cacf7e958c12494af662 block: 22337715
- current block number: 22337715

## Description

Field .issuedPermissions is removed from the output as no longer needed. Added 'permissionsConfigHash' due to refactoring of the modelling process (into a separate command).

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 22337715 (main branch discovery), not current.

```diff
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5) {
    +++ description: None
      issuedPermissions:
-        [{"permission":"upgrade","to":"0xc186fA914353c44b2E33eBE05f21846F1048bEda","via":[]}]
    }
```

Generated with discovered.json: 0xd2b98cee46be677a29fb7fba20754a4948f35323

# Diff at Thu, 24 Apr 2025 08:36:05 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@f3ec8b7fe4d902b94844aa2f7ddfb2affe4f3f61 block: 22187210
- current block number: 22337715

## Description

Upgrade the scroll adapter.

## Watched changes

```diff
-   Status: DELETED
    contract Scroll_Adapter (0xb6129Ab69aEA75e6884c2D6ecf25293C343C519F)
    +++ description: None
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.534352:
-        "0xb6129Ab69aEA75e6884c2D6ecf25293C343C519F"
+        "0x2DA799c2223c6ffB595e578903AE6b95839160d8"
    }
```

```diff
+   Status: CREATED
    contract Scroll_Adapter (0x2DA799c2223c6ffB595e578903AE6b95839160d8)
    +++ description: None
```

Generated with discovered.json: 0x3af056119078158b8cac1d38813cd3898c8a4fda

# Diff at Thu, 03 Apr 2025 08:31:29 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@ad19dfb413ff34348157f743c194a146b6447e05 block: 22166242
- current block number: 22187210

## Description

Redeploy zkstack adapters.

## Watched changes

```diff
-   Status: DELETED
    contract ZkStack_Adapter (0x3155A91D2EBAe69443B45556e1DE5ed8eB79C90D)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ZkStack_CustomGasToken_Adapter (0x54976794ef6b8d630F27c0F2cCB27bBcEf9aF9D0)
    +++ description: None
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.232:
-        "0x54976794ef6b8d630F27c0F2cCB27bBcEf9aF9D0"
+        "0x63AC22131eD457aeCbD63e6c4C7eeC7BBC74fF1F"
      values.Adapters.324:
-        "0x3155A91D2EBAe69443B45556e1DE5ed8eB79C90D"
+        "0xA374585E6062517Ee367ee5044946A6fBe17724f"
    }
```

```diff
+   Status: CREATED
    contract ZkStack_CustomGasToken_Adapter (0x63AC22131eD457aeCbD63e6c4C7eeC7BBC74fF1F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ZkStack_Adapter (0xA374585E6062517Ee367ee5044946A6fBe17724f)
    +++ description: None
```

Generated with discovered.json: 0xcfeefe518ed2f5050a3169fbf01cd75af43c2632

# Diff at Mon, 31 Mar 2025 10:16:28 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@71ffebe835be10b6d5d09ef65aa19b910de8a2ec block: 22045124
- current block number: 22166242

## Description

Add a second adapter for zkstacks.

## Watched changes

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.232:
+        "0x54976794ef6b8d630F27c0F2cCB27bBcEf9aF9D0"
      values.CrossChainContracts.232:
+        "0xe7cb3e167e7475dE1331Cf6E0CEb187654619E12"
    }
```

```diff
+   Status: CREATED
    contract ZkStack_CustomGasToken_Adapter (0x54976794ef6b8d630F27c0F2cCB27bBcEf9aF9D0)
    +++ description: None
```

## Source code changes

```diff
.../.flat/ZkStack_CustomGasToken_Adapter.sol       | 625 +++++++++++++++++++++
 1 file changed, 625 insertions(+)
```

Generated with discovered.json: 0x0e07582d889b04364a1534217256640cf647864f

# Diff at Fri, 14 Mar 2025 12:33:51 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@a22da884d1a9470186e80799bc96392136af1fbe block: 21802758
- current block number: 22045124

## Description

ZkStack adapter added (replaces ZkSync adapter). Currently targeting the old shared bridge address.

## Watched changes

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.324:
-        "0xE233009838CB898b50e0012a6E783FC9FeE447FB"
+        "0x3155A91D2EBAe69443B45556e1DE5ed8eB79C90D"
    }
```

```diff
-   Status: DELETED
    contract ZkSync_Adapter (0xE233009838CB898b50e0012a6E783FC9FeE447FB)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ZkStack_Adapter (0x3155A91D2EBAe69443B45556e1DE5ed8eB79C90D)
    +++ description: None
```

## Source code changes

```diff
.../ZkStack_Adapter.sol}                           | 214 ++++++++++++---------
 1 file changed, 125 insertions(+), 89 deletions(-)
```

Generated with discovered.json: 0xc753ebcff88fc4ca6a584bd241359bf7e72ae340

# Diff at Tue, 04 Mar 2025 10:38:49 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@98d260b45fe0d2195ce5e629bd7b200c8706e8ba block: 21802758
- current block number: 21802758

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 21802758 (main branch discovery), not current.

```diff
    contract Zora_Adapter (0x024F2fC31CBDD8de17194b1892c834f98Ef5169b) {
    +++ description: None
      sinceBlock:
+        20512287
    }
```

```diff
    contract VotingToken (0x04Fa0d235C4abf4BcF4787aF4CF447DE572eF828) {
    +++ description: None
      sinceBlock:
+        9247089
    }
```

```diff
    contract Soneium_Adapter (0x0c9d064523177dBB55CFE52b9D0c485FBFc35FD2) {
    +++ description: None
      sinceBlock:
+        21597341
    }
```

```diff
    contract Arbitrum_Adapter (0x100EDfCf3af2B4625Fca4EaF6C533703e71F7210) {
    +++ description: None
      sinceBlock:
+        21237154
    }
```

```diff
    contract Redstone_Adapter (0x188F8C95B7cfB7993B53a4F643efa687916f73fA) {
    +++ description: None
      sinceBlock:
+        20432774
    }
```

```diff
    contract Boba_Adapter (0x33B0Ec794c15D6Cc705818E70d4CaCe7bCfB5Af3) {
    +++ description: None
      sinceBlock:
+        14716798
    }
```

```diff
    contract AcrossConfigStore (0x3B03509645713718B78951126E0A6de6f10043f5) {
    +++ description: None
      sinceBlock:
+        14717196
    }
```

```diff
    contract Finder (0x40f941E48A552bF496B154Af6bf55725f18D77c3) {
    +++ description: None
      sinceBlock:
+        9247083
    }
```

```diff
    contract PolygonTokenBridger (0x48d990AbDA20afa1fD1da713AbC041B60a922c65) {
    +++ description: None
      sinceBlock:
+        14704448
    }
```

```diff
    contract ProposerV2 (0x50efaC9619225d7fB4703C5872da978849B6E7cC) {
    +++ description: None
      sinceBlock:
+        16697363
    }
```

```diff
    contract Ethereum_Adapter (0x527E872a5c3f0C7c24Fe33F2593cFB890a285084) {
    +++ description: None
      sinceBlock:
+        14704381
    }
```

```diff
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5) {
    +++ description: None
      sinceBlock:
+        17117454
    }
```

```diff
    contract Alephzero_Adapter (0x6F4083304C2cA99B077ACE06a5DcF670615915Af) {
    +++ description: None
      sinceBlock:
+        21131132
    }
```

```diff
    contract GovernorV2 (0x7b292034084A41B9D441B71b6E3557Edd0463fa8) {
    +++ description: None
      sinceBlock:
+        16697276
    }
```

```diff
    contract LpTokenFactory (0x7dB69eb9F52eD773E9b03f5068A1ea0275b2fD9d) {
    +++ description: None
      sinceBlock:
+        14704307
    }
```

```diff
    contract Ink_Adapter (0x7e90A40c7519b041A7DF6498fBf5662e8cFC61d2) {
    +++ description: None
      sinceBlock:
+        21438590
    }
```

```diff
    contract Linea_Adapter (0x7Ea0D1882D610095A45E512B0113f79cA98a8EfE) {
    +++ description: None
      sinceBlock:
+        19402413
    }
```

```diff
    contract EmergencyProposalExecutor (0x8180D59b7175d4064bDFA8138A58e9baBFFdA44a) {
    +++ description: None
      sinceBlock:
+        10688070
    }
```

```diff
    contract Lisk_Adapter (0x8229E812f20537caA1e8Fb41749b4887B8a75C3B) {
    +++ description: None
      sinceBlock:
+        20184545
    }
```

```diff
    contract OptimisticGovernor (0x8692B776d1Ff0664177c90465038056Dc64f8991) {
    +++ description: None
      sinceBlock:
+        17176107
    }
```

```diff
    contract EmergencyProposer (0x91F1804aCaf87C2D34A34A70be1bb16bB85D6748) {
    +++ description: None
      sinceBlock:
+        16697394
    }
```

```diff
    contract WorldChain_Adapter (0xA8399e221a583A57F54Abb5bA22f31b5D6C09f32) {
    +++ description: None
      sinceBlock:
+        20963234
    }
```

```diff
    contract Polygon_Adapter (0xb4AeF0178f5725392A26eE18684C2aB62adc912e) {
    +++ description: None
      sinceBlock:
+        19915066
    }
```

```diff
    contract HubPool Multisig (0xB524735356985D2f267FA010D681f061DfF03715) {
    +++ description: None
      sinceBlock:
+        13559776
    }
```

```diff
    contract Scroll_Adapter (0xb6129Ab69aEA75e6884c2D6ecf25293C343C519F) {
    +++ description: None
      sinceBlock:
+        20318360
    }
```

```diff
    contract CoveredCallFinancialProductLibrary (0xBbc6009fEfFc27ce705322832Cb2068F8C1e0A58) {
    +++ description: None
      sinceBlock:
+        12234012
    }
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      sinceBlock:
+        14819537
    }
```

```diff
    contract Base_Adapter (0xE1421233BF7158A19f89F17c9735F9cbd3D9529c) {
    +++ description: None
      sinceBlock:
+        19915087
    }
```

```diff
    contract Optimism_Adapter (0xE1e74B3D6A8E2A479B62958D4E4E6eEaea5B612b) {
    +++ description: None
      sinceBlock:
+        19915034
    }
```

```diff
    contract ZkSync_Adapter (0xE233009838CB898b50e0012a6E783FC9FeE447FB) {
    +++ description: None
      sinceBlock:
+        17842162
    }
```

```diff
    contract BondToken (0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea) {
    +++ description: None
      sinceBlock:
+        17980554
    }
```

```diff
    contract UMAOptimisticOracle (0xeE3Afe347D5C74317041E2618C49534dAf887c24) {
    +++ description: None
      sinceBlock:
+        13545034
    }
```

```diff
    contract Mode_Adapter (0xf1B59868697f3925b72889ede818B9E7ba0316d0) {
    +++ description: None
      sinceBlock:
+        19914094
    }
```

```diff
    contract Blast_Adapter (0xF2bEf5E905AAE0295003ab14872F811E914EdD81) {
    +++ description: None
      sinceBlock:
+        20221494
    }
```

```diff
    contract DoctorWho_Adapter (0xFADcC43096756e1527306FD92982FEbBe3c629Fa) {
    +++ description: None
      sinceBlock:
+        21773451
    }
```

```diff
    contract OptimisticOracleV3 (0xfb55F43fB9F48F63f9269DB7Dde3BbBe1ebDC0dE) {
    +++ description: None
      sinceBlock:
+        16636058
    }
```

Generated with discovered.json: 0xc81c768c833157376bd8b452462bae64089944f3

# Diff at Sat, 08 Feb 2025 15:50:47 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@ef01ea79812e0d524af00be3fae1170cef6fd662 block: 21786466
- current block number: 21802758

## Description

Upgrade of the ethereum spoke pool: Refactor that mainly switches previous `address` types to `bytes32` and renames / merges some functions.

## Watched changes

```diff
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5) {
    +++ description: None
      sourceHashes.1:
-        "0xf5ec60450a251965f87d58578708ae6f3718afe7721e152b6983ca8d18ec3362"
+        "0x10d81ccfd26fbcb9926942a46436a7bedd3946646911a43f3f0e13dc7eb81517"
      values.$implementation:
-        "0xD576931ab0bDC3dfdc2c041d3C7b9d2ED0c6dd9a"
+        "0x0190a2328e072Fc5a7fA00F6C9ae2a16c7F4E32a"
      values.$pastUpgrades.8:
+        ["2025-02-07T14:46:47.000Z","0xbea88935fe99b6faba60ee273a5eb146cd6c2d12decfef8842c5c719a0009376",["0x0190a2328e072Fc5a7fA00F6C9ae2a16c7F4E32a"]]
      values.$upgradeCount:
-        8
+        9
      values.EMPTY_RELAYER:
-        "0x0000000000000000000000000000000000000000"
+        "0x0000000000000000000000000000000000000000000000000000000000000000"
      values.UPDATE_V3_DEPOSIT_DETAILS_HASH:
-        "0x152eb71524aef34d838ab76573c14b1ebfa5e385d9ab29d7cf5398daa2438bd9"
      values.MAX_EXCLUSIVITY_PERIOD_SECONDS:
+        31536000
      values.UPDATE_ADDRESS_DEPOSIT_DETAILS_HASH:
+        "0x9c6dfd61d811b9950a4f2b9adf46357b717c816d22c420d0bde8f2360148f7cd"
      values.UPDATE_BYTES32_DEPOSIT_DETAILS_HASH:
+        "0x8d1994e2bbbd77564cdca06dd819e7ee2a5efa06c80dcb59a4a7b6e39edc538f"
    }
```

## Source code changes

```diff
.../Ethereum_SpokePool/Ethereum_SpokePool.sol      | 1128 +++++++++++++++-----
 1 file changed, 856 insertions(+), 272 deletions(-)
```

Generated with discovered.json: 0xc1e43b3b90793a3739173b71a2c7dce6122f42ca

# Diff at Thu, 06 Feb 2025 09:08:42 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@fa699ce266b15edb364aa471a661f580ea1a4529 block: 21736634
- current block number: 21786466

## Description

Adapter for Doctor Who (??) deployed, not yet in use.

## Watched changes

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.130:
+        "0xFADcC43096756e1527306FD92982FEbBe3c629Fa"
      values.CrossChainContracts.130:
+        "0x09aea4b2242abC8bb4BB78D537A67a245A7bEC64"
    }
```

```diff
+   Status: CREATED
    contract DoctorWho_Adapter (0xFADcC43096756e1527306FD92982FEbBe3c629Fa)
    +++ description: None
```

## Source code changes

```diff
.../across-v3/ethereum/.flat/DoctorWho_Adapter.sol | 588 +++++++++++++++++++++
 1 file changed, 588 insertions(+)
```

Generated with discovered.json: 0xaa2d1977472327aec38f40d945810841efd7dcc8

# Diff at Thu, 30 Jan 2025 10:04:12 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@2da0612158e4fa23c41926c49e88a7b955a8c5dc block: 21628877
- current block number: 21736634

## Description

Minor upgrade to the Ethereum SpokePool, `hubPool` now called `withdrawalRecipient`.

## Watched changes

```diff
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5) {
    +++ description: None
      sourceHashes.1:
-        "0x7bae4a313d267e381b0aa01e463be4435e016d0c53c26b0f4136d4caa180fa88"
+        "0xf5ec60450a251965f87d58578708ae6f3718afe7721e152b6983ca8d18ec3362"
      values.$implementation:
-        "0x48Dcf75EA18233BA947E4480dCd70594720449C1"
+        "0xD576931ab0bDC3dfdc2c041d3C7b9d2ED0c6dd9a"
      values.$pastUpgrades.7:
+        ["2025-01-29T00:44:11.000Z","0x4d37ad20bb31cedba7434223e08229ca95fbfd32eaf2bcbd456af0d0a32bba8b",["0xD576931ab0bDC3dfdc2c041d3C7b9d2ED0c6dd9a"]]
      values.$upgradeCount:
-        7
+        8
      values.hubPool:
-        "0xc186fA914353c44b2E33eBE05f21846F1048bEda"
      values.withdrawalRecipient:
+        "0xc186fA914353c44b2E33eBE05f21846F1048bEda"
    }
```

## Source code changes

```diff
.../Ethereum_SpokePool/Ethereum_SpokePool.sol      | 249 ++++++++++-----------
 1 file changed, 118 insertions(+), 131 deletions(-)
```

Generated with discovered.json: 0x1608f8395ca3960349c8322a8a60274fdea21e37

# Diff at Mon, 20 Jan 2025 11:09:12 GMT:

- author: Adrian Adamiak (<adrian@adamiak.net>)
- comparing to: main@2c8b4f3d9910bb6371be9b4df87b70856e7d8c64 block: 21628877
- current block number: 21628877

## Description

Rerun on the same block number. Applies fixes to permissions and via field. Renames permission's target to to/from.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 21628877 (main branch discovery), not current.

```diff
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5) {
    +++ description: None
      issuedPermissions.0.target:
-        "0xc186fA914353c44b2E33eBE05f21846F1048bEda"
      issuedPermissions.0.to:
+        "0xc186fA914353c44b2E33eBE05f21846F1048bEda"
    }
```

```diff
    contract OptimisticGovernor (0x8692B776d1Ff0664177c90465038056Dc64f8991) {
    +++ description: None
      directlyReceivedPermissions.0.target:
-        "0xB524735356985D2f267FA010D681f061DfF03715"
      directlyReceivedPermissions.0.from:
+        "0xB524735356985D2f267FA010D681f061DfF03715"
    }
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      receivedPermissions.0.target:
-        "0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5"
      receivedPermissions.0.from:
+        "0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5"
    }
```

Generated with discovered.json: 0x0f35b730661bd82dbea92413045a93d136735522

# Diff at Wed, 15 Jan 2025 09:06:12 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@3ea176aee1470e5ec80e65adfc81a954f84584d8 block: 21543430
- current block number: 21628877

## Description

Soneium adapter added.

## Watched changes

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.1868:
+        "0x0c9d064523177dBB55CFE52b9D0c485FBFc35FD2"
      values.CrossChainContracts.1868:
+        "0x3baD7AD0728f9917d1Bf08af5782dCbD516cDd96"
    }
```

```diff
+   Status: CREATED
    contract Soneium_Adapter (0x0c9d064523177dBB55CFE52b9D0c485FBFc35FD2)
    +++ description: None
```

## Source code changes

```diff
.../across-v3/ethereum/.flat/Soneium_Adapter.sol   | 596 +++++++++++++++++++++
 1 file changed, 596 insertions(+)
```

Generated with discovered.json: 0x4a75fdca8455fbd7d6fb3c4a66c4947552961416

# Diff at Fri, 03 Jan 2025 10:43:13 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@f2f208ac8a91552305da5e03332108446838b892 block: 21388072
- current block number: 21543430

## Description

New Arbitrum_Adapter: No changes  except for comments.

New standard OP_Adapter for the Ink RU.

## Watched changes

```diff
-   Status: DELETED
    contract Arbitrum_Adapter (0x5473CBD30bEd1Bf97C0c9d7c59d268CD620dA426)
    +++ description: None
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.42161:
-        "0x5473CBD30bEd1Bf97C0c9d7c59d268CD620dA426"
+        "0x100EDfCf3af2B4625Fca4EaF6C533703e71F7210"
      values.Adapters.57073:
+        "0x7e90A40c7519b041A7DF6498fBf5662e8cFC61d2"
      values.CrossChainContracts.57073:
+        "0xeF684C38F94F48775959ECf2012D7E864ffb9dd4"
    }
```

```diff
+   Status: CREATED
    contract Arbitrum_Adapter (0x100EDfCf3af2B4625Fca4EaF6C533703e71F7210)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Ink_Adapter (0x7e90A40c7519b041A7DF6498fBf5662e8cFC61d2)
    +++ description: None
```

## Source code changes

```diff
.../{.flat@21388072 => .flat}/Arbitrum_Adapter.sol |  10 +
 .../across-v3/ethereum/.flat/Ink_Adapter.sol       | 596 +++++++++++++++++++++
 2 files changed, 606 insertions(+)
```

Generated with discovered.json: 0x5cf4cef23f0cb03295260afbe5b50fdd11ebf6d1

# Diff at Thu, 12 Dec 2024 17:59:11 GMT:

- author: vincfurc (<10850139+vincfurc@users.noreply.github.com>)
- comparing to: main@fa5a98638066331a8ea6329a256a3462e7da2b3a block: 21142111
- current block number: 21388072

## Description

Ignored current time value.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 21142111 (main branch discovery), not current.

```diff
    contract UMAOptimisticOracle (0xeE3Afe347D5C74317041E2618C49534dAf887c24) {
    +++ description: None
      values.getCurrentTime:
-        1731059123
    }
```

Generated with discovered.json: 0x6e237fc3e7c6a0dfacdf8c3facadcfce1cd29744

# Diff at Tue, 10 Dec 2024 10:36:39 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@9ed5a41ddcad978cfdf826bc7a4827bf4a91c814 block: 21142111
- current block number: 21142111

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 21142111 (main branch discovery), not current.

```diff
+   Status: CREATED
    contract AcrossConfigStore (0x3B03509645713718B78951126E0A6de6f10043f5)
    +++ description: None
```

```diff
+   Status: CREATED
    contract PolygonTokenBridger (0x48d990AbDA20afa1fD1da713AbC041B60a922c65)
    +++ description: None
```

```diff
+   Status: CREATED
    contract UMAOptimisticOracle (0xeE3Afe347D5C74317041E2618C49534dAf887c24)
    +++ description: None
```

Generated with discovered.json: 0x52dadfca973170d723ce40d572f31cce6594232a

# Diff at Fri, 08 Nov 2024 09:45:41 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@53988239f42edde0275ed92d8f3ada4279354f7d block: 20997757
- current block number: 21142111

## Description

Alephzero adapter added.

## Watched changes

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.41455:
+        "0x6F4083304C2cA99B077ACE06a5DcF670615915Af"
      values.CrossChainContracts.41455:
+        "0x13fDac9F9b4777705db45291bbFF3c972c6d1d97"
    }
```

```diff
+   Status: CREATED
    contract Alephzero_Adapter (0x6F4083304C2cA99B077ACE06a5DcF670615915Af)
    +++ description: None
```

## Source code changes

```diff
.../across-v3/ethereum/.flat/Alephzero_Adapter.sol | 711 +++++++++++++++++++++
 1 file changed, 711 insertions(+)
```

Generated with discovered.json: 0x06759bc3145293933667947d7cb0ef0a871d648b

# Diff at Mon, 21 Oct 2024 11:03:42 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@8895d33866f5665c4c710f4ddaa32bfa63cc3c78 block: 20997757
- current block number: 20997757

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20997757 (main branch discovery), not current.

```diff
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5) {
    +++ description: None
      values.$pastUpgrades.6.2:
+        ["0x48Dcf75EA18233BA947E4480dCd70594720449C1"]
      values.$pastUpgrades.6.1:
-        ["0x48Dcf75EA18233BA947E4480dCd70594720449C1"]
+        "0xd3cfc5a7476fd33d3d3fdc2d77adac2bf6900945f9a5c5f35f65b6507dde381f"
      values.$pastUpgrades.5.2:
+        ["0x08C21b200eD06D2e32cEC91a770C3FcA8aD5F877"]
      values.$pastUpgrades.5.1:
-        ["0x08C21b200eD06D2e32cEC91a770C3FcA8aD5F877"]
+        "0xa604480755748d8162a3fb11442719682d473d868450e7460d9dd111a0b8903a"
      values.$pastUpgrades.4.2:
+        ["0xa4D3535f33549749Fb97fA42903AC80F6fb54af6"]
      values.$pastUpgrades.4.1:
-        ["0xa4D3535f33549749Fb97fA42903AC80F6fb54af6"]
+        "0x3ebfeeedb62ab726a1cb350595df3d4b2212f2fda619ae08015d16f304fc8332"
      values.$pastUpgrades.3.2:
+        ["0x90438AD3d81a0739ce1Cb20C73564682388c5FdD"]
      values.$pastUpgrades.3.1:
-        ["0x90438AD3d81a0739ce1Cb20C73564682388c5FdD"]
+        "0xf08778addb8376b0beb500bf569c6251eadc124e6aeeaf5f702ab1dbf576379f"
      values.$pastUpgrades.2.2:
+        ["0x5ab0A812327aD959dE664AEC8408Ef8c6ABe7184"]
      values.$pastUpgrades.2.1:
-        ["0x5ab0A812327aD959dE664AEC8408Ef8c6ABe7184"]
+        "0x946dec56639129cadd298ce5a44341b6f361c5c632f5dea2a80d9cb023b836c6"
      values.$pastUpgrades.1.2:
+        ["0x326510c1bf9d85Fb73d0AB8d20Aa5BbE9c7561e9"]
      values.$pastUpgrades.1.1:
-        ["0x326510c1bf9d85Fb73d0AB8d20Aa5BbE9c7561e9"]
+        "0xceb5b11cd6c78b29d16d2c91bedcb4ec7467814fdce84a753f468c452c36c0d6"
      values.$pastUpgrades.0.2:
+        ["0xA667498F46457548f1D3ad557340b95Fdb290148"]
      values.$pastUpgrades.0.1:
-        ["0xA667498F46457548f1D3ad557340b95Fdb290148"]
+        "0x411ae8360c51beff3d6034ea63f03c41e6cf8b031432391fc44bc4f5a1b908ef"
    }
```

Generated with discovered.json: 0x6d36103492d2f52e6253b8f9e2d07b73b4c8b5e5

# Diff at Sat, 19 Oct 2024 06:15:10 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@493c96785a6a32c6417182bb9548d3a990297dbe block: 20934032
- current block number: 20997757

## Description

Minor upgrade of the WorldChain Adapter to support their custom USDC escrow.

## Watched changes

```diff
-   Status: DELETED
    contract WorldChain_Adapter (0x8eBebfc894047bEE213A561b8792fCa71241731f)
    +++ description: None
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.480:
-        "0x8eBebfc894047bEE213A561b8792fCa71241731f"
+        "0xA8399e221a583A57F54Abb5bA22f31b5D6C09f32"
    }
```

```diff
+   Status: CREATED
    contract WorldChain_Adapter (0xA8399e221a583A57F54Abb5bA22f31b5D6C09f32)
    +++ description: None
```

## Source code changes

```diff
.../WorldChain_Adapter.sol                         | 25 +++++++++++++---------
 1 file changed, 15 insertions(+), 10 deletions(-)
```

Generated with discovered.json: 0xd7ff53370050b4046ea7e36258229abf1541932b

# Diff at Fri, 18 Oct 2024 10:53:31 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@0295165a89d86b7450439f24f100d1baa74381fc block: 20934032
- current block number: 20934032

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20934032 (main branch discovery), not current.

```diff
    contract OptimisticGovernor (0x8692B776d1Ff0664177c90465038056Dc64f8991) {
    +++ description: None
      directlyReceivedPermissions:
+        [{"permission":"act","target":"0xB524735356985D2f267FA010D681f061DfF03715"}]
    }
```

Generated with discovered.json: 0xd724021c94c1d6affef9e3b5adf59952c248f1fb

# Diff at Mon, 14 Oct 2024 10:48:32 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@1afc77ff111ceb0970e7d09efcc7b2f376b0c281 block: 20934032
- current block number: 20934032

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20934032 (main branch discovery), not current.

```diff
    contract Zora_Adapter (0x024F2fC31CBDD8de17194b1892c834f98Ef5169b) {
    +++ description: None
      sourceHashes:
+        ["0x6d9e4b79712a4e81c51941fb986f4c55774da36be108106577ca01ccb35a0f87"]
    }
```

```diff
    contract VotingToken (0x04Fa0d235C4abf4BcF4787aF4CF447DE572eF828) {
    +++ description: None
      sourceHashes:
+        ["0x349b0f612f02a8599667c43efe1e547bf4f18a46732001b3afb6b425a87325e9"]
    }
```

```diff
    contract Redstone_Adapter (0x188F8C95B7cfB7993B53a4F643efa687916f73fA) {
    +++ description: None
      sourceHashes:
+        ["0x0c32a0cfde3cb87843b5521bf184be1dd2b0031a8e91c2bc7885a2e10db010c1"]
    }
```

```diff
    contract Boba_Adapter (0x33B0Ec794c15D6Cc705818E70d4CaCe7bCfB5Af3) {
    +++ description: None
      sourceHashes:
+        ["0x9f8b082009430546d55daaa8e166eca77ef9ca17f7831f03de4635bdc4a32b31"]
    }
```

```diff
    contract Finder (0x40f941E48A552bF496B154Af6bf55725f18D77c3) {
    +++ description: None
      sourceHashes:
+        ["0x6b81a32a0de6b3e8ed743f089a6518d3791b0e4d373300269439642482338ddb"]
    }
```

```diff
    contract ProposerV2 (0x50efaC9619225d7fB4703C5872da978849B6E7cC) {
    +++ description: None
      sourceHashes:
+        ["0x28c93f7b68e31548857633c6cb61284d9d2860cc0fbbcaaede8f631d364d66a4"]
    }
```

```diff
    contract Ethereum_Adapter (0x527E872a5c3f0C7c24Fe33F2593cFB890a285084) {
    +++ description: None
      sourceHashes:
+        ["0x14afbe84cefefdcb06132c680d267b8892f0834a39fc23ca0ea563758653a21a"]
    }
```

```diff
    contract Arbitrum_Adapter (0x5473CBD30bEd1Bf97C0c9d7c59d268CD620dA426) {
    +++ description: None
      sourceHashes:
+        ["0xa1c171564a6e837069132a07b8c6d217e08cf53cd6a43151a7f497440d2f1e33"]
    }
```

```diff
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5) {
    +++ description: None
      sourceHashes:
+        ["0x669da4e91a9ad0ca23205a174e7f8931e4d7d128453132164ba6458f11f15c72","0x7bae4a313d267e381b0aa01e463be4435e016d0c53c26b0f4136d4caa180fa88"]
    }
```

```diff
    contract GovernorV2 (0x7b292034084A41B9D441B71b6E3557Edd0463fa8) {
    +++ description: None
      sourceHashes:
+        ["0xdf7f17e5c8ba1f0103fcfaf495da624089f8bfb3d5052217537bb064ca8c60b9"]
    }
```

```diff
    contract LpTokenFactory (0x7dB69eb9F52eD773E9b03f5068A1ea0275b2fD9d) {
    +++ description: None
      sourceHashes:
+        ["0x54ab5e1f981929fca37e28c313db9ab35343de3df6907dbaeb29dda3840aadcd"]
    }
```

```diff
    contract Linea_Adapter (0x7Ea0D1882D610095A45E512B0113f79cA98a8EfE) {
    +++ description: None
      sourceHashes:
+        ["0x6cc7cfdaa6b4d79d35a624dafc13713137f61d46c6536a4837a2793c3fa3fc4d"]
    }
```

```diff
    contract EmergencyProposalExecutor (0x8180D59b7175d4064bDFA8138A58e9baBFFdA44a) {
    +++ description: None
      sourceHashes:
+        ["0xd5a33441170541b7df25812e0e3dff6562b2f09ab835a6b431cb9e7198a47605","0xd42bbf9f7dcd3720a7fc6bdc6edfdfae8800a37d6dd4decfa0ef6ca4a2e88940"]
    }
```

```diff
    contract Lisk_Adapter (0x8229E812f20537caA1e8Fb41749b4887B8a75C3B) {
    +++ description: None
      sourceHashes:
+        ["0x4d929bc632eff7818792b2ad5539b8b5dbc8842e7d23c9d9bfb116acb05eb96a"]
    }
```

```diff
    contract OptimisticGovernor (0x8692B776d1Ff0664177c90465038056Dc64f8991) {
    +++ description: None
      sourceHashes:
+        ["0xcecd27c998c8fd83d7532693da2bdff346a1dbedbaab4744f21d2bcf1986e9de"]
    }
```

```diff
    contract WorldChain_Adapter (0x8eBebfc894047bEE213A561b8792fCa71241731f) {
    +++ description: None
      sourceHashes:
+        ["0xa2716832109570351047beb288a3a96a17d443cc548980a1327bb59729b74efe"]
    }
```

```diff
    contract EmergencyProposer (0x91F1804aCaf87C2D34A34A70be1bb16bB85D6748) {
    +++ description: None
      sourceHashes:
+        ["0x435ceb597bcf7bd820f593bdbc0e3ce4d223cc2203b368911d2b29fa6bc5e048"]
    }
```

```diff
    contract Polygon_Adapter (0xb4AeF0178f5725392A26eE18684C2aB62adc912e) {
    +++ description: None
      sourceHashes:
+        ["0xf598be4ed345b6b3e83e04dff2cb5472dc4df0b8476f8f74a4c75c473dee6347"]
    }
```

```diff
    contract HubPool Multisig (0xB524735356985D2f267FA010D681f061DfF03715) {
    +++ description: None
      sourceHashes:
+        ["0x81a7349eebb98ac33b0bc6842e3cb258034a8f2a4ba004570bb8e2e25947f9ff","0xd42bbf9f7dcd3720a7fc6bdc6edfdfae8800a37d6dd4decfa0ef6ca4a2e88940"]
    }
```

```diff
    contract Scroll_Adapter (0xb6129Ab69aEA75e6884c2D6ecf25293C343C519F) {
    +++ description: None
      sourceHashes:
+        ["0x56586e3315f76ed277970410b47da25a0980ca9400f2a97fd38139e2a1f2dc5e"]
    }
```

```diff
    contract CoveredCallFinancialProductLibrary (0xBbc6009fEfFc27ce705322832Cb2068F8C1e0A58) {
    +++ description: None
      sourceHashes:
+        ["0x626fc280735c432e9187554bc59d556389dc73435f1b570e64f424d257f68d09"]
    }
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      sourceHashes:
+        ["0x3afa0a01f4cde6c678d6ec12443078407e69293b9a4519105445f694671b2dec"]
    }
```

```diff
    contract Base_Adapter (0xE1421233BF7158A19f89F17c9735F9cbd3D9529c) {
    +++ description: None
      sourceHashes:
+        ["0x172a1f27f0fecf665d90a6adc1287223f05a73acd9ed19d9c446972880ccce0f"]
    }
```

```diff
    contract Optimism_Adapter (0xE1e74B3D6A8E2A479B62958D4E4E6eEaea5B612b) {
    +++ description: None
      sourceHashes:
+        ["0x59784b70d01278196c00fbfe1f237b01ec891dca28b0542cdf8dcc9e672b3849"]
    }
```

```diff
    contract ZkSync_Adapter (0xE233009838CB898b50e0012a6E783FC9FeE447FB) {
    +++ description: None
      sourceHashes:
+        ["0xc4f838b87ec9ed41b647f7d3a4a508abdb28aef5a4908a9e0829ccb37f319cc8"]
    }
```

```diff
    contract BondToken (0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea) {
    +++ description: None
      sourceHashes:
+        ["0x1d9754ae4e99e4320201bbc6f0e19aa5ecac917dcacaadba3b70cfa018910754"]
    }
```

```diff
    contract Mode_Adapter (0xf1B59868697f3925b72889ede818B9E7ba0316d0) {
    +++ description: None
      sourceHashes:
+        ["0x1b1b271fd3f736024fda7dd869d78943819efee5dcbf6f4075af9647cfb16cac"]
    }
```

```diff
    contract Blast_Adapter (0xF2bEf5E905AAE0295003ab14872F811E914EdD81) {
    +++ description: None
      sourceHashes:
+        ["0x596bdc0b39f0ff19cde625424cdc037dd3e79355ee2c845bd8a6e5e42b3bc332"]
    }
```

```diff
    contract OptimisticOracleV3 (0xfb55F43fB9F48F63f9269DB7Dde3BbBe1ebDC0dE) {
    +++ description: None
      sourceHashes:
+        ["0xfb2c9056673690384bb615fd326655f97b80fa2a5601a15a35065b0a68186ae7"]
    }
```

Generated with discovered.json: 0x38aad1481151a89c2ea4d20c9aef1cf3d10e0e3d

# Diff at Thu, 10 Oct 2024 08:32:18 GMT:

- author: sekuba (<sekuba@users.noreply.github.com>)
- comparing to: main@cb5ff535ffc194baf7396bd6db8232883e2ad088 block: 20675639
- current block number: 20934032

## Description

New Hub added (Worldchain).

## Watched changes

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.480:
+        "0x8eBebfc894047bEE213A561b8792fCa71241731f"
      values.CrossChainContracts.480:
+        "0x09aea4b2242abC8bb4BB78D537A67a245A7bEC64"
    }
```

```diff
+   Status: CREATED
    contract WorldChain_Adapter (0x8eBebfc894047bEE213A561b8792fCa71241731f)
    +++ description: None
```

## Source code changes

```diff
.../ethereum/.flat/WorldChain_Adapter.sol          | 591 +++++++++++++++++++++
 1 file changed, 591 insertions(+)
```

Generated with discovered.json: 0xfd768f13b611e4a0af3411019ac6f2f75bea7357

# Diff at Tue, 01 Oct 2024 10:49:24 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@bd754dc73c66120164006054f8d25c5fae9cd910 block: 20675639
- current block number: 20675639

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20675639 (main branch discovery), not current.

```diff
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5) {
    +++ description: None
      values.$pastUpgrades:
+        [["2023-04-24T16:52:35.000Z",["0xA667498F46457548f1D3ad557340b95Fdb290148"]],["2023-08-22T00:20:59.000Z",["0x326510c1bf9d85Fb73d0AB8d20Aa5BbE9c7561e9"]],["2023-10-03T13:48:47.000Z",["0x5ab0A812327aD959dE664AEC8408Ef8c6ABe7184"]],["2024-02-21T18:04:23.000Z",["0x90438AD3d81a0739ce1Cb20C73564682388c5FdD"]],["2024-03-18T13:40:47.000Z",["0xa4D3535f33549749Fb97fA42903AC80F6fb54af6"]],["2024-05-15T15:11:59.000Z",["0x08C21b200eD06D2e32cEC91a770C3FcA8aD5F877"]],["2024-09-03T15:48:23.000Z",["0x48Dcf75EA18233BA947E4480dCd70594720449C1"]]]
    }
```

Generated with discovered.json: 0x2a73e7d79017ef77856103254e8631297be55635

# Diff at Wed, 04 Sep 2024 07:12:24 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@878a951312cec062f5003f6749f781861b0cdba1 block: 20532552
- current block number: 20675639

## Description

Small implementation upgrade of the Ethereum Spoke Pool:
* depositExclusive(): Public method that allows users to set an exclusive relayer for their deposit for a certain time. (Any relayer can fulfill the request at the destination after `exclusivityDeadlineOffset` passes)

## Watched changes

```diff
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5) {
    +++ description: None
      values.$implementation:
-        "0x08C21b200eD06D2e32cEC91a770C3FcA8aD5F877"
+        "0x48Dcf75EA18233BA947E4480dCd70594720449C1"
      values.$upgradeCount:
-        6
+        7
    }
```

## Source code changes

```diff
.../Ethereum_SpokePool/Ethereum_SpokePool.sol      | 95 +++++++++++++++++++++-
 1 file changed, 93 insertions(+), 2 deletions(-)
```

Generated with discovered.json: 0x5505aceb59200d22be98a33c394b380e7a23c7cf

# Diff at Fri, 30 Aug 2024 07:50:52 GMT:

- author: Adrian Adamiak (<adrian@adamiak.net>)
- comparing to: main@6c1bd1f41fadf5f2cb1c1805b5a2c6138a3ed35a block: 20532552
- current block number: 20532552

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20532552 (main branch discovery), not current.

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      receivedPermissions.0.via:
-        []
    }
```

Generated with discovered.json: 0x8e35f31d9d10c1b7228c85a0ffc973980ed619c0

# Diff at Fri, 23 Aug 2024 09:50:52 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@67597c7d6c810bc726594446890178150240711e block: 20532552
- current block number: 20532552

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20532552 (main branch discovery), not current.

```diff
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5) {
    +++ description: None
      values.$upgradeCount:
+        6
    }
```

Generated with discovered.json: 0x25083660ffed581d9a0044fec9d4ec63fdf6a3d8

# Diff at Wed, 21 Aug 2024 10:01:38 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@2f6dde3357bf5d79196b6e94f79d853a6c4ec72b block: 20532552
- current block number: 20532552

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20532552 (main branch discovery), not current.

```diff
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5) {
    +++ description: None
      issuedPermissions:
+        [{"permission":"upgrade","target":"0xc186fA914353c44b2E33eBE05f21846F1048bEda","via":[]}]
    }
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      assignedPermissions:
-        {"upgrade":["0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5"]}
      receivedPermissions:
+        [{"permission":"upgrade","target":"0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5","via":[]}]
    }
```

Generated with discovered.json: 0xf27ee85934c0dc2fbfecd1d1d8da4503777c5497

# Diff at Thu, 15 Aug 2024 07:31:34 GMT:

- author: Radina Talanova (<nt.radina@gmail.com>)
- comparing to: main@9a07aead4b3726cc622f66fe9a15e06e63af7acd block: 20518997
- current block number: 20532552

## Description

New adapter and L2 crosschain target for Zora were added.

## Watched changes

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.7777777:
+        "0x024F2fC31CBDD8de17194b1892c834f98Ef5169b"
      values.CrossChainContracts.7777777:
+        "0x13fDac9F9b4777705db45291bbFF3c972c6d1d97"
    }
```

```diff
+   Status: CREATED
    contract Zora_Adapter (0x024F2fC31CBDD8de17194b1892c834f98Ef5169b)
    +++ description: None
```

## Source code changes

```diff
.../across-v3/ethereum/.flat/Zora_Adapter.sol      | 590 +++++++++++++++++++++
 1 file changed, 590 insertions(+)
```

Generated with discovered.json: 0xe9a9d7fdf87c58268c0949602f8942688583b6ab

# Diff at Tue, 13 Aug 2024 10:06:57 GMT:

- author: Radina Talanova (<nt.radina@gmail.com>)
- comparing to: main@8b923f6edf399d43a5cd7f331708956dce3e83d1 block: 20482283
- current block number: 20518997

## Description

The Spoke pool (used for liquidity on the destination chains) was changed for the Redstone Adapter.

## Watched changes

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.CrossChainContracts.690:
-        "0x28077B47Cd03326De7838926A63699849DD4fa87"
+        "0x13fDac9F9b4777705db45291bbFF3c972c6d1d97"
    }
```

Generated with discovered.json: 0x268645e90c13973d8d0e1a6b1dd839737c270f02

# Diff at Fri, 09 Aug 2024 10:08:18 GMT:

- author: Mateusz Radomski (<radomski.main@protonmail.com>)
- comparing to: main@1f0da1d0aab7bc6b3b5e54e7e93480bd98e57035 block: 20482283
- current block number: 20482283

## Description

Discovery rerun on the same block number with only config-related changes.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20482283 (main branch discovery), not current.

```diff
    contract EmergencyProposalExecutor (0x8180D59b7175d4064bDFA8138A58e9baBFFdA44a) {
    +++ description: None
      values.$multisigThreshold:
-        "2 of 4 (50%)"
      values.getOwners:
-        ["0x363605C0bdE9F1F5053aDA30618d95dbFc109Bf5","0xcc400c09ecBAC3e0033e4587BdFAABB26223e37d","0x1d933Fd71FF07E69f066d50B39a7C34EB3b69F05","0x837219D7a9C666F5542c4559Bf17D7B804E5c5fe"]
      values.getThreshold:
-        2
      values.$members:
+        ["0x363605C0bdE9F1F5053aDA30618d95dbFc109Bf5","0xcc400c09ecBAC3e0033e4587BdFAABB26223e37d","0x1d933Fd71FF07E69f066d50B39a7C34EB3b69F05","0x837219D7a9C666F5542c4559Bf17D7B804E5c5fe"]
      values.$threshold:
+        2
      values.multisigThreshold:
+        "2 of 4 (50%)"
    }
```

```diff
    contract HubPool Multisig (0xB524735356985D2f267FA010D681f061DfF03715) {
    +++ description: None
      values.$multisigThreshold:
-        "3 of 5 (60%)"
      values.getOwners:
-        ["0x1d933Fd71FF07E69f066d50B39a7C34EB3b69F05","0x837219D7a9C666F5542c4559Bf17D7B804E5c5fe","0x996267d7d1B7f5046543feDe2c2Db473Ed4f65e9","0xcc400c09ecBAC3e0033e4587BdFAABB26223e37d","0x868CF19464e17F76D6419ACC802B122c22D2FD34"]
      values.getThreshold:
-        3
      values.$members:
+        ["0x1d933Fd71FF07E69f066d50B39a7C34EB3b69F05","0x837219D7a9C666F5542c4559Bf17D7B804E5c5fe","0x996267d7d1B7f5046543feDe2c2Db473Ed4f65e9","0xcc400c09ecBAC3e0033e4587BdFAABB26223e37d","0x868CF19464e17F76D6419ACC802B122c22D2FD34"]
      values.$threshold:
+        3
      values.multisigThreshold:
+        "3 of 5 (60%)"
    }
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      assignedPermissions.admin:
-        ["0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5"]
      assignedPermissions.upgrade:
+        ["0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5"]
    }
```

Generated with discovered.json: 0x694b66df3231b8a4fe6cb923963e8254b05ba3e1

# Diff at Thu, 08 Aug 2024 07:11:14 GMT:

- author: Radina Talanova (<nt.radina@gmail.com>)
- comparing to: main@5a17db968badca34a66703637dabf76a313bb43e block: 20389580
- current block number: 20482283

## Description

A new Adapter and L2 crosschain target for Redstone are added.

## Watched changes

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.690:
+        "0x188F8C95B7cfB7993B53a4F643efa687916f73fA"
      values.CrossChainContracts.690:
+        "0x28077B47Cd03326De7838926A63699849DD4fa87"
    }
```

```diff
+   Status: CREATED
    contract Redstone_Adapter (0x188F8C95B7cfB7993B53a4F643efa687916f73fA)
    +++ description: None
```

## Source code changes

```diff
.../across-v3/ethereum/.flat/Redstone_Adapter.sol  | 590 +++++++++++++++++++++
 1 file changed, 590 insertions(+)
```

Generated with discovered.json: 0xdbd5447e307a5f0e39981d7b5ea954532dc92555

# Diff at Fri, 26 Jul 2024 08:38:43 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@f98f9bf0ba32e20ec33942af664ae6ed27e8172d block: 20289714
- current block number: 20389580

## Description

A new Adapter and L2 crosschain target for Scroll is registered.

## Watched changes

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.534352:
+        "0xb6129Ab69aEA75e6884c2D6ecf25293C343C519F"
      values.CrossChainContracts.534352:
+        "0x3baD7AD0728f9917d1Bf08af5782dCbD516cDd96"
    }
```

```diff
+   Status: CREATED
    contract Scroll_Adapter (0xb6129Ab69aEA75e6884c2D6ecf25293C343C519F)
    +++ description: None
```

## Source code changes

```diff
.../across-v3/ethereum/.flat/Scroll_Adapter.sol    | 531 +++++++++++++++++++++
 1 file changed, 531 insertions(+)
```

Generated with discovered.json: 0x5bed7c1b5746cf1f6518eef6a73859844d4d86c8

# Diff at Fri, 12 Jul 2024 10:06:36 GMT:

- author: sekuba (<sekuba@users.noreply.github.com>)
- comparing to: main@48ec906f1df3ec8351c0e2324170592091f7c1db block: 20232297
- current block number: 20289714

## Description

An adapter for Blast L2 is added.

## Watched changes

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.81457:
+        "0xF2bEf5E905AAE0295003ab14872F811E914EdD81"
      values.CrossChainContracts.81457:
+        "0x2D509190Ed0172ba588407D4c2df918F955Cc6E1"
    }
```

```diff
+   Status: CREATED
    contract Blast_Adapter (0xF2bEf5E905AAE0295003ab14872F811E914EdD81)
    +++ description: None
```

## Source code changes

```diff
.../across-v3/ethereum/.flat/Blast_Adapter.sol     | 601 +++++++++++++++++++++
 1 file changed, 601 insertions(+)
```

Generated with discovered.json: 0xe1c37ec100450be1198b8b4a281461e96e22f4fe

# Diff at Thu, 04 Jul 2024 09:37:01 GMT:

- author: sekuba (<29250140+sekuba@users.noreply.github.com>)
- comparing to: main@bfc05c606d82c4a38bb3b8c60569f0c976d7ba3a block: 20204613
- current block number: 20232297

## Description

A new adapter for Lisk is registered. Other changes are config related.

## Watched changes

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.Adapters.1135:
+        "0x8229E812f20537caA1e8Fb41749b4887B8a75C3B"
      values.CrossChainContracts.1135:
+        "0x9552a0a6624A23B848060AE5901659CDDa1f83f8"
    }
```

```diff
+   Status: CREATED
    contract Lisk_Adapter (0x8229E812f20537caA1e8Fb41749b4887B8a75C3B)
    +++ description: None
```

## Source code changes

```diff
.../across-v3/ethereum/.flat/Lisk_Adapter.sol      | 590 +++++++++++++++++++++
 1 file changed, 590 insertions(+)
```

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 20204613 (main branch discovery), not current.

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.CrossChainContracts.1:
-        {"l2ChainId":1,"adapter":"0x527E872a5c3f0C7c24Fe33F2593cFB890a285084","spokePool":"0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5"}
+        "0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5"
      values.CrossChainContracts.10:
-        {"l2ChainId":10,"adapter":"0xE1e74B3D6A8E2A479B62958D4E4E6eEaea5B612b","spokePool":"0x6f26Bf09B1C792e3228e5467807a900A503c0281"}
+        "0x6f26Bf09B1C792e3228e5467807a900A503c0281"
      values.CrossChainContracts.137:
-        {"l2ChainId":137,"adapter":"0xb4AeF0178f5725392A26eE18684C2aB62adc912e","spokePool":"0x9295ee1d8C5b022Be115A2AD3c30C72E34e7F096"}
+        "0x9295ee1d8C5b022Be115A2AD3c30C72E34e7F096"
      values.CrossChainContracts.288:
-        {"l2ChainId":288,"adapter":"0x33B0Ec794c15D6Cc705818E70d4CaCe7bCfB5Af3","spokePool":"0xBbc6009fEfFc27ce705322832Cb2068F8C1e0A58"}
+        "0xBbc6009fEfFc27ce705322832Cb2068F8C1e0A58"
      values.CrossChainContracts.324:
-        {"l2ChainId":324,"adapter":"0xE233009838CB898b50e0012a6E783FC9FeE447FB","spokePool":"0xE0B015E54d54fc84a6cB9B666099c46adE9335FF"}
+        "0xE0B015E54d54fc84a6cB9B666099c46adE9335FF"
      values.CrossChainContracts.8453:
-        {"l2ChainId":8453,"adapter":"0xE1421233BF7158A19f89F17c9735F9cbd3D9529c","spokePool":"0x09aea4b2242abC8bb4BB78D537A67a245A7bEC64"}
+        "0x09aea4b2242abC8bb4BB78D537A67a245A7bEC64"
      values.CrossChainContracts.34443:
-        {"l2ChainId":34443,"adapter":"0xf1B59868697f3925b72889ede818B9E7ba0316d0","spokePool":"0x3baD7AD0728f9917d1Bf08af5782dCbD516cDd96"}
+        "0x3baD7AD0728f9917d1Bf08af5782dCbD516cDd96"
      values.CrossChainContracts.42161:
-        {"l2ChainId":42161,"adapter":"0x5473CBD30bEd1Bf97C0c9d7c59d268CD620dA426","spokePool":"0xe35e9842fceaCA96570B734083f4a58e8F7C5f2A"}
+        "0xe35e9842fceaCA96570B734083f4a58e8F7C5f2A"
      values.CrossChainContracts.59144:
-        {"l2ChainId":59144,"adapter":"0x7Ea0D1882D610095A45E512B0113f79cA98a8EfE","spokePool":"0x7E63A5f1a8F0B4d0934B2f2327DAED3F6bb2ee75"}
+        "0x7E63A5f1a8F0B4d0934B2f2327DAED3F6bb2ee75"
      values.Adapters:
+        {"1":"0x527E872a5c3f0C7c24Fe33F2593cFB890a285084","10":"0xE1e74B3D6A8E2A479B62958D4E4E6eEaea5B612b","137":"0xb4AeF0178f5725392A26eE18684C2aB62adc912e","288":"0x33B0Ec794c15D6Cc705818E70d4CaCe7bCfB5Af3","324":"0xE233009838CB898b50e0012a6E783FC9FeE447FB","8453":"0xE1421233BF7158A19f89F17c9735F9cbd3D9529c","34443":"0xf1B59868697f3925b72889ede818B9E7ba0316d0","42161":"0x5473CBD30bEd1Bf97C0c9d7c59d268CD620dA426","59144":"0x7Ea0D1882D610095A45E512B0113f79cA98a8EfE"}
    }
```

Generated with discovered.json: 0x44dcb247700d419ff4f0fe12d00a6c356c1963ba

# Diff at Sun, 30 Jun 2024 12:51:10 GMT:

- author: Adrian Adamiak (<adrian@adamiak.net>)
- comparing to: main@60708cb34918009c7ee36a463625bddd2353d3c5 block: 19976242
- current block number: 20204613

## Description

Added ZkSync_Adapter.getL1CallValue to "ignoreMethods" because it is dependent
on tx.gasprice and returns different results event for the same block number
(e.g. when call is batched).

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19976242 (main branch discovery), not current.

```diff
    contract ZkSync_Adapter (0xE233009838CB898b50e0012a6E783FC9FeE447FB) {
    +++ description: None
      values.getL1CallValue:
-        500000000000000
    }
```

Generated with discovered.json: 0x4d7efdd31fe5b56bea03552b2c01f60249641603

# Diff at Wed, 29 May 2024 14:54:44 GMT:

- author: sekuba (<sekuba@users.noreply.github.com>)
- comparing to: main@d0877009edde2713b2b4f20a593b40156f5de045 block: 19926192
- current block number: 19976242

## Description

Config related: Owner is upgrade admin.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19926192 (main branch discovery), not current.

```diff
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5) {
    +++ description: None
      upgradeability.admin:
-        "0x0000000000000000000000000000000000000000"
+        "0xc186fA914353c44b2E33eBE05f21846F1048bEda"
    }
```

Generated with discovered.json: 0x00e7d86c9c32ebac36ad2111ea5369e41a1d7770

# Diff at Wed, 22 May 2024 15:04:33 GMT:

- author: vincfurc (<10850139+vincfurc@users.noreply.github.com>)
- comparing to: main@50042c8a4f2960931acbddbdf0949924bc003bcb block: 19891034
- current block number: 19926192

## Description

Added Mode adapter.
Changes to Polygon, Arbitrum, Optimism, Base adapters. 
    -  Added check for maximum burn amount for token per message on CCTP adapter. If the token amount to send exceeds the burn limit per message, then it will split the message into smaller parts.
New adapters implementation addresses broke config ignoreRelatives mapping, fixed now.


## Watched changes

```diff
-   Status: DELETED
    contract ProxyAdmin (0x0475cBCAebd9CE8AfA5025828d5b98DFb67E059E)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MessageTransmitter (0x0a992d191DEeC32aFe36203Ad87D7d289a738F81)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1DAITokenBridge (0x10E6593CDda8c58a1d0f14C5164B376352a55f2F)
    +++ description: None
```

```diff
-   Status: DELETED
    contract SequencerInbox (0x1c479675ad559DC151F6Ec7ed3FbF8ceE79582B6)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1CrossDomainMessenger (0x25ace71c97B33Cc4729CF772ae268934F7ab5fA1)
    +++ description: None
```

```diff
-   Status: DELETED
    contract StateSender (0x28e4F3a7f651294B9564800b2D01f35189A5bFbE)
    +++ description: None
```

```diff
-   Status: DELETED
    contract WithdrawManager (0x2A88696e0fFA76bAA1338F2C74497cC013495922)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1StandardBridge (0x3154Cf16ccdb4C6d922629664174b904d80F2C35)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Registry (0x33a02E6cC863D393d6Bf231B697b82F6e499cA71)
    +++ description: None
```

```diff
-   Status: DELETED
    contract SynthetixBridgeToOptimism (0x39Ea01a0298C315d149a490E34B59Dbf2EC7e48F)
    +++ description: None
```

```diff
-   Status: DELETED
    contract UpgradeExecutor (0x3ffFbAdAF827559da092217e474760E2b2c3CeDd)
    +++ description: None
```

```diff
-   Status: DELETED
    contract DepositManager (0x401F6c983eA34274ec46f84D70b31C151321188b)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ERC20Predicate (0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1Escrow (0x467194771dAe2967Aef3ECbEDD3Bf9a310C76C65)
    +++ description: None
```

```diff
-   Status: DELETED
    contract OptimismPortal (0x49048044D57e1C92A77f79988d21Fa8fAF74E97e)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Inbox (0x4Dbd4fc535Ac27206064B68FfCf827b0A60BAB3f)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ReadProxy (0x4E3b31eB0E5CB73641EE1E65E7dCEFe520bA3ef2)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ProxyAdmin (0x543bA4AADBAb8f9025686Bd03993043599c6fB04)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ProxyAdmin (0x554723262467F125Ac9e1cDFa9Ce15cc53822dbD)
    +++ description: None
```

```diff
-   Status: DELETED
    contract GnosisSafe (0x5a0Aae59D09fccBdDb6C6CcEB07B7279367C3d2A)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Dai (0x6B175474E89094C44Da98b954EedeAC495271d0F)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Governance (0x6e7a5820baD6cebA8Ef5ea69c0C92EbbDAc9CE48)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1GatewayRouter (0x72Ce9c846789fdB6fC1f34aC4AD25Dd9ef7031ef)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MaticToken (0x7D1AfA7B718fb893dB30A3aBc0Cfc608AaCfeBB0)
    +++ description: None
```

```diff
-   Status: DELETED
    contract AddressResolver (0x823bE81bbF96BEc0e25CA13170F5AaCb5B79ba83)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Arbitrum_Bridge (0x8315177aB297bA92A06054cE80a67Ed4DBd7ed3a)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1CrossDomainMessenger (0x866E82a600A1414e583f7F13623F1aC5d58b0Afa)
    +++ description: None
```

```diff
-   Status: DELETED
    contract RootChain (0x86E4Dc95c7FBdBf52e33D563BbDB00823894C287)
    +++ description: None
```

```diff
-   Status: DELETED
    contract AddressManager (0x8EfB6B5c4767B09Dc9AA6Af4eAA89F749522BaE2)
    +++ description: None
```

```diff
-   Status: DELETED
    contract SuperchainConfig (0x95703e0982140D16f8ebA6d158FccEde42f04a4C)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1StandardBridge (0x99C9fc46f92E8a1c0deC1b1747d010903E884bE1)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ProxyAdmin (0x9aD46fac0Cf7f790E5be05A0F15223935A0c0aDa)
    +++ description: None
```

```diff
-   Status: DELETED
    contract FiatTokenV2_2 (0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48)
    +++ description: None
```

```diff
-   Status: DELETED
    contract RootChainManager (0xA0c68C638235ee32657e8f720a23ceC1bFc77C77)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1ERC20Gateway (0xa3A7B6F88361F48403514059F1F16C8E78d60EeC)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MaticWETH (0xa45b966996374E9e65ab991C6FE4Bfce3a56DDe8)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MerklePatriciaProof (0xA6FA4fB5f76172d178d61B04b0ecd319C5d1C0aa)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Polygon_Adapter (0xB130E3056D5C692300d66c12C10ffA2073d9424D)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Optimism_Adapter (0xb3a4e39F0CD9aBAc5d866f023C18e73224667Fee)
    +++ description: None
```

```diff
-   Status: DELETED
    contract TokenMessenger (0xBd3fa81B58Ba92a82136038B25aDec7066af3155)
    +++ description: None
```

```diff
-   Status: DELETED
    contract OptimismPortal (0xbEb5Fc579115071764c7423A4f12eDde41f106Ed)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ProxyERC20 (0xC011a73ee8576Fb46F5E1c5751cA3B9Fe0af2a6F)
    +++ description: None
```

```diff
-   Status: DELETED
    contract WETH9 (0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2)
    +++ description: None
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.CrossChainContracts.10.adapter:
-        "0xb3a4e39F0CD9aBAc5d866f023C18e73224667Fee"
+        "0xE1e74B3D6A8E2A479B62958D4E4E6eEaea5B612b"
      values.CrossChainContracts.137.adapter:
-        "0xB130E3056D5C692300d66c12C10ffA2073d9424D"
+        "0xb4AeF0178f5725392A26eE18684C2aB62adc912e"
      values.CrossChainContracts.8453.adapter:
-        "0xD9948AE3405FE03A52A18F119EF72221DCdCc4df"
+        "0xE1421233BF7158A19f89F17c9735F9cbd3D9529c"
      values.CrossChainContracts.42161.adapter:
-        "0xd881A21F17B83AefFd11cc2e7363740449eb8069"
+        "0x5473CBD30bEd1Bf97C0c9d7c59d268CD620dA426"
      values.CrossChainContracts.34443:
+        {"l2ChainId":34443,"adapter":"0xf1B59868697f3925b72889ede818B9E7ba0316d0","spokePool":"0x3baD7AD0728f9917d1Bf08af5782dCbD516cDd96"}
    }
```

```diff
-   Status: DELETED
    contract TokenMinter (0xc4922d64a24675E16e1586e3e3Aa56C06fABe907)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Timelock (0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Synthetix (0xd711709eFc452152B7ad11DbD01ed4B69c9421B3)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Arbitrum_Adapter (0xd881A21F17B83AefFd11cc2e7363740449eb8069)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Base_Adapter (0xD9948AE3405FE03A52A18F119EF72221DCdCc4df)
    +++ description: None
```

```diff
-   Status: DELETED
    contract  (0xD9c7C4ED4B66858301D0cb28Cc88bf655Fe34861)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Lib_AddressManager (0xdE1FCfB0851916CA5101820A69b13a4E276bd81F)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MasterMinter (0xE982615d461DD5cD06575BbeA87624fda4e3de17)
    +++ description: None
```

```diff
-   Status: DELETED
    contract GnosisSafe (0xEb3107117FEAd7de89Cd14D463D340A2E6917769)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ValidatorShare (0xf98864DA30a5bd657B13e70A57f5718aBf7BAB31)
    +++ description: None
```

```diff
-   Status: DELETED
    contract FxRoot (0xfe5e5D361b2ad62c541bAb87C45a0B9B018389a2)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Arbitrum_Adapter (0x5473CBD30bEd1Bf97C0c9d7c59d268CD620dA426)
    +++ description: None
```

```diff
+   Status: CREATED
    contract EmergencyProposalExecutor (0x8180D59b7175d4064bDFA8138A58e9baBFFdA44a)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Polygon_Adapter (0xb4AeF0178f5725392A26eE18684C2aB62adc912e)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Base_Adapter (0xE1421233BF7158A19f89F17c9735F9cbd3D9529c)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Optimism_Adapter (0xE1e74B3D6A8E2A479B62958D4E4E6eEaea5B612b)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Mode_Adapter (0xf1B59868697f3925b72889ede818B9E7ba0316d0)
    +++ description: None
```

## Source code changes

```diff
.../.flat@19891034/AddressManager.sol => /dev/null |  128 -
 .../AddressResolver.sol => /dev/null               |  102 -
 .../{.flat@19891034 => .flat}/Arbitrum_Adapter.sol |   13 +-
 .../Arbitrum_Bridge/Bridge.sol => /dev/null        |  664 ----
 .../TransparentUpgradeableProxy.p.sol => /dev/null |  628 ----
 .../{.flat@19891034 => .flat}/Base_Adapter.sol     |   13 +-
 .../ethereum/.flat@19891034/Dai.sol => /dev/null   |  153 -
 .../DepositManager/DepositManager.sol => /dev/null |  473 ---
 .../DepositManagerProxy.p.sol => /dev/null         |  220 --
 .../ERC20Predicate/ERC20Predicate.sol => /dev/null | 1137 -------
 .../ERC20PredicateProxy.p.sol => /dev/null         |  151 -
 .../EmergencyProposalExecutor}/GnosisSafe.sol      |    0
 .../EmergencyProposalExecutor}/Proxy.p.sol         |    0
 .../FiatTokenProxy.p.sol => /dev/null              |  267 --
 .../FiatTokenV2_2/FiatTokenV2_2.sol => /dev/null   | 2356 --------------
 .../.flat@19891034/FxRoot.sol => /dev/null         |   24 -
 .../GnosisSafeProxy.p.sol => /dev/null             |   34 -
 .../GnosisSafe.sol => /dev/null                    |  952 ------
 .../Governance/Governance.sol => /dev/null         |   83 -
 .../Governance/GovernanceProxy.p.sol => /dev/null  |  156 -
 .../.flat@19891034/Inbox/Inbox.sol => /dev/null    | 1181 -------
 .../TransparentUpgradeableProxy.p.sol => /dev/null |  442 ---
 .../L1CrossDomainMessenger.sol => /dev/null        | 1513 ---------
 .../Lib_ResolvedDelegateProxy.p.sol => /dev/null   |   67 -
 .../L1CrossDomainMessenger.sol => /dev/null        | 1727 ----------
 .../ResolvedDelegateProxy.p.sol => /dev/null       |   54 -
 .../L1DAITokenBridge.sol => /dev/null              |  482 ---
 .../L1ERC20Gateway/L1ERC20Gateway.sol => /dev/null | 1381 --------
 .../TransparentUpgradeableProxy.p.sol => /dev/null |  442 ---
 .../.flat@19891034/L1Escrow.sol => /dev/null       |   39 -
 .../L1GatewayRouter.sol => /dev/null               |  991 ------
 .../TransparentUpgradeableProxy.p.sol => /dev/null |  442 ---
 .../L1ChugSplashProxy.p.sol => /dev/null           |  268 --
 .../L1StandardBridge.sol => /dev/null              | 1586 ---------
 .../L1ChugSplashProxy.p.sol => /dev/null           |  343 --
 .../L1StandardBridge.sol => /dev/null              | 1537 ---------
 .../Lib_AddressManager.sol => /dev/null            |  151 -
 .../.flat@19891034/MasterMinter.sol => /dev/null   |  371 ---
 .../.flat@19891034/MaticToken.sol => /dev/null     |  438 ---
 .../.flat@19891034/MaticWETH.sol => /dev/null      |  289 --
 .../MerklePatriciaProof.sol => /dev/null           |  413 ---
 .../MessageTransmitter.sol => /dev/null            | 3080 ------------------
 .../across-v3/ethereum/.flat/Mode_Adapter.sol      |  578 ++++
 .../OptimismPortal.sol => /dev/null                | 3425 --------------------
 .../Proxy.p.sol => /dev/null                       |  210 --
 .../OptimismPortal.sol => /dev/null                | 2881 ----------------
 .../Proxy.p.sol => /dev/null                       |  210 --
 .../{.flat@19891034 => .flat}/Optimism_Adapter.sol |   13 +-
 .../{.flat@19891034 => .flat}/Polygon_Adapter.sol  |   13 +-
 .../dev/null                                       |  297 --
 .../dev/null                                       |  297 --
 .../dev/null                                       |  139 -
 .../dev/null                                       |  131 -
 .../.flat@19891034/ProxyERC20.sol => /dev/null     |  305 --
 .../.flat@19891034/ReadProxy.sol => /dev/null      |   62 -
 .../.flat@19891034/Registry.sol => /dev/null       |  150 -
 .../RootChain/RootChain.sol => /dev/null           |  608 ----
 .../RootChain/RootChainProxy.p.sol => /dev/null    |  193 --
 .../RootChainManager.sol => /dev/null              | 2087 ------------
 .../RootChainManagerProxy.p.sol => /dev/null       |  151 -
 .../SequencerInbox/SequencerInbox.sol => /dev/null | 1086 -------
 .../TransparentUpgradeableProxy.p.sol => /dev/null |  628 ----
 .../.flat@19891034/StateSender.sol => /dev/null    |  178 -
 .../SuperchainConfig/Proxy.p.sol => /dev/null      |  199 --
 .../SuperchainConfig.sol => /dev/null              |  476 ---
 .../.flat@19891034/Synthetix.sol => /dev/null      | 1662 ----------
 .../SynthetixBridgeToOptimism.sol => /dev/null     | 1284 --------
 .../.flat@19891034/Timelock.sol => /dev/null       |  675 ----
 .../.flat@19891034/TokenMessenger.sol => /dev/null | 2591 ---------------
 .../.flat@19891034/TokenMinter.sol => /dev/null    | 1270 --------
 .../TransparentUpgradeableProxy.p.sol => /dev/null |  630 ----
 .../UpgradeExecutor.sol => /dev/null               |  995 ------
 .../.flat@19891034/ValidatorShare.sol => /dev/null |  802 -----
 .../ethereum/.flat@19891034/WETH9.sol => /dev/null |   62 -
 .../WithdrawManager.sol => /dev/null               | 1267 --------
 .../WithdrawManagerProxy.p.sol => /dev/null        |  222 --
 76 files changed, 622 insertions(+), 49946 deletions(-)
```

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19891034 (main branch discovery), not current.

```diff
-   Status: DELETED
    contract EmergencyProposalExecutor (0x8180D59b7175d4064bDFA8138A58e9baBFFdA44a)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (0x0475cBCAebd9CE8AfA5025828d5b98DFb67E059E)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MessageTransmitter (0x0a992d191DEeC32aFe36203Ad87D7d289a738F81)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1DAITokenBridge (0x10E6593CDda8c58a1d0f14C5164B376352a55f2F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract SequencerInbox (0x1c479675ad559DC151F6Ec7ed3FbF8ceE79582B6)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1CrossDomainMessenger (0x25ace71c97B33Cc4729CF772ae268934F7ab5fA1)
    +++ description: None
```

```diff
+   Status: CREATED
    contract StateSender (0x28e4F3a7f651294B9564800b2D01f35189A5bFbE)
    +++ description: None
```

```diff
+   Status: CREATED
    contract WithdrawManager (0x2A88696e0fFA76bAA1338F2C74497cC013495922)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1StandardBridge (0x3154Cf16ccdb4C6d922629664174b904d80F2C35)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Registry (0x33a02E6cC863D393d6Bf231B697b82F6e499cA71)
    +++ description: None
```

```diff
+   Status: CREATED
    contract SynthetixBridgeToOptimism (0x39Ea01a0298C315d149a490E34B59Dbf2EC7e48F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract UpgradeExecutor (0x3ffFbAdAF827559da092217e474760E2b2c3CeDd)
    +++ description: None
```

```diff
+   Status: CREATED
    contract DepositManager (0x401F6c983eA34274ec46f84D70b31C151321188b)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ERC20Predicate (0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1Escrow (0x467194771dAe2967Aef3ECbEDD3Bf9a310C76C65)
    +++ description: None
```

```diff
+   Status: CREATED
    contract OptimismPortal (0x49048044D57e1C92A77f79988d21Fa8fAF74E97e)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Inbox (0x4Dbd4fc535Ac27206064B68FfCf827b0A60BAB3f)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ReadProxy (0x4E3b31eB0E5CB73641EE1E65E7dCEFe520bA3ef2)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (0x543bA4AADBAb8f9025686Bd03993043599c6fB04)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (0x554723262467F125Ac9e1cDFa9Ce15cc53822dbD)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GnosisSafe (0x5a0Aae59D09fccBdDb6C6CcEB07B7279367C3d2A)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Dai (0x6B175474E89094C44Da98b954EedeAC495271d0F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Governance (0x6e7a5820baD6cebA8Ef5ea69c0C92EbbDAc9CE48)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1GatewayRouter (0x72Ce9c846789fdB6fC1f34aC4AD25Dd9ef7031ef)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MaticToken (0x7D1AfA7B718fb893dB30A3aBc0Cfc608AaCfeBB0)
    +++ description: None
```

```diff
+   Status: CREATED
    contract AddressResolver (0x823bE81bbF96BEc0e25CA13170F5AaCb5B79ba83)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Arbitrum_Bridge (0x8315177aB297bA92A06054cE80a67Ed4DBd7ed3a)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1CrossDomainMessenger (0x866E82a600A1414e583f7F13623F1aC5d58b0Afa)
    +++ description: None
```

```diff
+   Status: CREATED
    contract RootChain (0x86E4Dc95c7FBdBf52e33D563BbDB00823894C287)
    +++ description: None
```

```diff
+   Status: CREATED
    contract AddressManager (0x8EfB6B5c4767B09Dc9AA6Af4eAA89F749522BaE2)
    +++ description: None
```

```diff
+   Status: CREATED
    contract SuperchainConfig (0x95703e0982140D16f8ebA6d158FccEde42f04a4C)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1StandardBridge (0x99C9fc46f92E8a1c0deC1b1747d010903E884bE1)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (0x9aD46fac0Cf7f790E5be05A0F15223935A0c0aDa)
    +++ description: None
```

```diff
+   Status: CREATED
    contract FiatTokenV2_2 (0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48)
    +++ description: None
```

```diff
+   Status: CREATED
    contract RootChainManager (0xA0c68C638235ee32657e8f720a23ceC1bFc77C77)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1ERC20Gateway (0xa3A7B6F88361F48403514059F1F16C8E78d60EeC)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MaticWETH (0xa45b966996374E9e65ab991C6FE4Bfce3a56DDe8)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MerklePatriciaProof (0xA6FA4fB5f76172d178d61B04b0ecd319C5d1C0aa)
    +++ description: None
```

```diff
+   Status: CREATED
    contract TokenMessenger (0xBd3fa81B58Ba92a82136038B25aDec7066af3155)
    +++ description: None
```

```diff
+   Status: CREATED
    contract OptimismPortal (0xbEb5Fc579115071764c7423A4f12eDde41f106Ed)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyERC20 (0xC011a73ee8576Fb46F5E1c5751cA3B9Fe0af2a6F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract WETH9 (0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2)
    +++ description: None
```

```diff
+   Status: CREATED
    contract TokenMinter (0xc4922d64a24675E16e1586e3e3Aa56C06fABe907)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Timelock (0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Synthetix (0xd711709eFc452152B7ad11DbD01ed4B69c9421B3)
    +++ description: None
```

```diff
+   Status: CREATED
    contract  (0xD9c7C4ED4B66858301D0cb28Cc88bf655Fe34861)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Lib_AddressManager (0xdE1FCfB0851916CA5101820A69b13a4E276bd81F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MasterMinter (0xE982615d461DD5cD06575BbeA87624fda4e3de17)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GnosisSafe (0xEb3107117FEAd7de89Cd14D463D340A2E6917769)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ValidatorShare (0xf98864DA30a5bd657B13e70A57f5718aBf7BAB31)
    +++ description: None
```

```diff
+   Status: CREATED
    contract FxRoot (0xfe5e5D361b2ad62c541bAb87C45a0B9B018389a2)
    +++ description: None
```

Generated with discovered.json: 0x55d0510f7032eff3f615bdae368015f76f42ff06

# Diff at Fri, 17 May 2024 16:59:08 GMT:

- author: vincfurc (<10850139+vincfurc@users.noreply.github.com>)
- comparing to: main@7634eb7892129fd76fa0bce18d68181ba69b99db block: 19718050
- current block number: 19891034

## Description

Ethereum_SpokePool.sol
- Added events FundsDeposited, RequestedSpeedUpDeposit, FilledRelay

HubPool changes: added CircleCCTPAdapter. 
- The Cross-Chain Transfer Protocol (CCTP) is now used to bridge USDC on Arbitrum, Base, Optimism, and Polygon. 
- Change of adapters interface format (e.g., messenger -> MESSENGER, l1Weth -> L1_WETH) that impacted ignoreRelatives discovery. Now restored to ignore relatives of updated methods. 
Impacted adapters contracts: Arbitrum_Adapter.sol, Base_Adapter.sol, Optimism_Adapter.sol, Polygon_Adapter.sol.

## Watched changes

```diff
-   Status: DELETED
    contract  (0x01F645DcD6C796F6BC6C982159B32fAaaebdC96A)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ProxyAdmin (0x0475cBCAebd9CE8AfA5025828d5b98DFb67E059E)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MultiCollateralSynth (0x10A5F7D9D65bCc2734763444D4940a31b109275f)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1DAITokenBridge (0x10E6593CDda8c58a1d0f14C5164B376352a55f2F)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ERC20PredicateBurnOnly (0x158d5fa3Ef8e4dDA8a5367deCF76b94E7efFCe95)
    +++ description: None
```

```diff
-   Status: DELETED
    contract SequencerInbox (0x1c479675ad559DC151F6Ec7ed3FbF8ceE79582B6)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1CrossDomainMessenger (0x25ace71c97B33Cc4729CF772ae268934F7ab5fA1)
    +++ description: None
```

```diff
-   Status: DELETED
    contract StateSender (0x28e4F3a7f651294B9564800b2D01f35189A5bFbE)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Arbitrum_Adapter (0x29528780E29abb8Af95a5e5a125b94766987543F)
    +++ description: None
```

```diff
-   Status: DELETED
    contract WithdrawManager (0x2A88696e0fFA76bAA1338F2C74497cC013495922)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Base_Adapter (0x2d8B1e2B0Dff62DF132d23BEa68a6D2c4D20046E)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1StandardBridge (0x3154Cf16ccdb4C6d922629664174b904d80F2C35)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Registry (0x33a02E6cC863D393d6Bf231B697b82F6e499cA71)
    +++ description: None
```

```diff
-   Status: DELETED
    contract SynthetixBridgeToOptimism (0x39Ea01a0298C315d149a490E34B59Dbf2EC7e48F)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Polygon_Adapter (0x3E94e8d4316a1eBfb2245E45E6F0B8724094CE1A)
    +++ description: None
```

```diff
-   Status: DELETED
    contract UpgradeExecutor (0x3ffFbAdAF827559da092217e474760E2b2c3CeDd)
    +++ description: None
```

```diff
-   Status: DELETED
    contract DepositManager (0x401F6c983eA34274ec46f84D70b31C151321188b)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ERC20Predicate (0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1Escrow (0x467194771dAe2967Aef3ECbEDD3Bf9a310C76C65)
    +++ description: None
```

```diff
-   Status: DELETED
    contract OptimismPortal (0x49048044D57e1C92A77f79988d21Fa8fAF74E97e)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Inbox (0x4Dbd4fc535Ac27206064B68FfCf827b0A60BAB3f)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ReadProxy (0x4E3b31eB0E5CB73641EE1E65E7dCEFe520bA3ef2)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ERC721PredicateBurnOnly (0x54150f44c785D412Ec262fe895Cc3B689c72F49B)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ProxyAdmin (0x543bA4AADBAb8f9025686Bd03993043599c6fB04)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ProxyAdmin (0x554723262467F125Ac9e1cDFa9Ce15cc53822dbD)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ProxyAdmin (0x5613AF0474EB9c528A34701A5b1662E3C8FA0678)
    +++ description: None
```

```diff
-   Status: DELETED
    contract GnosisSafe (0x5a0Aae59D09fccBdDb6C6CcEB07B7279367C3d2A)
    +++ description: None
```

```diff
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5) {
    +++ description: None
      upgradeability.implementation:
-        "0xa4D3535f33549749Fb97fA42903AC80F6fb54af6"
+        "0x08C21b200eD06D2e32cEC91a770C3FcA8aD5F877"
      implementations.0:
-        "0xa4D3535f33549749Fb97fA42903AC80F6fb54af6"
+        "0x08C21b200eD06D2e32cEC91a770C3FcA8aD5F877"
      values.fillDeadlineBuffer:
-        28800
+        21600
    }
```

```diff
-   Status: DELETED
    contract StakeManager (0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Dai (0x6B175474E89094C44Da98b954EedeAC495271d0F)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Governance (0x6e7a5820baD6cebA8Ef5ea69c0C92EbbDAc9CE48)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1GatewayRouter (0x72Ce9c846789fdB6fC1f34aC4AD25Dd9ef7031ef)
    +++ description: None
```

```diff
-   Status: DELETED
    contract GnosisSafe (0x7bB41C3008B3f03FE483B28b8DB90e19Cf07595c)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MaticToken (0x7D1AfA7B718fb893dB30A3aBc0Cfc608AaCfeBB0)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Arbitrum_Bridge (0x8315177aB297bA92A06054cE80a67Ed4DBd7ed3a)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1CrossDomainMessenger (0x866E82a600A1414e583f7F13623F1aC5d58b0Afa)
    +++ description: None
```

```diff
-   Status: DELETED
    contract RootChain (0x86E4Dc95c7FBdBf52e33D563BbDB00823894C287)
    +++ description: None
```

```diff
-   Status: DELETED
    contract AddressManager (0x8EfB6B5c4767B09Dc9AA6Af4eAA89F749522BaE2)
    +++ description: None
```

```diff
-   Status: DELETED
    contract SuperchainConfig (0x95703e0982140D16f8ebA6d158FccEde42f04a4C)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1StandardBridge (0x99C9fc46f92E8a1c0deC1b1747d010903E884bE1)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ProxyAdmin (0x9aD46fac0Cf7f790E5be05A0F15223935A0c0aDa)
    +++ description: None
```

```diff
-   Status: DELETED
    contract RootChainManager (0xA0c68C638235ee32657e8f720a23ceC1bFc77C77)
    +++ description: None
```

```diff
-   Status: DELETED
    contract L1ERC20Gateway (0xa3A7B6F88361F48403514059F1F16C8E78d60EeC)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MaticWETH (0xa45b966996374E9e65ab991C6FE4Bfce3a56DDe8)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MerklePatriciaProof (0xA6FA4fB5f76172d178d61B04b0ecd319C5d1C0aa)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MultiCollateralSynth (0xa8E31E3C38aDD6052A9407298FAEB8fD393A6cF9)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Optimism_Adapter (0xAd1b0a86c98703fd5F4E56fff04F6b2D9b9f246F)
    +++ description: None
```

```diff
-   Status: DELETED
    contract OptimismPortal (0xbEb5Fc579115071764c7423A4f12eDde41f106Ed)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ProxyERC20 (0xC011a73ee8576Fb46F5E1c5751cA3B9Fe0af2a6F)
    +++ description: None
```

```diff
-   Status: DELETED
    contract WETH9 (0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2)
    +++ description: None
```

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.CrossChainContracts.10.adapter:
-        "0xAd1b0a86c98703fd5F4E56fff04F6b2D9b9f246F"
+        "0xb3a4e39F0CD9aBAc5d866f023C18e73224667Fee"
      values.CrossChainContracts.137.adapter:
-        "0x3E94e8d4316a1eBfb2245E45E6F0B8724094CE1A"
+        "0xB130E3056D5C692300d66c12C10ffA2073d9424D"
      values.CrossChainContracts.8453.adapter:
-        "0x2d8B1e2B0Dff62DF132d23BEa68a6D2c4D20046E"
+        "0xD9948AE3405FE03A52A18F119EF72221DCdCc4df"
      values.CrossChainContracts.42161.adapter:
-        "0x29528780E29abb8Af95a5e5a125b94766987543F"
+        "0xd881A21F17B83AefFd11cc2e7363740449eb8069"
    }
```

```diff
-   Status: DELETED
    contract Timelock (0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Whitelist (0xD485e5c28AA4985b23f6DF13dA03caa766dcd459)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Synthetix (0xd711709eFc452152B7ad11DbD01ed4B69c9421B3)
    +++ description: None
```

```diff
-   Status: DELETED
    contract  (0xD9c7C4ED4B66858301D0cb28Cc88bf655Fe34861)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MultiCollateralSynth (0xdc883b9d9Ee16f74bE08826E68dF4C9D9d26e8bD)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Lib_AddressManager (0xdE1FCfB0851916CA5101820A69b13a4E276bd81F)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MultiCollateralSynth (0xE1cc2332852B2Ac0dA59A1f9D3051829f4eF3c1C)
    +++ description: None
```

```diff
-   Status: DELETED
    contract GnosisSafe (0xEb3107117FEAd7de89Cd14D463D340A2E6917769)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ValidatorShare (0xf98864DA30a5bd657B13e70A57f5718aBf7BAB31)
    +++ description: None
```

```diff
-   Status: DELETED
    contract GnosisSafe (0xFa7D2a996aC6350f4b56C043112Da0366a59b74c)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MultiCollateralSynth (0xfb020CA7f4e8C4a5bBBe060f59a249c6275d2b69)
    +++ description: None
```

```diff
-   Status: DELETED
    contract FxRoot (0xfe5e5D361b2ad62c541bAb87C45a0B9B018389a2)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Polygon_Adapter (0xB130E3056D5C692300d66c12C10ffA2073d9424D)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Optimism_Adapter (0xb3a4e39F0CD9aBAc5d866f023C18e73224667Fee)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Arbitrum_Adapter (0xd881A21F17B83AefFd11cc2e7363740449eb8069)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Base_Adapter (0xD9948AE3405FE03A52A18F119EF72221DCdCc4df)
    +++ description: None
```

## Source code changes

```diff
.../.flat@19718050/AddressManager.sol => /dev/null |  128 -
 .../{.flat@19718050 => .flat}/Arbitrum_Adapter.sol |  405 ++-
 .../Arbitrum_Bridge/Bridge.sol => /dev/null        |  664 ----
 .../TransparentUpgradeableProxy.p.sol => /dev/null |  628 ----
 .../{.flat@19718050 => .flat}/Base_Adapter.sol     |  139 +-
 .../ethereum/.flat@19718050/Dai.sol => /dev/null   |  153 -
 .../DepositManager/DepositManager.sol => /dev/null |  473 ---
 .../DepositManagerProxy.p.sol => /dev/null         |  220 --
 .../ERC20Predicate/ERC20Predicate.sol => /dev/null | 1137 -------
 .../ERC20PredicateProxy.p.sol => /dev/null         |  151 -
 .../ERC20PredicateBurnOnly.sol => /dev/null        | 1115 -------
 .../ERC721PredicateBurnOnly.sol => /dev/null       | 1120 -------
 .../Ethereum_SpokePool/Ethereum_SpokePool.sol      |   86 +-
 .../.flat@19718050/FxRoot.sol => /dev/null         |   24 -
 .../GnosisSafe.sol => /dev/null                    |  952 ------
 .../GnosisSafeProxy.p.sol => /dev/null             |   34 -
 .../GnosisSafe.sol => /dev/null                    |  952 ------
 .../GnosisSafeProxy.p.sol => /dev/null             |   34 -
 .../GnosisSafe.sol => /dev/null                    |  952 ------
 .../Proxy.p.sol => /dev/null                       |   38 -
 .../GnosisSafe.sol => /dev/null                    |  958 ------
 .../Proxy.p.sol => /dev/null                       |   38 -
 .../Governance/Governance.sol => /dev/null         |   83 -
 .../Governance/GovernanceProxy.p.sol => /dev/null  |  156 -
 .../.flat@19718050/Inbox/Inbox.sol => /dev/null    | 1181 -------
 .../TransparentUpgradeableProxy.p.sol => /dev/null |  442 ---
 .../L1CrossDomainMessenger.sol => /dev/null        | 1513 ---------
 .../Lib_ResolvedDelegateProxy.p.sol => /dev/null   |   67 -
 .../L1CrossDomainMessenger.sol => /dev/null        | 1727 ----------
 .../ResolvedDelegateProxy.p.sol => /dev/null       |   54 -
 .../L1DAITokenBridge.sol => /dev/null              |  482 ---
 .../L1ERC20Gateway/L1ERC20Gateway.sol => /dev/null | 1381 --------
 .../TransparentUpgradeableProxy.p.sol => /dev/null |  442 ---
 .../.flat@19718050/L1Escrow.sol => /dev/null       |   39 -
 .../L1GatewayRouter.sol => /dev/null               |  991 ------
 .../TransparentUpgradeableProxy.p.sol => /dev/null |  442 ---
 .../L1ChugSplashProxy.p.sol => /dev/null           |  268 --
 .../L1StandardBridge.sol => /dev/null              | 1586 ---------
 .../L1ChugSplashProxy.p.sol => /dev/null           |  343 --
 .../L1StandardBridge.sol => /dev/null              | 1537 ---------
 .../Lib_AddressManager.sol => /dev/null            |  151 -
 .../.flat@19718050/MaticToken.sol => /dev/null     |  438 ---
 .../.flat@19718050/MaticWETH.sol => /dev/null      |  289 --
 .../MerklePatriciaProof.sol => /dev/null           |  413 ---
 .../dev/null                                       | 1057 ------
 .../dev/null                                       | 1057 ------
 .../dev/null                                       | 1057 ------
 .../dev/null                                       | 1057 ------
 .../dev/null                                       | 1057 ------
 .../OptimismPortal.sol => /dev/null                | 3425 --------------------
 .../Proxy.p.sol => /dev/null                       |  210 --
 .../OptimismPortal.sol => /dev/null                | 2881 ----------------
 .../Proxy.p.sol => /dev/null                       |  210 --
 .../{.flat@19718050 => .flat}/Optimism_Adapter.sol |  156 +-
 .../{.flat@19718050 => .flat}/Polygon_Adapter.sol  |  342 +-
 .../dev/null                                       |  297 --
 .../dev/null                                       |  297 --
 .../dev/null                                       |  139 -
 .../dev/null                                       |  146 -
 .../dev/null                                       |  131 -
 .../.flat@19718050/ProxyERC20.sol => /dev/null     |  305 --
 .../.flat@19718050/ReadProxy.sol => /dev/null      |   62 -
 .../.flat@19718050/Registry.sol => /dev/null       |  150 -
 .../RootChain/RootChain.sol => /dev/null           |  608 ----
 .../RootChain/RootChainProxy.p.sol => /dev/null    |  193 --
 .../RootChainManager.sol => /dev/null              | 2087 ------------
 .../RootChainManagerProxy.p.sol => /dev/null       |  151 -
 .../SequencerInbox/SequencerInbox.sol => /dev/null | 1086 -------
 .../TransparentUpgradeableProxy.p.sol => /dev/null |  628 ----
 .../StakeManager/StakeManager.sol => /dev/null     | 2112 ------------
 .../StakeManagerProxy.p.sol => /dev/null           |  145 -
 .../.flat@19718050/StateSender.sol => /dev/null    |  178 -
 .../SuperchainConfig/Proxy.p.sol => /dev/null      |  199 --
 .../SuperchainConfig.sol => /dev/null              |  476 ---
 .../.flat@19718050/Synthetix.sol => /dev/null      | 1662 ----------
 .../SynthetixBridgeToOptimism.sol => /dev/null     | 1284 --------
 .../.flat@19718050/Timelock.sol => /dev/null       |  675 ----
 .../TransparentUpgradeableProxy.p.sol => /dev/null |  630 ----
 .../UpgradeExecutor.sol => /dev/null               |  995 ------
 .../.flat@19718050/ValidatorShare.sol => /dev/null |  802 -----
 .../ethereum/.flat@19718050/WETH9.sol => /dev/null |   62 -
 .../.flat@19718050/Whitelist.sol => /dev/null      |   39 -
 .../WithdrawManager.sol => /dev/null               | 1267 --------
 .../WithdrawManagerProxy.p.sol => /dev/null        |  222 --
 84 files changed, 828 insertions(+), 53135 deletions(-)
```

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19718050 (main branch discovery), not current.

```diff
+   Status: CREATED
    contract  (0x01F645DcD6C796F6BC6C982159B32fAaaebdC96A)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (0x0475cBCAebd9CE8AfA5025828d5b98DFb67E059E)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MultiCollateralSynth (0x10A5F7D9D65bCc2734763444D4940a31b109275f)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1DAITokenBridge (0x10E6593CDda8c58a1d0f14C5164B376352a55f2F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ERC20PredicateBurnOnly (0x158d5fa3Ef8e4dDA8a5367deCF76b94E7efFCe95)
    +++ description: None
```

```diff
+   Status: CREATED
    contract SequencerInbox (0x1c479675ad559DC151F6Ec7ed3FbF8ceE79582B6)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1CrossDomainMessenger (0x25ace71c97B33Cc4729CF772ae268934F7ab5fA1)
    +++ description: None
```

```diff
+   Status: CREATED
    contract StateSender (0x28e4F3a7f651294B9564800b2D01f35189A5bFbE)
    +++ description: None
```

```diff
+   Status: CREATED
    contract WithdrawManager (0x2A88696e0fFA76bAA1338F2C74497cC013495922)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1StandardBridge (0x3154Cf16ccdb4C6d922629664174b904d80F2C35)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Registry (0x33a02E6cC863D393d6Bf231B697b82F6e499cA71)
    +++ description: None
```

```diff
+   Status: CREATED
    contract SynthetixBridgeToOptimism (0x39Ea01a0298C315d149a490E34B59Dbf2EC7e48F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract UpgradeExecutor (0x3ffFbAdAF827559da092217e474760E2b2c3CeDd)
    +++ description: None
```

```diff
+   Status: CREATED
    contract DepositManager (0x401F6c983eA34274ec46f84D70b31C151321188b)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ERC20Predicate (0x40ec5B33f54e0E8A33A975908C5BA1c14e5BbbDf)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1Escrow (0x467194771dAe2967Aef3ECbEDD3Bf9a310C76C65)
    +++ description: None
```

```diff
+   Status: CREATED
    contract OptimismPortal (0x49048044D57e1C92A77f79988d21Fa8fAF74E97e)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Inbox (0x4Dbd4fc535Ac27206064B68FfCf827b0A60BAB3f)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ReadProxy (0x4E3b31eB0E5CB73641EE1E65E7dCEFe520bA3ef2)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ERC721PredicateBurnOnly (0x54150f44c785D412Ec262fe895Cc3B689c72F49B)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (0x543bA4AADBAb8f9025686Bd03993043599c6fB04)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (0x554723262467F125Ac9e1cDFa9Ce15cc53822dbD)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (0x5613AF0474EB9c528A34701A5b1662E3C8FA0678)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GnosisSafe (0x5a0Aae59D09fccBdDb6C6CcEB07B7279367C3d2A)
    +++ description: None
```

```diff
+   Status: CREATED
    contract StakeManager (0x5e3Ef299fDDf15eAa0432E6e66473ace8c13D908)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Dai (0x6B175474E89094C44Da98b954EedeAC495271d0F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Governance (0x6e7a5820baD6cebA8Ef5ea69c0C92EbbDAc9CE48)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1GatewayRouter (0x72Ce9c846789fdB6fC1f34aC4AD25Dd9ef7031ef)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GnosisSafe (0x7bB41C3008B3f03FE483B28b8DB90e19Cf07595c)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MaticToken (0x7D1AfA7B718fb893dB30A3aBc0Cfc608AaCfeBB0)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Arbitrum_Bridge (0x8315177aB297bA92A06054cE80a67Ed4DBd7ed3a)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1CrossDomainMessenger (0x866E82a600A1414e583f7F13623F1aC5d58b0Afa)
    +++ description: None
```

```diff
+   Status: CREATED
    contract RootChain (0x86E4Dc95c7FBdBf52e33D563BbDB00823894C287)
    +++ description: None
```

```diff
+   Status: CREATED
    contract AddressManager (0x8EfB6B5c4767B09Dc9AA6Af4eAA89F749522BaE2)
    +++ description: None
```

```diff
+   Status: CREATED
    contract SuperchainConfig (0x95703e0982140D16f8ebA6d158FccEde42f04a4C)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1StandardBridge (0x99C9fc46f92E8a1c0deC1b1747d010903E884bE1)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (0x9aD46fac0Cf7f790E5be05A0F15223935A0c0aDa)
    +++ description: None
```

```diff
+   Status: CREATED
    contract RootChainManager (0xA0c68C638235ee32657e8f720a23ceC1bFc77C77)
    +++ description: None
```

```diff
+   Status: CREATED
    contract L1ERC20Gateway (0xa3A7B6F88361F48403514059F1F16C8E78d60EeC)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MaticWETH (0xa45b966996374E9e65ab991C6FE4Bfce3a56DDe8)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MerklePatriciaProof (0xA6FA4fB5f76172d178d61B04b0ecd319C5d1C0aa)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MultiCollateralSynth (0xa8E31E3C38aDD6052A9407298FAEB8fD393A6cF9)
    +++ description: None
```

```diff
+   Status: CREATED
    contract OptimismPortal (0xbEb5Fc579115071764c7423A4f12eDde41f106Ed)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyERC20 (0xC011a73ee8576Fb46F5E1c5751cA3B9Fe0af2a6F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract WETH9 (0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Timelock (0xCaf0aa768A3AE1297DF20072419Db8Bb8b5C8cEf)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Whitelist (0xD485e5c28AA4985b23f6DF13dA03caa766dcd459)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Synthetix (0xd711709eFc452152B7ad11DbD01ed4B69c9421B3)
    +++ description: None
```

```diff
+   Status: CREATED
    contract  (0xD9c7C4ED4B66858301D0cb28Cc88bf655Fe34861)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MultiCollateralSynth (0xdc883b9d9Ee16f74bE08826E68dF4C9D9d26e8bD)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Lib_AddressManager (0xdE1FCfB0851916CA5101820A69b13a4E276bd81F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MultiCollateralSynth (0xE1cc2332852B2Ac0dA59A1f9D3051829f4eF3c1C)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GnosisSafe (0xEb3107117FEAd7de89Cd14D463D340A2E6917769)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ValidatorShare (0xf98864DA30a5bd657B13e70A57f5718aBf7BAB31)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GnosisSafe (0xFa7D2a996aC6350f4b56C043112Da0366a59b74c)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MultiCollateralSynth (0xfb020CA7f4e8C4a5bBBe060f59a249c6275d2b69)
    +++ description: None
```

```diff
+   Status: CREATED
    contract FxRoot (0xfe5e5D361b2ad62c541bAb87C45a0B9B018389a2)
    +++ description: None
```

Generated with discovered.json: 0xb4bd133d76516e18e5f01eab8e4bd307d27863c2

# Diff at Tue, 23 Apr 2024 12:22:02 GMT:

- author: sekuba (<sekuba@users.noreply.githum.com>)
- comparing to: main@0c5cebacabe91d4bb808f51a732583d8107ec7bc block: 19645947
- current block number: 19718050

## Description

Liveness value in the HubPool (token escrow) is decreased from 1,5 to 1h. This is the time before a subitted root bundle is finalized and cannot be disputed anymore (And when relayers are reimbursed with tokens).

## Watched changes

```diff
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda) {
    +++ description: None
      values.liveness:
-        5400
+        3600
    }
```

Generated with discovered.json: 0x5c90684b94ec67ec0205143a888b5085c83eecf9

# Diff at Sat, 13 Apr 2024 10:06:54 GMT:

- author: sekuba (<sekuba@users.noreply.github.com>)
- comparing to: main@ce9ed778ed3251d8c0182e8225fd576d18383215 block: 19631863
- current block number: 19645947

## Description

Tidy up config.jsonc:

- no onchain changes
- scope of discovery config stays the same (+Linea adapter added)

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19631863 (main branch discovery), not current.

```diff
-   Status: DELETED
    contract TokenBridge (0x051F1D88f0aF5763fB888eC4378b4D8B29ea3319)
    +++ description: None
```

```diff
-   Status: DELETED
    contract BridgedToken (0x36f274C1C197F277EA3C57859729398FCc8a3763)
    +++ description: None
```

```diff
-   Status: DELETED
    contract ProxyAdmin (0x5B0bb17755FBa06028530682E2FD5bc373931768)
    +++ description: None
```

```diff
-   Status: DELETED
    contract GnosisSafe (0x892bb7EeD71efB060ab90140e7825d8127991DD3)
    +++ description: None
```

```diff
-   Status: DELETED
    contract UpgradeableBeacon (0x971f46a2852d11D59dbF0909e837cfd06f357DeB)
    +++ description: None
```

```diff
-   Status: DELETED
    contract MultiSend (0xA238CBeb142c10Ef7Ad8442C6D1f9E89e07e7761)
    +++ description: None
```

```diff
-   Status: DELETED
    contract Roles (0xF24f1DC519d88246809B660eb56D94048575d083)
    +++ description: None
```

Generated with discovered.json: 0x89400dca91a7d0ef56df44dae3bda28049f2ef91

# Diff at Thu, 11 Apr 2024 10:44:49 GMT:

- author: sekuba (<sekuba@users.noreply.github.com>)
- comparing to: main@4b6ab939705ef1b9fdc0ffd8813b4869519e6547 block: 19574841
- current block number: 19631863

## Description

Config related.

## Config/verification related changes

Following changes come from updates made to the config file,
or/and contracts becoming verified, not from differences found during
discovery. Values are for block 19574841 (main branch discovery), not current.

```diff
    contract EmergencyProposalExecutor (0x8180D59b7175d4064bDFA8138A58e9baBFFdA44a) {
    +++ description: None
      upgradeability.threshold:
+        "2 of 4 (50%)"
    }
```

```diff
    contract GnosisSafe (0x892bb7EeD71efB060ab90140e7825d8127991DD3) {
    +++ description: None
      upgradeability.threshold:
+        "4 of 8 (50%)"
    }
```

```diff
    contract HubPool Multisig (0xB524735356985D2f267FA010D681f061DfF03715) {
    +++ description: None
      upgradeability.threshold:
+        "3 of 5 (60%)"
    }
```

Generated with discovered.json: 0x71164dd68d40c603ad2f2be8190d8e65dd9a7765

# Diff at Wed, 03 Apr 2024 11:07:55 GMT:

- author: vincfurc (<10850139+vincfurc@users.noreply.github.com>)
- current block number: 19574841

## Description

- added Linea support
- SpokePool upgrade: various functions to register orders, updated to V3 specs. // does it use merkle proofs to withdraw funds?
  Plus some counters of filled orders and deposits. These counters are designed to implement a fee mechanism that is based on a canonical history of deposit and fill events and how they update a virtual running balance of liabilities and assets, which then determines the LP fee charged to relays. Plus some error handling, handling of non-expiring deposits.

Workflow - from the contract:
Request to bridge input token cross chain to a destination chain and receive a specified amount of output tokens. The fee paid to relayers and the system should be captured in the spread between output amount and input amount when adjusted to be denominated in the input token. A relayer on the destination chain will send outputAmount of outputTokens to the recipient and receive inputTokens on a repayment chain of their choice. Therefore, the fee should account for destination fee transaction costs, the relayer's opportunity cost of capital while they wait to be refunded following an optimistic challenge window in the HubPool, and the system fee that they'll be charged. On the destination chain, the hash of the deposit data will be used to uniquely identify this deposit, so modifying any params in it will result in a different hash and a different deposit. The hash will comprise all parameters to this function along with this chain's chainId(). Relayers are only refunded for filling deposits with deposit hashes that map exactly to the one emitted by this contract.

## Initial discovery

```diff
+   Status: CREATED
    contract VotingToken (0x04Fa0d235C4abf4BcF4787aF4CF447DE572eF828)
    +++ description: None
```

```diff
+   Status: CREATED
    contract TokenBridge (0x051F1D88f0aF5763fB888eC4378b4D8B29ea3319)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Arbitrum_Adapter (0x29528780E29abb8Af95a5e5a125b94766987543F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Base_Adapter (0x2d8B1e2B0Dff62DF132d23BEa68a6D2c4D20046E)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Boba_Adapter (0x33B0Ec794c15D6Cc705818E70d4CaCe7bCfB5Af3)
    +++ description: None
```

```diff
+   Status: CREATED
    contract BridgedToken (0x36f274C1C197F277EA3C57859729398FCc8a3763)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Polygon_Adapter (0x3E94e8d4316a1eBfb2245E45E6F0B8724094CE1A)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Finder (0x40f941E48A552bF496B154Af6bf55725f18D77c3)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProposerV2 (0x50efaC9619225d7fB4703C5872da978849B6E7cC)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Ethereum_Adapter (0x527E872a5c3f0C7c24Fe33F2593cFB890a285084)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ProxyAdmin (0x5B0bb17755FBa06028530682E2FD5bc373931768)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Ethereum_SpokePool (0x5c7BCd6E7De5423a257D81B442095A1a6ced35C5)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GovernorV2 (0x7b292034084A41B9D441B71b6E3557Edd0463fa8)
    +++ description: None
```

```diff
+   Status: CREATED
    contract LpTokenFactory (0x7dB69eb9F52eD773E9b03f5068A1ea0275b2fD9d)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Linea_Adapter (0x7Ea0D1882D610095A45E512B0113f79cA98a8EfE)
    +++ description: None
```

```diff
+   Status: CREATED
    contract EmergencyProposalExecutor (0x8180D59b7175d4064bDFA8138A58e9baBFFdA44a)
    +++ description: None
```

```diff
+   Status: CREATED
    contract OptimisticGovernor (0x8692B776d1Ff0664177c90465038056Dc64f8991)
    +++ description: None
```

```diff
+   Status: CREATED
    contract GnosisSafe (0x892bb7EeD71efB060ab90140e7825d8127991DD3)
    +++ description: None
```

```diff
+   Status: CREATED
    contract EmergencyProposer (0x91F1804aCaf87C2D34A34A70be1bb16bB85D6748)
    +++ description: None
```

```diff
+   Status: CREATED
    contract UpgradeableBeacon (0x971f46a2852d11D59dbF0909e837cfd06f357DeB)
    +++ description: None
```

```diff
+   Status: CREATED
    contract MultiSend (0xA238CBeb142c10Ef7Ad8442C6D1f9E89e07e7761)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Optimism_Adapter (0xAd1b0a86c98703fd5F4E56fff04F6b2D9b9f246F)
    +++ description: None
```

```diff
+   Status: CREATED
    contract HubPool Multisig (0xB524735356985D2f267FA010D681f061DfF03715)
    +++ description: None
```

```diff
+   Status: CREATED
    contract CoveredCallFinancialProductLibrary (0xBbc6009fEfFc27ce705322832Cb2068F8C1e0A58)
    +++ description: None
```

```diff
+   Status: CREATED
    contract HubPool (0xc186fA914353c44b2E33eBE05f21846F1048bEda)
    +++ description: None
```

```diff
+   Status: CREATED
    contract ZkSync_Adapter (0xE233009838CB898b50e0012a6E783FC9FeE447FB)
    +++ description: None
```

```diff
+   Status: CREATED
    contract BondToken (0xee1DC6BCF1Ee967a350e9aC6CaaAA236109002ea)
    +++ description: None
```

```diff
+   Status: CREATED
    contract Roles (0xF24f1DC519d88246809B660eb56D94048575d083)
    +++ description: None
```

```diff
+   Status: CREATED
    contract OptimisticOracleV3 (0xfb55F43fB9F48F63f9269DB7Dde3BbBe1ebDC0dE)
    +++ description: None
```
