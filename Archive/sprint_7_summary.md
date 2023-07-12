# Sprint 7

## Arcalod

> 05-May-22 to 18-May-22

### Goal

#### AE Blockchain:
- Leverage sharded origin keys and expose its API
- Transaction already exists and transaction timeout issues

#### AE Packaging: 
- Auto-updating: Build cycle, pushing the package to the public
- Prerequisite: 50 miners are ready to be shipped

#### AE Biometrics: 
- Use the fingerprint vector/matrix and convert it into 32 Bytes and then keys (priv, public, etc...)
- Finger orientation and its approach and which minutiae to look for (its classification, priority ...)

#### AE Wallet:
- Drafting of the specifications for the redesign (UI/UX) of the wallet via 99Design.

#### AE Website: 
- Further improve the performance of Archethic Website and provide the lighthouse score before/after (performance >75)

### Target
- Total Issues: 15
- Total Story Points: 144

#### Carry Forwards
- Issues carried from last sprint: 2 | Story Points: 13
- Issues carried from last 2 sprints: 3 | Story Points: 55

### Scope

#### AE Blockchain
 - [293 Feature - Get the genesis public_key of the chain](https://github.com/archethic-foundation/archethic-node/issues/293)
 - [40 Feature - Add transaction building from the keychain](https://github.com/archethic-foundation/libjs/issues/40)
 - [47 Feature - Add setOriginSignature to the transaction builder](https://github.com/archethic-foundation/libjs/issues/47)
 - [241 Feature - Implement hybrid root of trust](https://github.com/archethic-foundation/archethic-node/issues/241)
 - [297 Feature - Use pagination state in GraphQL API](https://github.com/archethic-foundation/archethic-node/issues/297)
 - [302 Feature - Improve Github Actions duration](https://github.com/archethic-foundation/archethic-node/issues/302)
 - [272 Bug - Transaction already exists](https://github.com/archethic-foundation/archethic-node/issues/272)
 - [34 Feature - Change the derivation path for wallet](https://github.com/archethic-foundation/archethic-ledger/issues/34)




#### AE Packaging
 - [2 Feature - Implement Erlang hot reload via snap upgrade](https://github.com/archethic-foundation/archethic-snap/issues/2)
 - [26 Feature - Switching to embedded db implementation](https://github.com/archethic-foundation/archethic-snap/issues/26)



#### AE Biometrics
 - [26 Task - Study the improved/more robust fingerprint feature extraction for key generation](https://github.com/archethic-foundation/biometrics/issues/26)
 - [24 Task - Finger print extraction (Part 8/8): ATECC608A Development With Cryptoauthlib - Key Generation With Raw Data and Biometrics](https://github.com/archethic-foundation/biometrics/issues/24)
 - [25 Task - Study the fingerprint Orientation](https://github.com/archethic-foundation/biometrics/issues/25)



#### AE Website
 - [64 Feature - Improve the performance of Archethic Website](https://github.com/archethic-foundation/archethic-website/issues/64)
 - [63 Feature - Improve Archethic Website on the basis of community feedback](https://github.com/archethic-foundation/archethic-website/issues/63)

### Team Availability: 100%

### Target
- Total Issues: 15
- Total Story Points: 144

#### Carry Forwards
- Issues carried from last sprint: 2 | Story Points: 13
- Issues carried from last 2 sprints: 3 | Story Points: 55

### Actual

#### Closed: 18 Issues | 167 Points

#### Not touched (Sprint Backlog): -

#### Pending (WIP): xx Issues | xx Points
- DIP Today: xx issues | xx points
- Blockage / Dependency: - | -
- Review / QA: - issues | - points

### Issues added in-sprint

#### 6 Issues | 47 Points

##### Day 5 - 26 Points: 
- archethic-node: Expose API to get the origin key
- archethic-node: Leverage sharded origin keys

##### Day 7 - 18 Points: 
- biometrics: Finger print extraction (Part 7/8): ATECC608A Development With Cryptoauthlib- Create asymmetric keys with random data
- archethic-snap: Check user-defined ports are available and in range

##### Day 8 - 3 Points:
- archethic-node: Explorer - Error formatting UCO balance
- archethic-foundation: Community Section Update


### Observations
- Issues got broken into smaller chuncks, which helped closures
