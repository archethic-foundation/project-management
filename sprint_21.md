# Sprint 21

> 09/01/2023 to 27/01/2023

## Sprint Goals

### AE Backend (Core Blockchain):
- Smart Contract enhancements
- BeaconChain network patch
- Optimize memory & handle off-loading of ETS tables
- Rework on the NAT Discovery to support more network configuration
- Enhancements of APIs
- Smart Contract's fee

### AEWeb
- Integrating cache 
- Optimizations for websites updates
- SSL certificate automation
- Publish Github Actions

### Wallet
- Yubikey SDK (PIV)
- AEIP 4 / Decentralized app / Wallet communication
- Tests end to end
- Help users to manage their tokens (burn/hide features)
- Maintenance

### Dart SDK
- Improve and standardize architecture
- Maintenance

### Bridge
- Manage feedbacks from HTML/CSS integration

### AE Collection generator
- Provide the MVP
- AEIP 4 / Decentralized app / Wallet communication

### Archethic Website
- Maintenance

## Scope

### AE Backend (Core Blockchain):

#### AE Blockchain

- Total Issues estimated: 
- Total Story Points estimated: 

- Total Issues completed: 
- Total Story Points completed: 

| Sprint Planned | Sprint Summary |
| -------------- | -------------- |
| archethic-foundation/archethic-node#726 Add new types of transaction      | done.      |
| archethic-foundation/archethic-node#779 Improve atomic commitment for replication | done.      |
| archethic-foundation/archethic-node#786 Improve atomic commitment replication  | done.      |
| archethic-foundation/archethic-node#808 Add getGenesisAddress query to graphql. | done.      |
| archethic-foundation/archethic-node#728 Fetch UCO price from coinPaprika    | done.      |
| archethic-foundation/archethic-node#729 Fetch UCO price from CoinMarketCap  | done.      |
| archethic-foundation/archethic-node#698 Upnp port forwarding fail on local ip change  | done.      |
| archethic-foundation/archethic-node#700 Forwarding random port with upnpc | done.      |
| archethic-foundation/archethic-node#727 Create an oracle data aggregator  | done.      |
| archethic-foundation/archethic-node#639 Add new API to get beacon aggregate | done.      |
| archethic-foundation/archethic-node#795 Add previous transaction address in GraphQl transaction schema | done.      |
| archethic-foundation/archethic-node#785 Use Interpreter parsing to check the prior code | done.      |
| archethic-foundation/archethic-node#409 Provide a better validation for typed transaction | done.      |
| archethic-foundation/archethic-node#730 For explorer, fetch data from DB if they are available  | done.      |
| archethic-foundation/archethic-node#711 Burned fee transfer should not be sent to IO node   | done.      | 
| archethic-foundation/archethic-node#512 Add the possibility to get the inputs in the smart contract | Not done      |
| archethic-foundation/libjs#92 Add function to update a keychain| Not done      |
| archethic-foundation/archethic-node#768 Add anti DDOS for abusive requests on the API| Not done      |
| archethic-foundation/archethic-node#823 DB: nested fields are returned empty| Not done      |
| archethic-foundation/archethic-node#825 Bug: Restarting a node is not starting the SC workers| Not done      |
| archethic-foundation/archethic-node#610 Specify the hash algorithm in the SC library functions| Not done      |
| archethic-foundation/archethic-node#740 Add `get_first_address` in smart contract library| Not done      |
| archethic-foundation/archethic-node#826 SC functions to work on lists| Not done      |
| archethic-foundation/archethic-node#843 Check_the_validity_of_addresses_in_the_SC_statements#616| Not done      |
| archethic-foundation/archethic-node#799 Refactor Message module| Not done      |
| archethic-foundation/archethic-node#57 Validate smart contract calls| Not done      |
| archethic-foundation/archethic-node#616 Check the validity of addresses in the SC statements| Not done      |
| archethic-foundation/archethic-node#642 Improving connection timeout| Not done      |
| archethic-foundation/archethic-node#607 Implement the SC transaction fee model| Not done      |
| archethic-foundation/archethic-node#757 Update Node's geo patch with mmdb2 updates| Not done      |
| archethic-foundation/archethic-node#796 Write inputs of burn address in DB instead of keeping it in memory| Not done      |
| archethic-foundation/archethic-node#47 Support inheritance exception based on the multiple secrets and proof of ownership| Not done      |
| archethic-foundation/archethic-node#159 Create a program to compute network patch| Not done      |
| archethic-foundation/archethic-node#811 Off-loading of memory tables| Not done      |
| archethic-foundation/archethic-node#811 Off-loading of memory tables| Not done      |
| archethic-foundation/archethic-node#741 Add resolved destination in smart contract constants| Not done      |
| archethic-foundation/archethic-node#812 Improve SC interval triggers| Not done      |

