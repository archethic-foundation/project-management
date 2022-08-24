# Sprint 14 (Chamundi Hill)

> 11-August-22 to 24-August-22

### Goal

#### AE Blockchain:
- Hardening and stabilization of the network
- Improve transaction processing integrity
- Issue fixing

#### AE Website: 
- Create a 404 error page
- Integrate in main page Nodes worldmap emplacement
- Blog's articles section - Change the data source of the summary

#### AE Wallet
- Stabilize the app post mainnet
- New feature: NFT management
- Document the app

### Scope

#### AE Blockchain
Sprint Planned | Sprint Summary
------------- | -------------
[Add unique identification in the token API](https://github.com/archethic-foundation/archethic-node/issues/503)| Done
[Use authorized node in the election to fetch transaction details remotely](https://github.com/archethic-foundation/archethic-node/issues/521) | Done
[Handle conflicts in the resolving of the last transaction addres](https://github.com/archethic-foundation/archethic-node/issues/520) | Done
[Sef default max confirmation in transaction subscriber](https://github.com/archethic-foundation/archethic-node/issues/522) | Done
[Add function to be notified of the error](https://github.com/archethic-foundation/libjs/issues/66) | Done
[Improve replication error explicitness](https://github.com/archethic-foundation/archethic-node/issues/504) | Done
[Start listening P2P connections after complete bootstrap](https://github.com/archethic-foundation/archethic-node/issues/507) | Done
[Transaction movement type mapping is incorrect](https://github.com/archethic-foundation/archethic-node/issues/497) | Done
[Make chain replication asynchronous](https://github.com/archethic-foundation/archethic-node/issues/498) | Done
[Improve latency handling](https://github.com/archethic-foundation/archethic-node/issues/494) | Done
[Add the possibility to get the inputs in the smart contract ](https://github.com/archethic-foundation/archethic-node/issues/512) | Not Done
[Resolve Metric issues, : poller don't get metrics correctly](https://github.com/archethic-foundation/archethic-node/issues/455) | Not Done
[Handle sending timeouts in P2P clients](https://github.com/archethic-foundation/archethic-node/issues/510) | Not Done
[Cancellation of GraphQL subscription](https://github.com/archethic-foundation/libjs/issues/67) | Not Done
[Ensure network transaction type only passed in a network transaction chain](https://github.com/archethic-foundation/archethic-node/issues/423) | Not Done
[Enforce resync of last network transactions after bootstrap] (https://github.com/archethic-foundation/archethic-node/issues/508) | Not Done
[Beacon chain loading takes to much time on explorer](https://github.com/archethic-foundation/archethic-node/issues/458) | Not Done
[Add error detection in fetch](https://github.com/archethic-foundation/libjs/issues/65) | Not Done
[Provide a way to get the last value of an oracle](https://github.com/archethic-foundation/archethic-node/issues/451) | Not Done
[Verify scheduled transaction only happens once](https://github.com/archethic-foundation/archethic-node/issues/421) | Not Done
[Verify if transaction exists before validation](https://github.com/archethic-foundation/archethic-node/issues/502) | Not Done
[Prevent scheduled transaction to be sent in the same time by multiple nodes](https://github.com/archethic-foundation/archethic-node/issues/420) | Not Done


#### AE Website
Sprint Planned (Highest Priority) | Sprint Summary
------------- | -------------
[Blog's articles section - Change the data source of the summary #111](https://github.com/archethic-foundation/archethic-website/issues/111) | Done
[Create a beautiful page for error 404, etc... #102](https://github.com/archethic-foundation/archethic-website/issues/102) | Done
[Integrate in main page Nodes worldmap emplacement (3D map) #110](https://github.com/archethic-foundation/archethic-website/issues/110) | Done
[Improve visibility of Governance section (pie chart) on mobile version #76](https://github.com/archethic-foundation/archethic-website/issues/76)| Done
[Project architecture - structuration and hidden files #83](https://github.com/archethic-foundation/archethic-website/issues/83)| Not Done
[like in production, synchronize the preprod branch to the preprod environment #99](https://github.com/archethic-foundation/archethic-website/issues/99) | Not Done
[http redirection #103](https://github.com/archethic-foundation/archethic-website/issues/103)| Not Done
[Add medium link #104](https://github.com/archethic-foundation/archethic-website/issues/104) | Not Done


#### AE Keychains and ID Management
Sprint Planned (Highest Priority) | Sprint Summary
------------- | -------------
[Prototyping DID with Python and Libsodium Part 3/3: Implementing DID](https://github.com/archethic-foundation/biometrics/issues/45) | Done
[DID W3C Standard (Part 1/3) : Identifying components of W3C standard in Decentralised Identity](https://github.com/archethic-foundation/biometrics/issues/46) | Not Done


#### AE Wallet

Sprint Planned (Highest Priority) | Sprint Summary
------------- | -------------
[NFT management #235](https://github.com/archethic-foundation/archethic-wallet/issues/235) | Not Done
[Service's keychain : Add all characters in naming #136](https://github.com/archethic-foundation/archethic-wallet/issues/136) | Done
Documentation (Blog Article : Functional and technical presentation) | Done
Documentation (Video update) : script FR/EN | Done

Sprint Planned (Bonus) | Sprint Summary
------------- | -------------
[After import keychain with many accounts, if user would to change account in accountList screen, an error appears #260](https://github.com/archethic-foundation/archethic-wallet/issues/260) | Done
[Token creation doesn't work with service name contained special characters #246](https://github.com/archethic-foundation/archethic-wallet/issues/246) | Done
[Send screens : Symbol currency is not correct #252](https://github.com/archethic-foundation/archethic-wallet/issues/252) | Done
[Chart - wrong chart appears on main screen #250](https://github.com/archethic-foundation/archethic-wallet/issues/250) | Done
[Send a token to yourself. Error message display "UCO" instead of symbol #259](https://github.com/archethic-foundation/archethic-wallet/issues/259) | Done
[Lock Screen - do not reset the number of attempts if users back #153](https://github.com/archethic-foundation/archethic-wallet/issues/153) | Done
[Sometimes OTP with yubikey doesn't work #165](https://github.com/archethic-foundation/archethic-wallet/issues/165) | Done
[Manage balanceFee API errors #215](https://github.com/archethic-foundation/archethic-wallet/issues/215) | Done
[Price chart - Fix the UI issue with the low value of the ordinate #181](https://github.com/archethic-foundation/archethic-wallet/issues/181) | Done
Block the wallet creation process when keychain is not create in the blockchain #158 | Done
[Samsung Smart Suggestion crash when entering text to send UCOs #210](https://github.com/archethic-foundation/archethic-wallet/issues/210) | Done
Wallet not responding when sending UCO to address starting with [1-9] #222 | Done
[Keyboard hides infos or buttons #139](https://github.com/archethic-foundation/archethic-wallet/issues/139)| Not Done

Sprint Planned (Configuration) | Sprint Summary
------------- | -------------
upgrade Android version SDK 33 (closed) | Done
[Removal of the package-based architecture #237](https://github.com/archethic-foundation/archethic-wallet/issues/237) | Done
[Linux - Configuration feature #263](https://github.com/archethic-foundation/archethic-wallet/issues/263) | Not Done
[Check path in xcconfig #148](https://github.com/archethic-foundation/archethic-wallet/issues/148) | Invalid 

Sprint Planned (UI/UX) | Sprint Summary
------------- | -------------
[Flat theme - improve UI #257](https://github.com/archethic-foundation/archethic-wallet/issues/257) | Done
[Manage token symbol in receive notification #241](https://github.com/archethic-foundation/archethic-wallet/issues/241) | Done
[Show/Hide amounts - improve option #254](https://github.com/archethic-foundation/archethic-wallet/issues/254)| Done
When users click on an account in account list screen, go back to the main screen #243 | Done
Token creation screen : Inform the user of the maximum length of a symbol #255 | Done
[Remove parenthesis in balance widgets for the main information #248](https://github.com/archethic-foundation/archethic-wallet/issues/248) | Done
[UI Improvements #258](https://github.com/archethic-foundation/archethic-wallet/issues/258) | Not Done
Archethic Icon doesn't appear in notification for some android devices #245 | Re-opened

Sprint Planned (Features) | Sprint Summary
------------- | -------------
[Add max number of confirmations #238](https://github.com/archethic-foundation/archethic-wallet/issues/238) | Done
[Password - add random password generation #114](https://github.com/archethic-foundation/archethic-wallet/issues/114) | Done
[Import wallet - use autocompletion #157](https://github.com/archethic-foundation/archethic-wallet/issues/157) | Done
Password - add status bars showing whether password is strong, medium, easy : #115 | Done
[Add flat theme #236](https://github.com/archethic-foundation/archethic-wallet/issues/236) | Done
[Price Chart - Add 1h + all chart #180](https://github.com/archethic-foundation/archethic-wallet/issues/180) | Done
Add a possibility to copy balances #221 | Done


### Target (AE Wallet + Website)
- Total Issues completed: 28/33
- Total Story Points completed: 91 pts

### Target (AE Blockchain)
- Total Issues: 12/22
- Total Story Points: 48 pts (this is as of the demo meeting, some more reviews are expected to finish later today)
