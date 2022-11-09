# Sprint 15 (Chaukhamba)

> 20-Oct-22 to 09-Nov-22

## Sprint Goals

### AE Backend (Core Blockchain):
- Bug fixes and stabilization for P2P/SelfRepair in order to include more nodes
- Migration for technical debt (Elixir/Dependencies)
- Improve SC SDK
- Improve AEWEB API

### AEWEB CLI
- Improve update of websites
- Reduce size of deployed websites

### Wallet
- Migrate to state management architecture
- Update Icons
- New feature: NFT management

### Research
- Finish research of Malicious Detection and Elimination Algorithm 
- Get started with Node Gamification Research (Literature Review, Idea and Hypothesis validation)

## Scope

### AE Backend (Core Blockchain):

#### AE Blockchain

- Total Issues completed: 
- Total Story Points completed: 

| Sprint Planned                                                                                                  | Sprint Summary |
| ------------------------------------------------------------------------------------------------------          | -------------- |
archethic-foundation/archethic-node#675 Add send timeout on connection                                            | Done.          |
archethic-foundation/archethic-node#638 Upgrade js dependencies to fix vulnerabilities                            | Done.          |
archethic-foundation/archethic-node#649 Ensure download of self repair on other locally available nodes           | Done.          |
archethic-foundation/archethic-node#647 Deterministic transaction fee                                             | Done.          |
archethic-foundation/archethic-node#652 Fix self repair bugs                                                      | Done.          |
archethic-foundation/archethic-node#584 Certificate in origin_key api is not checked                              | Done.          |
archethic-foundation/archethic-node#655 Cancel oracle polling timer when a rescheduling is started                | Done.          |
archethic-foundation/archethic-node#656 Prevent update of node availability history during node update            | Done.          |
archethic-foundation/archethic-node#657 Stop self repair if transaction's processing failed                       | Done.          |
archethic-foundation/archethic-node#653 Fix beacon date projections                                               | Done.          |
archethic-foundation/archethic-node#658 Update dependencies                                                       | Done.          |
archethic-foundation/archethic-node#660 Prevent existing beacon aggregate to be rewritten on migrate.sh           | Done.          |
archethic-foundation/archethic-node#651 Version transaction structs to ease data migrations                       | Done.          |
archethic-foundation/archethic-node#662 Fix bootstraping bugs                                                     | Done.          |
archethic-foundation/archethic-node#665 Fix connection                                                            | Done.          |
archethic-foundation/archethic-node#666 Handle ipv6 local ip in node settings page                                | Done.          |
archethic-foundation/archethic-node#667 Add lower timeout for replication error notification                      | Done.          |
archethic-foundation/archethic-node#669 Update installation and release scripts to use asdf                       | Done.          |
archethic-foundation/archethic-node#642 Improve connection timeout                                                | Pending.       |
archethic-foundation/archethic-node#596 Listing directory for web hosting deployment without index.html           | Pending        |
archethic-foundation/archethic-node#643 Provide AEWEB API to return hash of all files for a website               | Pending        |
archethic-foundation/archethic-node#644 Improve files responses by caching content                                | Pending        |
archethic-foundation/archethic-node#628 Improve smart contract interpreter (error handling)                       | Pending        |
archethic-foundation/archethic-node#624 Purge spend UTXO in the Account mem tables                                | Pending        |
archethic-foundation/archethic-node#627 Determines whether transaction input is spent from the last transaction   | Pending        |
archethic-foundation/archethic-node#639 Add API to get beacon's aggregate                                         | Pending        |
archethic-foundation/archethic-node#610 Specify hash of algorithm in SC library                                   | Pending        |
archethic-foundation/archethic-node#615 Add comparison date in SC library                                         | Pending        |
archethic-foundation/archethic-node#640 Add token id function in SC library                                       | Pending        |
archethic-foundation/archethic-node#616 Check validity of addresses in SC                                         | Pending        |



## AEWEB CLI

- Total Issues completed: 
- Total Story Points completed: 

| Sprint Planned                                                                                                  | Sprint Summary |
| ------------------------------------------------------------------------------------------------------          | -------------- |
archethic-foundation/aeweb-cli#82 Support of .git and .gitignore                                                  | Pending |
archethic-foundation/aeweb-cli#83 Handle website update                                                           | Pending |
archethic-foundation/aeweb-cli#81 Modularize code                                                                 | Done |



### AE Wallet

