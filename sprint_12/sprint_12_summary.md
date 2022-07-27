# Sprint 12 (Mount Baigura)

> 14-July-22 to 27-July-22

### Goal

#### AE Blockchain:
- Finalize building the Miner Remuneration algorithm
- Bug bounty tracking and fixing important bugs

#### AE Website: 
- Tech update section: Improve look and feel
- Website architecture (hidden files) to be redesigned
- like in production, synchronize the preprod branch to the preprod environment (http redirection to be added)
- Integrate in main page Nodes worldmap emplacement

#### AE Wallet:
- Optimize UI in onboarding process
- Increase the nb of tx on the main screen
- Change Account (If users change account before loading the keychains)
- Bug bounty tracking and fixing important bugs 

### Scope

#### AE Blockchain
 - archethic-foundation/archethic-node#443 Replicate only missing transactions on Replication transaction chain
 - archethic-foundation/archethic-node#436 P2P view is invalid after quick disconnection of a node
 - archethic-foundation/archethic-node#408 Support varint to have a better list size encoding
 - archethic-foundation/archethic-node#381 Transform miner reward token to UCO
 - archethic-foundation/archethic-node#382 Schedule sending of reward tokens to the node reward address
 - archethic-foundation/archethic-node#380 Mint miner rewards token on self-repair cycle
 - archethic-foundation/archethic-node#445 Transaction subscriber should also returns error
 - archethic-foundation/archethic-node#447 Faucet - Provide control over the transaction chain and all nodes
 - archethic-foundation/archethic-node#456 Return fully validated transaction on Transaction Subscriber
 - archethic-foundation/archethic-node#458 Beacon chain loading takes to much time on explorer
 - archethic-foundation/archethic-node#430 Deserialization of Beacon Slot failed
 - archethic-foundation/archethic-node#473 Internal error when querying explorer/transactions
 - archethic-foundation/archethic-node#471 Internal error on graphql when requesting transaction input
 - archethic-foundation/archethic-node#469 Task timeout during mining process
 - archethic-foundation/libjs#63 Implement VarInt when getting signature payload
 - archethic-foundation/archethic-node#460 Node shared secrets chain write in loop during self repair
 - archethic-foundation/archethic-node#461 Database folder problem when releasing a new version
 - archethic-foundation/archethic-node#230 Take the testnet live on atleast 3 AE nodes
 - archethic-foundation/archethic-node#434 Database crash : Caused by terminating chain reader Process
 - archethic-foundation/archethic-node#425 Self-Repair timeouts with the new batching of summaries
 - archethic-foundation/archethic-node#457 Catch JSON format error on Explorer

#### AE Website
- archethic-foundation/archethic-website#79 Bridge - Explore solution
- archethic-foundation/archethic-website#87 Tech update section : Improve Look and feel
- archethic-foundation/archethic-website#94 Change ÆWeb by AEWeb everywhere in aeweb.html
- archethic-foundation/archethic-website#95 Mainnet Tasks
- archethic-foundation/archethic-website#96 Integrate in main page Nodes worldmap emplacement
#### - archethic-foundation/archethic-website#103 http redirection
#### - archethic-foundation/archethic-website#99 like in production, synchronize the preprod branch to the preprod environment

#### AE Keychains and ID Management
- archethic-foundation/biometrics#43 Prototyping DID with Python and Libsodium Part 1/3: Implementing Cryptography Functions
- archethic-foundation/biometrics#44 Prototyping DID with Python and Libsodium Part 2/3: Implementing Transaction Structure / Accessing
- archethic-foundation/biometrics#45 Prototyping DID with Python and Libsodium Part 3/3: Implementing DID

#### AE Wallet
- archethic-foundation/archethic-wallet#206 Change account : if users change account before the loading of the keychain, the account selected is not selected
- archethic-foundation/archethic-wallet#189 Contents (message) in transactions received are not available when we have several messages
- archethic-foundation/archethic-wallet#214 Balance doesn't appear sometimes
- archethic-foundation/archethic-wallet#220 Increase the nb of tx on the main screen
- archethic-foundation/archethic-wallet#216 Access faucet - Simplify the process to return to the app
- archethic-foundation/archethic-wallet#218 Add a way to hide/display balance info
- archethic-foundation/archethic-wallet#217 Blog - pb with main screen refresh
- archethic-foundation/archethic-wallet#219 Transfer UCO - Add control to check if the amount > 0

### Target
- Total Issues: 39
- Total Story Points: 177

### Target Achieved
- Total Issues completed: 28
- Total Story Points completed (This is not considered for this sprint as a lot of bugs were fixed and the story points of bugs could not be added)

### Observations 
- The team delivered well the Mainnet Bug bounty with fast fixing of bugs and its stabilization
- Need to better track and estimate the bugs that arise mid sprint 
