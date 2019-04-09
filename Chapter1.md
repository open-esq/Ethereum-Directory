# Chapter 1: Wallets and Utilities

## 1.1 Introduction

## 1.2 Wallets

### MetaMask

MetaMask is a popular wallet because it allows users to interact with Ethereum's decentralized applications (called "DApps").  It runs a light client within the user's web browser.  It's currently compatible with Chrome, Brave, and Mozilla.

***How to get it.*** The following instructions are from Anton Anonopoulos and Dr. Gavin Wood's seminal book, Mastering Ethereum:

>Open the Google Chrome browser and navigate to https://chrom.google.com/webstore/category/extentions.  Search for “MetaMask” and click on the logo of a fox.  [Make sure the extension is offered by https://metamask.io, that it has over 1,400 reviews, and has more than 1,000,000 users.  This is important to ensure that it’s not a malicious counterfeit.]  Once you confirm you are looking at the correct extension, click “Add to Chrome” to install it.

Once MetaMask is installed you should see a new icon (the head of a fox) in your browser’s toolbar.  Click on it to get started.  You will be asked to accept the terms and conditions and then to create your new Ethereum wallet by entering a password […].

Once you’re set a password, MetaMask will generate a wallet for you and show you a mnemonic backup consisting of 12 English words […].  These words can be used in any compatible wallet to recover access to your funds should something happen to MetaMask on your computer.  You do not need the password for this recovery; the 12 words are sufficient.

You account page shows the name of your account […], an Ethereum address […], and a colorful icon to help you visually distinguish this account from other accounts.  At the top of the account page, you can see which Ethereum network you are currently working on […].


### The Ethereum Foundation's Wallet

The Ethereum Foundation developed its own wallet application, simply called "Ethereum Wallet."  This wallet offers three sync modes, fast, light, and full.

***How to get it.***
The latest version of Ethereum Wallet can be downloaded from https://github.com/ethereum/mist/releases.  Note that the Ethereum Foundation also produced a web3 browser called "Mist", but it has been discontinued.

### My Ether Wallet

My Ether Wallet ("MEW") allows users to generate wallets within their personal web browsers, allowing them to hold their assets and wallet information offline.  This feature safeguards wallets by precenting disclosures to online exchanges.  It also makes the user solely responsible for securiting access information.  Simply put, if you lose your wallet information, you have no one to blame but yourself.

***How to get it.*** Visit MyEtherWallet.com

### Parity

Parity markets itself as "the fasted and most advanced Ethereum client."  Parity, like the Ethereum Foundation's wallet, syncs directly with the Ethereum blockchain; but it's accessible through your web browser.  It also offers an offline wallet for mobile devices called "Parity Signer," and a light wallet called "Parity Feather."  It is written in a newer programming language called "Rust."

***How to get it.*** Visit parity.io/ethereum/

### Coinbase

Coinbase markets itself the following way:

>Coinbase is a secure online platform for buying, selling, transferring, and storing digital currency.  Our mission is to create an open financial system for the world and to be the leading global brand for helping people convert digital currency into and out of their local currency.  We make buying and selling digital currency easy.  Sending or receiving digital currency between online wallets, friends, or merchants on Coinbase is free!  We handle security and backups so you don’t have to worry.  We are a “one stop shop” - we offer a wallet, an exchange, and merchant tools within one simple interface.  Coinbase is a platform on which many applications are being built using our API.

***How to get it.*** Visit coinbase.com

## 1.3 Utilities

### Etherscan

>Etherscan is the leading BlockExplorer for the Ethereum Blockchain.  A BlockExplorer is basically a search engine that allows users to easily lookup, confirm and validate transactions that have taken place on the Ethereum Blockchain.  We are independently operated and developed by a team of individuals who are truly passionate and excited about the kinds of decentralized information and infrastructure applications that Ethereum makes possible.
Etherscan is not a wallet service provider, we do not store your private keys and we have no control over the transactions that take place over the Ethereum network.

https://etherscancom.freshdesk.com/support/solutions/articles/35000022140-what-is-etherscan-

***Where to find it.*** Find it at etherscan.io

### Geth

Geth is a program that serves as a node for the Ethereum blockchain, and via which a user can mine Ether and create software that runs on the EVM – the Ethereum Virtual Machine.

***How to get it.***  Visit https://geth.ethereum.org/downloads/

### Status

Status is a web browsing application for mobile phones that allows users to interact with DApps, similar to MetaMask.  It markets itself in the following way:

>Status is a mobile operating system that will completely change the way the world interacts with the Ethereum network.  Designed as a decentralized browser and private messenger, Status allows you to connect to the entire Ethereum network right in the palm of your hand.

>Operating as a light client node on Ethereum, Status provides you access to all of Ethereum’s decentralized applications (dApps) through an app on your smartphone.  It opens the door to mass adoption of Ethereum dApps by targeting the fastest growing computer segment in the world - smartphone users.
Smartphone users will quickly realize that utilizing Ethereum and its dApps has never been so easy and convenient.

***How to get it.*** Search for it in your iPhone or Android app store, or visit dev.status.im

### uPort

uPort specializes in allowing users to register and confirm their real life idenity on Ethereum.  It markets itself as follows:

>uPort returns ownership of identity to the individual.  uPort’s open identity system allows users to register their own identity on Ethereum, send and request credentials, sign transactions, and securely manage keys & data.
uPort consists of identity and messaging protocols that together form an interoperable identity layer for the decentralized web.

>uPort is building a shared identity web of trust.  Your app can request access to the set of credentials a user has collected from the network.  Users can always choose what to share.
Our modular open-source components, developer tools, and mobile clients help you connect with your users.  We help make it simple to build on Ethereum.”
>…
>An identity is not just based on what others say about them, but also on the things they do.  Their interactions with other people, businesses, and blockchains all form part of who they are and how they choose to represent themselves for future interactions.

>Developers can interact with this data by asking for consent and requesting identity datum.
A uPort identity is built by using verified data.  Every interaction, request, response, and transaction a user performs helps improve the value of their identity.

### Ethereum Name Service

Ethereum Name Service ("ENS") allows Ethereum accounts to be linked to easily identifiable names.  These names are autioned off and registered in a decentralized fashion, and identified with a .eth domain.

[How to get it]
