# Sprint 19 (Grande Casse)

> 10-Nov-22 to 30-Nov-22

## Sprint Goals

### AE Backend (Core Blockchain):
- Fix some bugs 
- Improve AEWeb hosting
- Enhance protocol for scalability, performances and efficency

### Wallet
- Migrate to state management architecture (last sprint)
- NFT management (tests)
- Deploy 2 new versions in production
    - mid november
    - start of mainnet
- SDK optimization
- Specifications of the topic "Interactions/Interoperability with DApps”
- New video: Wallet update with Marketing’s team

### AE Collection generator
- Internal presentation of the subject
- Identification of the backlog for the MVP

### Archethic Website
- Maintenance

## Scope

### AE Backend (Core Blockchain):

#### AE Blockchain

- Total Issues completed: 23
- Total Story Points completed: 114

| Sprint Planned                                                                                                  | Sprint Summary |
| ------------------------------------------------------------------------------------------------------          | -------------- |
archethic-foundation/archethic-node#675 Add send timeout on connection                                              | Done.          |
archethic-foundation/archethic-node#714 Add ownerships in "token" graphQL request                                   | Done.          |
archethic-foundation/archethic-node#693 Calcul node reward based on scheduler time                                  | Done.          |
archethic-foundation/archethic-node#712 Update last transaction address only if the timestamp is greater            | Done.          |
archethic-foundation/archethic-node#714 Add ownerships in "token" graphQL request                                   | Done.          |
archethic-foundation/archethic-node#701 Add new API to get the version number of running code                       | Done.          |
archethic-foundation/archethic-node#677 Fix validation node election                                                | Done.          |
archethic-foundation/archethic-node#624 Purge Account UTXO table once an input is spent                             | Done.          |
archethic-foundation/archethic-node#697 Remove old daily keys from ets table                                        | Done.          |
archethic-foundation/archethic-node#692 Add quorum to request balance                                               | Done.          |
archethic-foundation/archethic-node#678 Check transaction's address existence during validation                     | Done.          |
archethic-foundation/archethic-node#663 Fix replication tree when sharding is applied                               | Done.          |
archethic-foundation/archethic-node#663 Fix replication tree when sharding is applied                               | Done.          |
archethic-foundation/archethic-node#691 Add default `code_change/4` in GenStateMachine                              | Done.          |
archethic-foundation/archethic-node#688 Fix recursion of notify last address                                        | Done.          |
archethic-foundation/archethic-node#627 Determines whether transaction input is spent from the last transaction in the chain    | Done.          |
archethic-foundation/archethic-node#661 Add @vsn attribute in genservers to prepare hot reload                      | Done.          |
archethic-foundation/archethic-node#681 Fix Proof of work existence for node transaction                            | Done.          |
archethic-foundation/archethic-node#685 Improve Task's timeout handling                                             | Done.          |
archethic-foundation/archethic-node#683 Use current node view for downloading while in self repair                  | Done.          |
archethic-foundation/archethic-node#679 Fix genesis pool amounts & addresses                                        | Done.          |
archethic-foundation/archethic-node#672 Optimize ack of previous shards                                             | Done.          |
archethic-foundation/archethic-node#691 Add default code_change/4 in GenStateMachine                                | Done.          |
archethic-foundation/archethic-node#628 Catch error in proof of work to get contracts parsing error                 | Pending.          |
archethic-foundation/archethic-node#596 Listing directory for web hosting deployment without index.html             | Pending.          |
archethic-foundation/archethic-node#696 Do not send replication message if validation has error                     | Pending.          |
archethic-foundation/archethic-node#710 Use asynchronous connection                                                 | Pending.          |
archethic-foundation/archethic-node#695 Number of validation nodes should not be more than replica number           | Pending.          |
archethic-foundation/archethic-node#699 Oracle live display new oracle summary on any page                          | Pending.          |
archethic-foundation/archethic-node#645 Fix self-repair notifier                                                    | Pending.          |
archethic-foundation/archethic-node#566 Notify beacon summary in case of network topology change                    | Pending.          |
archethic-foundation/archethic-node#642 Improving connection timeout                                                | Pending.          |