- Total Issues completed: 
- Total Story Points completed: 

| Sprint Planned                                                                                                                  | Sprint Summary |
| -----------------------------------------------------------------------------------------------------------                     | -------------- |
archethic-foundation/archethic-wallet#376 Add new icons                                                                           | Done.          |
archethic-foundation/archethic-wallet#371 🎨 Transfer feature - Refactoring                                                       | Done.          |
archethic-foundation/archethic-wallet#370 :art: authentication refacto.                                                           | Done.          |
archethic-foundation/archethic-wallet#379 UI improvements                                                                         | Done.          |
archethic-foundation/archethic-wallet#347 Error with currency choice update                                                       | Done.          |
archethic-foundation/archethic-wallet#320 Transfer sheet : distinct token and uco management more clearly                         | Done.          |
archethic-foundation/archethic-wallet#375 🐛 Nft refacto                                                                          | Done.          |
archethic-foundation/archethic-wallet#182 Sometimes, notifications are received when the icon is disabled or when user manages his keychain | Done.|
archethic-foundation/archethic-wallet#380 🐛 fix regressions following riverpod refactoring                                        | Done.          |
archethic-foundation/archethic-wallet#381 Add scrollbars                                                                          | Done.          |
archethic-foundation/archethic-wallet#365 Improve the UX in the display of the 24 words list                                      | Done.          |
archethic-foundation/archethic-wallet#346 Error with checkTransactionInputs                                                       | Done.          |
archethic-foundation/archethic-wallet#299 Import seed - wrongly deactivated button                                                | Done.          |
archethic-foundation/archethic-wallet#306 The NFT category index does not work after a sorting change                              | Done.          |
archethic-foundation/archethic-wallet#292 Change the icons in the app                                                              | Done.          |
archethic-foundation/archethic-wallet#383 🎨 fungibles tokens refacto                                                              | Done.          |
archethic-foundation/archethic-wallet#384 Configure new logo app                                                                   | Done.          |
archethic-foundation/archethic-wallet#385 :fix: Handle CanceledTask exceptions.                                                    | Done.          |
archethic-foundation/archethic-wallet#377 :bug: Fix home constant reload                                                            | Done.          |
archethic-foundation/archethic-wallet#388 Change Riverpod libs version                                                              | Done.          |
archethic-foundation/archethic-wallet#390 iOS - use image without transparency to be conform with app Store                         | Done.          |
archethic-foundation/archethic-wallet#389 iOS icon not conform                                                                      | Done.          |
archethic-foundation/archethic-wallet#392 391 add token add waiting message to avoid double validation                              | Done.          |
archethic-foundation/archethic-wallet#391 Add token : Add waiting message to avoid double validation                                | Done.          |
archethic-foundation/archethic-wallet#341 Token fungible creation : check balance                                                   | Done.          |
archethic-foundation/archethic-wallet#386 Scroll bar doesn't work with desktop platform                                             | Done.          |
archethic-foundation/archethic-wallet#393 🎨 Migrate NFT Management to last architecture                                             | Done.          |
archethic-foundation/archethic-node#675 Add send timeout on connection                                                              | Done.          |
archethic-foundation/aeweb-cli#81 Modularize the business logic                                                                      | Done.          |
archethic-foundation/archethic-wallet#378 :art: Extract appwallet from StateContainer.                                                | Done.          |
archethic-foundation/archethic-wallet#404 :shirt: remove curNetwork from StateContainer.                                                | Done.          |
archethic-foundation/archethic-wallet#405 :shirt: remove unused properties from StateContainer.                                       | Done.          |
archethic-foundation/archethic-wallet#403 :bug: Fix wallet deletion.                                                                  | Done.          |
archethic-foundation/archethic-wallet#399 Create a widget with Scrollbar and SingleChildScrollView widgets                            | Done.          |
archethic-foundation/archethic-wallet#387 🎨 Market management - migration to Riverpod                                                 | Done.          |
archethic-foundation/archethic-wallet#369 Chart not available                                                                          | Done.          |
 


### AE Website 
| Sprint Planned                                                                                           | Sprint Summary |
| -------------------------------------------------------------------------------------------------------- | -------------- |
| [Dynamic roadmap#136](archethic-foundation/archethic-website#122)                                        | Done           |
archethic-foundation/archethic-website#122 Background pictures bug on newsfeed                             | Done.          |

### Summary

- Total Issues completed: 
- Total Story Points completed: 
