# Sprint 9

## Puy de Dome

> 02-June-22 to 15-June-22

### Goal

#### AE Blockchain (Backend)
- Testnet Live with at least 3 nodes 
- Testnet Stabilisation (also Global) 
- Origin Key Management / Device authorised key based on certificate
- Ledger Key implementation
- AEWeb (backend improvements)
- Networking Improvements (Port forwarding, UPnP, etc…)
- P2P Improvements
- UTXO management with IDs

#### AE Website and Wallet (Frontend)
- Finalization the Website Optimization (esbuild, webpack, etc...)
- 99designs application
- Add Keychain management
- multi accounts management 

#### AE Biometrics 
- Documentation finalization and approval (Global View)
- Test the Minutiae extraction algorithm (results + redesign if needed)

### Scope

#### Archethic Blockchain
- archethic-foundation/archethic-node#340 Update web hosting API to handle splited transaction
- archethic-foundation/archethic-node#375 Integrate MiniUPNP
- archethic-foundation/aeweb-cli#62 Handle website over than 3 MB
- archethic-foundation/archethic-node#351 Improve location using GeoLite2
- archethic-foundation/archethic-node#332 Support read quorum for P2P
- archethic-foundation/archethic-node#369 Implement read quorum
- archethic-foundation/archethic-node#330 Enforce tx size validation in API
- archethic-foundation/archethic-node#367 Support PCP for UPnP discovery and port forwarding#346
- archethic-foundation/libjs#55 Managing Origin Key
- archethic-foundation/archethic-node#326 Simplification of origin key management
- archethic-foundation/archethic-node#349 Change transaction fee with base fee
- archethic-foundation/archethic-node#361 Handle end of sync to make node available
- archethic-foundation/archethic-node#360 Fix beacon live transaction chain loading
- archethic-foundation/libdart#12 Add waitConfirmations function to listen acks
- archethic-foundation/archethic-node#371 Improve Transaction API validation
- archethic-foundation/archethic-node#318 Temporary unavailability of miners cause proof of election failure

#### Archethic Website
- archethic-foundation/archethic-website#71 Use new logos
- archethic-foundation/archethic-website#72 Add space between Paper links on hovering
- archethic-foundation/archethic-website#73 Fix scroll to uco section for mobile version
- archethic-foundation/archethic-website#74 Fix Lab section bug for desktop version
- archethic-foundation/archethic-website#68 Remove unused CSS
- archethic-foundation/archethic-website#66 Improve community section of the archethic.net website
- archethic-foundation/archethic-website#67 Improve mobile version of website

#### Archethic Biometrics
- archethic-foundation/biometrics#36 Documentation: Decentralized Identity (Part 4/4): Device Key & Transactions from after access to keychain
- archethic-foundation/biometrics#35 Documentation: Decentralized Identity (Part 3/4): Derivation path from keychain to Wallet Address
- archethic-foundation/biometrics#32 Documentation: Decentralized Identity (Part 1/4): From Private key to keychain Address
- archethic-foundation/biometrics#34 Documentation: Decentralized Identity (Part 2/4): Accessing keychain from Seed

#### Archethic Wallet
- archethic-foundation/archethic-wallet#95 Contact - Double error message when contact already exists
- archethic-foundation/archethic-wallet#55 [Feature] - Add multi-accounts management
- archethic-foundation/archethic-wallet#84 [Feature] - Add Keychain management
- archethic-foundation/archethic-wallet#80 Hive error
- archethic-foundation/archethic-wallet#88 Simplify the derivation path for the Archethic purpose

### Target
- Total Issues: 34 (2 issues from previous sprint)
- Total Story Points: 210

### Target Achieved
- Total Issues Completed: 26 
- Total Story Points Completed: 187

### Observations
- Issues got broken into smaller chuncks, which helped closures
- Waiting Buckets: Issues from QA / Review and Blockage / Dependencies need immediate attention