#### AEWeb

| Sprint Planned                                                                                                  | Sprint Summary |
| ------------------------------------------------------------------------------------------------------          | -------------- |
archethic-foundation/aeweb-cli#86 Add more informations in reference transaction                                   | Pending.       |
archethic-foundation/aeweb-cli#82 Support of .git folder and .gitignore                                            | Pending.       |
archethic-foundation/aeweb-cli#83 Handle website update                                                            | Pending.       |
archethic-foundation/aeweb-cli#67 Not possible to push a basic site                                                | Done.          |


### AE Wallet

- Total Issues completed: 21
- Total Story Points completed: 49 (declared) 

| Sprint Planned                                                                                                                  | Sprint Summary |
| -----------------------------------------------------------------------------------------------------------                     | -------------- |
archethic-foundation/archethic-wallet#394 Set mainnet as default in onboarding | Done. |
archethic-foundation/archethic-wallet#411 Importation of account doesn't work | Done. |
archethic-foundation/archethic-wallet#422 NFT Creation : Remove public keys | Done. |
archethic-foundation/archethic-wallet#416 Migrate market price and market chart to riverpod | Done. |
archethic-foundation/archethic-wallet#242 Flat theme - battery indicator is not visible | Done. |
archethic-foundation/archethic-wallet#328 Take into account the GraphQL query joins | Done. |
archethic-foundation/archethic-wallet#290 Problem displaying recent transactions | Done. |
archethic-foundation/archethic-wallet#262 Error loading recent transactions when tx number > 10 | Done. |
archethic-foundation/archethic-wallet#412 Manage dynamic properties and associated public keys | Not done. |
archethic-foundation/archethic-wallet#317 Add visuals for NFTs that are not images or pdf | Done. |
archethic-foundation/archethic-wallet#187 When a keychain receive transfer on several services (accounts), notification informs user on only one service | Done. |
archethic-foundation/archethic-wallet#410 Specifications of the topic "Interactions/Interoperability with DApps” | Done. |
archethic-foundation/archethic-wallet#477 Sometimes, the wrong NFT is sent to a recipient | Done. |
archethic-foundation/archethic-wallet#474 Add next the QR Code with 2 functions: viewing the content and copy and paste | Done. |
archethic-foundation/archethic-wallet#470 List accounts - Homogenize the number of lines by keeping the height fixed | Done. |
archethic-foundation/archethic-wallet#469 Move NFT menu to the bottom | Done. |
archethic-foundation/archethic-wallet#422 NFT Creation : Remove public keys | Done. |
archethic-foundation/archethic-wallet#417 Allow to change the category of an NFT | Done. |
archethic-foundation/archethic-wallet#415 Add waiting message when users create new account | Done. |
archethic-foundation/archethic-wallet#411 Importation of account doesn't work | Done. |
archethic-foundation/archethic-wallet#400 Standardize font sizes | Done. |

### AE Collection generator

- Total Issues completed: 2
- Total Story Points completed: 28

| Sprint Planned                                                                                           | Sprint Summary |
| -------------------------------------------------------------------------------------------------------- | -------------- |
archethic-foundation/archethic-collection-generator#1 Definition of the backlog | Done. |
archethic-foundation/archethic-collection-generator#2 Organize an internal demonstration | Done. |
archethic-foundation/archethic-collection-generator#4 Perform Testing | Done. |

### AE Website 

- Total Issues completed: 3
- Total Story Points completed: 2

| Sprint Planned                                                                                           | Sprint Summary |
| -------------------------------------------------------------------------------------------------------- | -------------- |
archethic-foundation/archethic-website#141 Remove AENFT references | Done. |
archethic-foundation/archethic-website#136 Dynamic Roadmap | Not done. |
Add LinkedIn links | Done. |



### Summary

- Total Issues completed: 
- Total Story Points completed: 
