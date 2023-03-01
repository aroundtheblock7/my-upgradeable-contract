# My-Upgradeable-Contract

#### In this project I have used Open Zeppelin's Upgradeable Package and Hardhat's upgradeable plugin to create 2 upgrades to the the inital smart contract using the Transparent Upgradeable Proxy Model. Open Zepp's upgradeable package includes an ERC1967 contract,  TransparentUpgradeableProxy contract, the Proxy Admin contract, the StorageSlot contract, and several additional contracts which allow for updates to the implemenation/logic contracts while using the Proxy contract for storage. The StorageSlot and ERC1967 contracts make it possible forward a new implemenation/logic address as and create new data structures (state vars, mappings, structs, arrays, etc) on the upgraded contrats without any storage collision on the Proxy. See photo below for upgrade confirmations on Goerli.

<img width="1082" alt="Screen Shot 2023-03-01 at 12 23 43 PM" src="https://user-images.githubusercontent.com/81759076/222219900-1017c7dc-30de-4cfe-a605-664957fb33b3.png">




