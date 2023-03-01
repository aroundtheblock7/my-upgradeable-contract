# My-Upgradeable-Contract

#### In this project I have used Open Zeppelin's Upgradeable Package and Hardhat's upgradeable plugin to create 2 upgrades to the the inital smart contract using the Transparent Upgradeable Proxy Model. Open Zepp's upgradeable package includes an ERC1967 contract,  TransparentUpgradeableProxy contract, the Proxy Admin contract, the StorageSlot contract, and several additional contracts which allow for updates to the implemenation/logic contracts while using the Proxy contact for storage. The StorageSlot and ERC1967 contracts also prevent storage collision allowing the new implemenation address, new variables, and other data structures (mappings, structs, arrays, etcc) on the upgraded contrats to be stored on the proxy without storage collision. See photo below for upgrade confirmations on Goerli.




