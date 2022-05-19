# 1. Introduction

The objective of this specification document is to clearly define this bounty’s deliverables and requirements. 

## 1.1 Concept

### 1.1.1. Value Proposition:

Dash Integration into MetaMask will open new opportunities for Dash Platform using an established and familiar Web3 interface. 

### 1.1.2. Concept Source Link

https://trello.com/c/6XAuy9DW/94-request-new-concept#comment-627be7a69cc69b89293143a8 

## 1.2 Bounty

### 1.2.1. Link to Card:

https://trello.com/c/JTyG2pS0/198-metamask-dash-snap 

## 1.3 Specification

### 1.3.1. Task Description

1) Create initial specification (3 DASH)

# 2. Deliverables

## 2.1. MetaMask Flask / Snap Browser Extension with support for Dash Network

## 2.2. Sample HTML and/or React Site for connecting with MetaMask Browser Extension

# 3. Requirements

## 3.1. Application Functionalities

MetaMask provides a browser extension capable of signing transactions and can be interacted with by a web3-enabled website. Once a connection to a given website has been established, the website can execute wallet functions and prompt the user to sign transactions. 

This application will bring the above functionality to the Dash Network through the use of a “Snap”, a development framework, intended to facilitate adding new networks and functionalities to the extension.

At a minimum, the application should be able to “connect” to a Dash-enabled MetaMask Extension and query basic wallet and network information through JSON-RPC.

If possible, the application should enable communication to Dash Platform using gRPC requests. An ideal outcome would be to enable the utilization of Identities on web3-enabled websites.

## 3.2. User Experience

The user will need to install a specialized version of MetaMask called MetaMask Flask. Within this development version of MetaMask they can then install the Dash Snap to enable access to the Dash Network.

## 3.3. User Interface

The existing MetaMask User Interface will be used.

## 3.4. System and Architecture

This application will be built using the [Snaps Development Guide](https://docs.metamask.io/guide/snaps-development-guide.html#table-of-contents) as a reference.

## 3.5. Infrastructure

This application will require an API connection to the Dash Network.

## 3.6. Performance

N/A

## 3.7. Operational

[How does MetaMask connect to a blockchain network?](https://metamask.zendesk.com/hc/en-us/articles/5378119120667-How-does-MetaMask-connect-to-a-blockchain-network-)

## 3.8. Resource

N/A

## 3.9. Security

[Basic Safety and Security Tips for MetaMask](https://metamask.zendesk.com/hc/en-us/articles/360015489591-Basic-Safety-and-Security-Tips-for-Metamask)

# 4. Tasks

## 4.1. Production Tasks

### 4.1.1. Production Task 1 - Enable support for Dash Network as per Developer’s Guide [7 DASH]

### 4.1.2. Production Task 2 - Enable BIP44 Management of Public Keys for Dash Network [5 DASH]

### 4.1.3. Production Task 3 - Integrate custom JSON-RPC endpoints into extension [5 DASH]

### 4.1.4. Production Task 4 - Integrate custom gRPC endpoints into extension [5 DASH]

### 4.1.5. Production Task 5 - Develop test webpage / React App for demonstration purposes [3 DASH]

## 4.2. QA Tasks

### 4.2.1. QA Task 1 - Verify import / recovery of wallet seed

### 4.2.2. QA Task 2 - Verify ability to sign / broadcast transactions

### 4.2.3 QA Task 3 - Verify ability to reach custom RPC endpoints using web3