#### AEWeb

- Total Issues estimated: 
- Total Story Points estimated: 

- Total Issues completed: 
- Total Story Points completed: 
  
| Sprint Planned | Sprint Summary |
| -------------- | -------------- |
| archethic-foundation/archethic-node#644 AEWeb: improve files response by caching their content     | done.      |
|archethic-foundation/aeweb-cli#92 Fix deploy | done.      |
|archethic-foundation/archethic-node#643 AEWeb: provide an API to returns hash of all files content for a website | done.      |
|archethic-foundation/aeweb-cli#86 Add more informations in reference transaction | done.      |
|archethic-foundation/archethic-node#774 Transaction's details timeout with internal server error | done.      |
|archethic-foundation/archethic-node#800 AEWeb: display the size when listing the files of a directory | Not done      |
|archethic-foundation/aeweb-cli#82 Support of .git folder and .gitignore| Not done      |
|archethic-foundation/aeweb-cli#83 Handle website update| Not done      |


### Wallet

- Total Issues estimated: 4
- Total Story Points estimated: 67 

- Total Issues completed: 
- Total Story Points completed: 

| Sprint Planned                                                                                                                               | Sprint Summary |
| -------------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| https://github.com/archethic-foundation/archethic-wallet/issues/580 Error when the size of a NFT exceeds the size of the transaction content | Not done.      |
| https://github.com/archethic-foundation/archethic-wallet/issues/569  Burn                                                                    | Not done.      |
| https://github.com/archethic-foundation/archethic-wallet/issues/552 Allow to hide tokens on his wallet                                       | Not done.      |
| https://github.com/archethic-foundation/archethic-wallet/issues/612 Use Yubikey to manage seed                                               | Not done.      |

### Dart SDK

- Total Issues estimated: 1
- Total Story Points estimated: 2 

- Total Issues completed: 
- Total Story Points completed: 

| Sprint Planned                                                                                     | Sprint Summary |
| -------------------------------------------------------------------------------------------------- | -------------- |
| https://github.com/archethic-foundation/libdart/issues/58 Transaction fee API - Error parsing json | Not done.      |

### AE Collection generator

- Total Issues estimated: 3
- Total Story Points estimated: 47

- Total Issues completed: 
- Total Story Points completed: 

| Sprint Planned                                                                                                       | Sprint Summary |
| -------------------------------------------------------------------------------------------------------------------- | -------------- |
| - https://github.com/archethic-foundation/archethic-collection-generator/issues/6 Create nft collection              | Not done.      |
| - https://github.com/archethic-foundation/archethic-collection-generator/issues/5 Configure uploading data via aeweb | Not done.      |
| - https://github.com/archethic-foundation/archethic-collection-generator/issues/3 Create a landing page              | Not done.      |

### AE Website 

- Total Issues estimated: 2
- Total Story Points estimated: 13 

- Total Issues completed: 
- Total Story Points completed: 

| Sprint Planned                                                                                                                                                            | Sprint Summary |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| https://github.com/archethic-foundation/archethic-website/issues/155 Add a new section in website to show our partners                                                    | Not done.      |
| https://github.com/archethic-foundation/archethic-website/issues/154 Display latest five articles under global tab when latest article is from partnership or tech update | Not done.      |

### Summary

- Total Issues estimated: 
- Total Story Points estimated: 

- Total Issues completed: 
- Total Story Points completed: 
