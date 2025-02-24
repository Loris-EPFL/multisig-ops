# Ethereum DAO Multisig

[Tenderly]()

[Sign nonce xxx](https://app.safe.global/transactions/queue?safe=eth:0x10A19e7eE7d7F8a52822f6817de8ea18204F2e4f)

```
+----------+-------------------------------------------------+------------------------------------------------------------------------+----------------------------+---------+----------+
| function | token_symbol                                    | recipient                                                              | amount                     |   bip   | tx_index |
+----------+-------------------------------------------------+------------------------------------------------------------------------+----------------------------+---------+----------+
| transfer | USDC:0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48 | multisigs/foundation_opco:0x3B8910F378034FD6E103Df958863e5c684072693   | 35200.0 (RAW: 35200000000) | BIP-786 |    0     |
| transfer | USDC:0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48 | payees/hypernative_payments:0x5CA24e2A586834A7B96216D68b26A82405e3DC15 | 80000.0 (RAW: 80000000000) | BIP-775 |    3     |
+----------+-------------------------------------------------+------------------------------------------------------------------------+----------------------------+---------+----------+
```

```
+-----------------------+---------------------+--------------------------------------------+----------------------------------------------------------------------------------------+--------------------------------------------------------------------+---------+----------+
| function              | caller_name         | caller_address                             | fx_paths                                                                               | action_ids                                                         |   bip   | tx_index |
+-----------------------+---------------------+--------------------------------------------+----------------------------------------------------------------------------------------+--------------------------------------------------------------------+---------+----------+
| Authorizer/grantRoles | multisigs/maxi_omni | 0x9ff471F9f98F42E5151C7855fD1b5aa906b1AF7e | 20250121-v3-stable-surge/StablePool/startAmplificationParameterUpdate(uint256,uint256) | 0x3050dfbb6294dc29c5cae13acb241fddea61d345d9b8c809f216c8259b013ff8 | BIP-787 |    1     |
|                       |                     |                                            | 20250121-v3-stable-surge/StablePool/stopAmplificationParameterUpdate()                 | 0x866d7d17a9b007d202e4da84f38a0bfbb310db8184a4f1d2e6de3c8e78ecd1e0 |         |          |
| Authorizer/grantRoles | multisigs/maxi_omni | 0x9ff471F9f98F42E5151C7855fD1b5aa906b1AF7e | 20250121-v3-stable-surge/StableSurgeHook/setMaxSurgeFeePercentage(address,uint256)     | 0x2f27aa67b6bf44b4441ea2656c22e09252261845a98dc577a6fc06b6526f8bcc | BIP-778 |    2     |
|                       |                     |                                            | 20250121-v3-stable-surge/StableSurgeHook/setSurgeThresholdPercentage(address,uint256)  | 0x66c657ea0d5ce1dc0286795937131c61620bb6ccd0f126fbfe3799d8b89a9753 |         |          |
+-----------------------+---------------------+--------------------------------------------+----------------------------------------------------------------------------------------+--------------------------------------------------------------------+---------+----------+
```

# Gnosis DAO Multisig

[Tenderly]()

[Sign nonce xxx](https://app.safe.global/transactions/queue?safe=gno:0x2a5AEcE0bb9EfFD7608213AE1745873385515c18)

```
+-----------------------+---------------------+--------------------------------------------+----------------------------------------------------------------------------------------+--------------------------------------------------------------------+---------+----------+
| function              | caller_name         | caller_address                             | fx_paths                                                                               | action_ids                                                         |   bip   | tx_index |
+-----------------------+---------------------+--------------------------------------------+----------------------------------------------------------------------------------------+--------------------------------------------------------------------+---------+----------+
| Authorizer/grantRoles | multisigs/maxi_omni | 0x9ff471F9f98F42E5151C7855fD1b5aa906b1AF7e | 20250121-v3-stable-surge/StableSurgeHook/setMaxSurgeFeePercentage(address,uint256)     | 0x7380cab0ed6c5f6a40913d98c4931ae4d29a059fa33ae27635ab1f4f6e4c5077 | BIP-778 |    0     |
|                       |                     |                                            | 20250121-v3-stable-surge/StableSurgeHook/setSurgeThresholdPercentage(address,uint256)  | 0x4fdd01a86430670b9ac98e6baa39e03b7df692fb1c7c988b41fa7d510f8ff7e7 |         |          |
| Authorizer/grantRoles | multisigs/maxi_omni | 0x9ff471F9f98F42E5151C7855fD1b5aa906b1AF7e | 20250121-v3-stable-surge/StablePool/startAmplificationParameterUpdate(uint256,uint256) | 0x4acf55e494b685b95a5b14cf8c5507d75bd1aa71a85fc1214c0e8b825a469170 | BIP-787 |    1     |
|                       |                     |                                            | 20250121-v3-stable-surge/StablePool/stopAmplificationParameterUpdate()                 | 0x472cb2d86bd228ad5c01dda464760927533d1f2075d5857fb2c01bfee9790125 |         |          |
+-----------------------+---------------------+--------------------------------------------+----------------------------------------------------------------------------------------+--------------------------------------------------------------------+---------+----------+
```

# Base DAO Multisig

[Tenderly]()

[Sign nonce xxx](https://app.safe.global/transactions/queue?safe=base:0xC40DCFB13651e64C8551007aa57F9260827B6462)

```
+-----------------------+---------------------+--------------------------------------------+----------------------------------------------------------------------------------------+--------------------------------------------------------------------+---------+----------+
| function              | caller_name         | caller_address                             | fx_paths                                                                               | action_ids                                                         |   bip   | tx_index |
+-----------------------+---------------------+--------------------------------------------+----------------------------------------------------------------------------------------+--------------------------------------------------------------------+---------+----------+
| Authorizer/grantRoles | multisigs/maxi_omni | 0x9ff471F9f98F42E5151C7855fD1b5aa906b1AF7e | 20250121-v3-stable-surge/StableSurgeHook/setMaxSurgeFeePercentage(address,uint256)     | 0xe81edd4ccc5901443972e580b5d997ced38f33bd4f7e9bca8829dc5efcca6fed | BIP-778 |    0     |
|                       |                     |                                            | 20250121-v3-stable-surge/StableSurgeHook/setSurgeThresholdPercentage(address,uint256)  | 0x4a7d099f7d634af69cf552b5b1c76ed8d44074051cbca5a59b842154288b96f1 |         |          |
| Authorizer/grantRoles | multisigs/maxi_omni | 0x9ff471F9f98F42E5151C7855fD1b5aa906b1AF7e | 20250121-v3-stable-surge/StablePool/startAmplificationParameterUpdate(uint256,uint256) | 0xbf865f1c6f8d104fabfc55638d1622f92901741c27314f329670c51b54f3eded | BIP-787 |    1     |
|                       |                     |                                            | 20250121-v3-stable-surge/StablePool/stopAmplificationParameterUpdate()                 | 0x1a357d5b1643481255960a2981adcdd96069c98aff413a5e8387d5e199d34a64 |         |          |
+-----------------------+---------------------+--------------------------------------------+----------------------------------------------------------------------------------------+--------------------------------------------------------------------+---------+----------+
```

# Arbitrum DAO Multisig

[Tenderly]()

[Sign nonce xxx](https://app.safe.global/transactions/queue?safe=arb1:0xaF23DC5983230E9eEAf93280e312e57539D098D0)

```
+-----------------------+---------------------+--------------------------------------------+----------------------------------------------------------------------------------------+--------------------------------------------------------------------+---------+----------+
| function              | caller_name         | caller_address                             | fx_paths                                                                               | action_ids                                                         |   bip   | tx_index |
+-----------------------+---------------------+--------------------------------------------+----------------------------------------------------------------------------------------+--------------------------------------------------------------------+---------+----------+
| Authorizer/grantRoles | multisigs/maxi_omni | 0x9ff471F9f98F42E5151C7855fD1b5aa906b1AF7e | 20250121-v3-stable-surge/StableSurgeHook/setMaxSurgeFeePercentage(address,uint256)     | 0x261258d23af1013ceb3a0574a5f194e3d4d09a07c0b9014665519c3f1b37f792 | BIP-778 |    0     |
|                       |                     |                                            | 20250121-v3-stable-surge/StableSurgeHook/setSurgeThresholdPercentage(address,uint256)  | 0x5968f4b1f98171ccadc78df4f25cf8262b250f2f12a83c45b7311b4674d23e0a |         |          |
| Authorizer/grantRoles | multisigs/maxi_omni | 0x9ff471F9f98F42E5151C7855fD1b5aa906b1AF7e | 20250121-v3-stable-surge/StablePool/startAmplificationParameterUpdate(uint256,uint256) | 0x2fbb47746d921903b9f91d439cf9e524a40a377607923d64f01c38c5d0ea1b14 | BIP-787 |    1     |
|                       |                     |                                            | 20250121-v3-stable-surge/StablePool/stopAmplificationParameterUpdate()                 | 0xdecec4789661e9e43897955fb7d3796d8f5159ba0cc6593dbf71f88c8f4da475 |         |          |
+-----------------------+---------------------+--------------------------------------------+----------------------------------------------------------------------------------------+--------------------------------------------------------------------+---------+----------+
```
