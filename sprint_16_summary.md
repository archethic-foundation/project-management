# Sprint 15 (Trisul)

> 08-Sept-22 to 28-Sept-22

## Sprint Goals

### AE Backend (Core Blockchain):
- Display more information on the explorer (network transaction listing, latest transactions realtime)
- Better management of timeouts for P2P communication
- Better management of P2P availability (BeaconChain)
- AEIP2 updates
- Improvement of the GraphQL API
- Bug fixes (sync and schedulers)
- Support of HTTPS for AEWeb websites

### AE Frontend (Wallet + Website):
- Stabilize the app post mainnet
- New feature: NFT management
- Document the app
- Update website with the nodes world map (3D)

### AE Research
- Structuring R&D processes
- Documentation Alignment

## Scope

### AE Backend (Core Blockchain):

#### AE Blockchain

- Total Issues completed: 25/27
- Total Story Points completed: 23 pts

| Sprint Planned                                                                                         | Sprint Summary |
| ------------------------------------------------------------------------------------------------------ | -------------- |
| [AEIP-2. Defined Metadata](archethic-foundation/aeip#4)                                                | Done           |
| [Add keychain transaction creation test](archethic-foundation/libjs#42)                                | Done           |
| [Create class/container for any interaction](archethic-foundation/libjs#27)                            | Done           |
| [Add test for API calls](archethic-foundation/libjs#80)                                                | Done           |
| [Add last transactions feed on the homepage](archethic-foundation/archethic-node#404)                  | Done           |
| [Reduce wait by parallelizing process](archethic-foundation/aeweb-cli#72)                              | Done           |
| [Amount management. Int format (10^8) from end to end](archethic-foundation/aeweb-cli#75)              | Done           |
| [Update sending workflow with last libjs implementation](archethic-foundation/aeweb-cli#76)            | Done           |
| [Improve node availability in beacon slots](archethic-foundation/archethic-node#569)                   | Done           |
| [AEIP-2. Comments on Properties](archethic-foundation/aeip#9)                                          | Done           |
| [Unspent outputs fetch causes timeouts](archethic-foundation/archethic-node#568)                       | Done           |
| [Add nearest_endpoints GraphQL query](archethic-foundation/archethic-node#572)                         | Done           |
| [Fix faucet limitation](archethic-foundation/archethic-node#571)                                       | Done           |
| [Update node index on bootstrap in case of DB lost](archethic-foundation/archethic-node#567)           | Done           |
| [Some fixes for P2P and OracleChain](archethic-foundation/archethic-node#563)                          | Done           |
| [Handle sending timeouts in P2P clients](archethic-foundation/archethic-node#510)                      | Done           |
| [Beacon chain loading takes to much time on explorer](archethic-foundation/archethic-node#458)         | Done           |
| [Drop transaction in beacon chains for slot and summaries](archethic-foundation/archethic-node#523)    | Done           |
| [Enforce resync of last network transactions after bootstrap](archethic-foundation/archethic-node#508) | Done           |
| [Prevent schedulers to be launched before end of bootstrap](archethic-foundation/archethic-node#543)   | Done           |
| [Rename token naming in the API calls](archethic-foundation/libdart#33)                                | Done           |
| [Explorer Inputs misplaced](archethic-foundation/archethic-node#560)                                   | Done           |
| [Add node rewards chain explorer](archethic-foundation/archethic-node#413)                             | Done           |
| [Add node shared secrets chain explorer](archethic-foundation/archethic-node#411)                      | Done           |
| [Certificate for Custom domains](archethic-foundation/archethic-node#449)                              | Done           |
| [Add timestamp in the unspent outputs](archethic-foundation/archethic-node#564)                        | Not Done       |
| [Add origin chain explorer](archethic-foundation/archethic-node#412)                                   | Done           |
| [Resolve Metric issues, : poller don't get metrics correctly](archethic-foundation/archethic-node#455) | Done           |

#### AE Website

- Total Issues completed: 7/8
- Total Story Points completed: 11 pts

| Sprint Planned                                                                                           | Sprint Summary |
| -------------------------------------------------------------------------------------------------------- | -------------- |
| [Wallet: Add link to mac Store](archethic-foundation/archethic-website#130)                              | Done           |
| [Integrate in main page Nodes worldmap emplacement (3D map)](archethic-foundation/archethic-website#110) | Done           |
| [Background pictures bug on newsfeed](archethic-foundation/archethic-website#122)                        | Not Done       |

#### AE Wallet

- Total Issues completed: 14/18
- Total Story Points completed: 97 pts

| Sprint Planned                                                                                              | Sprint Summary |
| ----------------------------------------------------------------------------------------------------------- | -------------- |
| [Error loading recent transactions when tx number > 10](archethic-foundation/archethic-wallet#262)          | Not Done       |
| [Flat theme - battery indicator is not visible](archethic-foundation/archethic-wallet#242)                  | Not Done       |
| [Message from a secret doesn't appear for the receiver](archethic-foundation/archethic-wallet#280)          | Done           |
| [Protect message in a transaction](archethic-foundation/archethic-wallet#266)                               | Done           |
| [NFT management](archethic-foundation/archethic-wallet#235)                                                 | Not Done       |
| [Add function to be notified of the error](archethic-foundation/archethic-wallet#270)                       | Not Done       |
| [Precise waiting confirmation informations](archethic-foundation/archethic-wallet#282)                      | Done           |
| [Add a contact from a transaction received or sent](archethic-foundation/archethic-wallet#275)              | Done           |
| [Video update - September](archethic-foundation/archethic-wallet#286)                                       | Done           |
| [Add build information near the version number in the menu](archethic-foundation/archethic-wallet#285)      | Done           |
| [Windows - Configuration feature](archethic-foundation/archethic-wallet#301)                                | Done           |
| [Add an option "Flat" on each theme instead of a specific theme](archethic-foundation/archethic-wallet#279) | Done           |
| [Add a control to avoid sending tokens to yourself](archethic-foundation/archethic-wallet#295)              | Done           |
| [Memory leak ](archethic-foundation/archethic-wallet#287)                                                   | Done           |
| [Problem displaying recent transactions](archethic-foundation/archethic-wallet#290)                         | Done           |
| [Check PickerWidget with small screen](archethic-foundation/archethic-wallet#298)                           | Done           |
| [Access to receive sheet from accounts list with long press](archethic-foundation/archethic-wallet#297)     | Done           |
| [Improve outlines](archethic-foundation/archethic-wallet#294)                                               | Done           |


#### R&D

- Total Issues completed: 0/2
- Total Story Points completed: 0 pts

| Sprint Planned                                                                                   | Sprint Summary |
| ------------------------------------------------------------------------------------------------ | -------------- |
| [Key generation using with User Input](archethic-foundation/biometrics#49)                       | Done           |
| [Using the internal ledger private key as origin keys](archethic-foundation/archethic-ledger#36) | Not Done       |

#### Summary

- Total Issues completed: 24/40
- Total Story Points completed: 104


