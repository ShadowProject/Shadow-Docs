---
title: 	Shadow Documentation

language_tabs:
  - cpp
  - shell
  - json


toc_footers:
  - <a href='https://shadowproject.io/'>Shadow Website</a>
  - <a href='https://shadowproject.io/en/gettingstarted'>Download</a>
  - <a href='https://blog.shadowproject.io/'>Blog</a>
  - <a href='https://slack.shadowproject.io/'>Invite Slack</a>
  - <a href='https://shadowproject.slack.com/'>Slack</a>
  - <a href='https://talk.shadowproject.io/'>Forum</a>
  - <a href='http://explorer.shadow.cash/'>Block explorer</a>
  - <a href='https://github.com/shadowproject'>Github</a>
  - <a href='https://github.com/tripit/slate'>Documentation Powered by Slate</a>

search: true
---

# About Shadow
## History
### Bitcoin

Due to their superiority over traditional methods of exchange, virtual currencies are quickly becoming very popular. Prior to Bitcoin, the largest problem for these virtual currencies was the prevention of double spending attacks. In short, a double spend attack is the malicious act of executing multiple transactions using the same units of currency (the equivalent of counterfeiting paper money). Bitcoin was able to solve this major issue by integrating a public ledger of all previous transactions known as a block chain.


Bitcoin relies on a peer-to-peer network (P2P) where each member (peer) of the network has the ability to analyze every transaction ever executed. This method of checks-and-balances allows peers to see if coins have been previously spent before accepting any new transactions, thus limiting double spend attacks.


The public nature of a block chain allows anyone to observe the entire transaction history and holdings of every participant. Unfortunately, while names and personal data aren't revealed in transaction records, a block chain such as Bitcoin’s does not allow for native anonymity or privacy. Addresses can be linked and traced to individuals and businesses by block chain anaylsis.


### Shadow

Born on July 19, 2014, the Shadow Project quickly distinguished itself as an innovative and unique open source project with a mission to create the first truly anonymous and decentralized cryptocurrency built with Bitcoin’s code.
At the time, most cryptocurrencies had traits analogous to traditional bank accounts with transactional protocols similar to credit cards and the only way to privately transact peer-to-peer was through centralized bitcoin mixing services or by learning an entirely different cryptocurrency protocol, Cryptonote.
Besides the privacy developments within cryptonote coins, the anonymity provided by traditional fiat systems (cash) had yet to be fully realized within the cryptocurrency space.


The Shadow Project development team tasked themselves to create just that, a privacy platform built on bitcoin codebase that provided anonymity without the need for a central, middle-man intermediary.
Inspired by the Cypherpunk anonymity movement, Shadow developers began simultaneously integrating emerging privacy technologies & services with security improvements based in zero-knowledge cryptography.
By the time of the project's first birthday, Shadow had evolved from a simple idea of a truly anonymous currency into one of the most advanced cryptocurrency privacy projects to date.


## Mission Statement

```On December 10, 1948, the General Assembly of the United Nations adopted and proclaimed the Universal Declaration of Human Rights. Article 12 states, “No one shall be subjected to arbitrary interference with his privacy, family, home or correspondence, nor to attacks upon his honour and reputation. Everyone has the right to the protection of the law against such interference or attacks”. ```
Privacy is inherently entangled with power. Privacy provides a protected space to express and think for one's self freely. An individual stripped of their privacy is a powerless individual.


Our society is increasingly becoming more comfortable with surveillance, while in reality it's a battle of power, a battle that people are losing everyday. While we are told collection of personal data is for the good of the nation, it is being abused without accountability. Elected officials are accountable to the people, not the (current) other way around. Solutions to problems take a back seat when limitless money is being thrown at solving problems.


We live in a world where comfort is priority. We don't like waiting or doing extra work to protect our privacy. Governments have figured this out long ago and will continue to look the other way while holding out their hands until the people with the power (citizens) decide enough is enough.


Many open source privacy projects are tackling big problems that start to protect users, however these solutions are often uncomfortable to work with. They sometimes require many different procedures and are prone to failure simply by human error. In order for adoption of privacy tools to happen on a large scale the learning curve needs to shrink considerably and intuitive design needs to make use of applications clear, concise and enjoyable.



The Shadow Project is on a mission to solve this. The focus of our privacy platform is to use cutting edge cryptography to encrypt and anonymize user data with every tool we release. We are creating applications with a streamlined procedure that provides  privacy and anonymity without the cost of comfort.



Nearly 67 years later, we believe this declaration to be more important than ever. To help protect this most basic right to privacy, The Shadow Project is building an encrypted, digital ecosystem. Cryptographic innovations will catalyze the evolution of communication, commerce, and currency. Shadow’s mission is to remain at the forefront of this evolution with it’s decentralized privacy platform, made available to all operating systems.

## Other cryptocurrency projects
### Network architecture

<span class="shadow-table"></span>

|                      |   SHADOW   |   MONERO   |    DASH    |  DARKNOTE  |  BITCOIN  |  ZCASH  |
| -------------------- | ---------- | -----------| ---------- | ---------- | ---------- | ---------- |
| **Proof-of-Work**    |    false    |    true    |    true    |    true    |    true    |    true    |
| **Proof-of-Stake**   |    true    |    false    |    false    |    progress    |    false    |    false    |
| **Bitcoin Based**    |    true    |    false    |    true    |    false    |    true    |    true    |
| **CryptoNote Based** |    false    |    true    |    false    |    true    |    false    |    false    |

### Anonymity features

<span class="shadow-table"></span>

|                      |   SHADOW   |   MONERO   |    DASH    |  DARKNOTE  |  BITCOIN  |  ZCASH  |
| -------------------- | ---------- | -----------| ---------- | ---------- | ---------- | ---------- |
| **Mixing**    |    false    |    false    |    true    |    false    |    false    |    false    |
| **Stealth Addresses**   |    true    |    true    |    false    |    true    |    false    |    true    |
| **Ring Signatures**   |    true    |    true    |    false    |    true    |    false    |    true    |
| **Zero Knowledge Proofs**   |    true    |    true    |    false    |    true    |    false    |    true    |
| **Untraceable**    |    true    |    true    |    undefined    |    true    |    false    |    undefined    |
| **Unlinkable**    |    true    |    true    |    false    |    true    |    false    |    undefined    |
| **End to end Anon** |    true    |    true    |    false    |    true    |    false    |    undefined    |

### Wallet features

<span class="shadow-table"></span>

|                      |   SHADOW   |   MONERO   |    DASH    |  DARKNOTE  |  BITCOIN  |  ZCASH  |
| -------------------- | ---------- | -----------| ---------- | ---------- | ---------- | ---------- |
| **GUI Wallet**    |    true    |    false    |    true    |    true    |    true    |    progress    |
| **HTML Interface**   |    true    |    false    |    false    |    false    |    false    |    false    |
| **Lite Wallet**    |    true    |    false    |    false    |    true    |    false    |    false    |
| **HD Wallet**    |    true    |    false    |    false    |    false    |    true    |    undefined    |
| **Multisignatures** |    progress    |    false    |    false    |    false    |    true    |    undefined    |

- GUI: General User Interface
- HD: Hierarchical Deterministic

### Other Features

<span class="shadow-table"></span>

|                      |   SHADOW   |   MONERO   |    DASH    |  DARKNOTE  |  BITCOIN  |  ZCASH  |
| -------------------- | ---------- | -----------| ---------- | ---------- | ---------- | ---------- |
| **Web Wallet**    |    false    |    true    |    false    |    false    |    false    |    false    |
| **Fast Transactions**   |    false    |    false    |    true    |    false    |    false    |    false    |
| **Incentive Nodes**   |    false    |    false    |    true    |    false    |    false    |    false    |

### Blockchain Decentralized Apps

<span class="shadow-table"></span>

|                      |   SHADOW   |   MONERO   |    DASH    |  DARKNOTE  |  BITCOIN  |  ZCASH  |
| -------------------- | ---------- | -----------| ---------- | ---------- | ---------- | ---------- |
| **Encrypted Chat**    |    true    |    false    |    false    |    true    |    false    |    false    |
| **MarketPlace**   |    progress    |    false    |    false    |    false    |    false    |    false    |

# Community

Shadow has an awesome community, ranging from privacy activists to technical and financial experts.
The biggest part of the community resides in #general on Slack, great times assured.

[shadowproject.io](https://shadowproject.io) is dedicated to help Shadow’s community develop in a sustainable way. The website is registered and managed by community members, with the input of Shadow developers. Aboutshadow.com is not a foundation. Foundations imply centralization or a controlling body. All Shadow holders are equal and all have a say in the direction the project is heading. Just like nobody owns the email technology, nobody owns the Shadow network. As such, aboutshadow.com does not speak with authority in the name of the Shadow project.

## Social Media

Below you will find a list of places where you can find other Shadow users, community members and news.

- IRC: freenode.net #shadowcash
- Blog: [blog.shadowproject.io](https://www.blog.shadowproject.io)
- Forum: [talk.shadowproject.io](https://www.talk.shadowproject.io)
- Slack: [shadowproject.slack.com](https://shadowproject.slack.com/)
- Reddit: [reddit.com/r/Shadowcash](https://www.reddit.com/r/Shadowcash)
- Twitter: [twitter.com/allaboutshadow](https://www.twitter.com/allaboutshadow)

- Slack Invite: [shadowproject.herokuapp.com](https://shadowproject.herokuapp.com/)

# Currency

## Specification

Specification | Value
--- | ---
Protocol | **PoSv3**
Block Time | **60 seconds**
Difficulty Re-target | **every block**
Nominal Stake Interest | **2% annually**
Min Stake Age | **8 hours** (no max age)
P2P Port | 51737
RPC Port | 51736

### Transactions

| Specification   | Value          |
| --------------- | -------------- |
| Min Fee         | **0.0001 SDC** |
| Confirmations   | **10**         |
| Maturity        | **500**        |

## Exchanges

Currently you can only buy ShadowCash (SDC) once you have Bitcoin (BTC). Bitcoin can be bought at a number of places [link needed](). Once you have BTC you can buy SDC on a number of crypto-to-crypto currency exchanges.

ShadowCash is available at these exchanges:

- [BITTREX](https://bittrex.com/Market/Index?MarketName=BTC-SDC)
- [POLONIEX](https://poloniex.com/exchange#btc_sdc)

You can also instantly pay for purchases with ShadowCash anywhere Bitcoin is accepted with:

- [SHAPESHIFT](https://shapeshift.io/)
- [PURSE](https://purse.io/)

## Network Consensus

### Proof of Work (PoW) - Complete
Specification | Value
--- | ---
Algo | Scrypt
Max Height | 31000 (after this network will not accept PoW blocks)
SDC Circulation |  ~6,400,000 SDC
Length | two weeks of PoW

### Proof of Stake (PoS) - Ongoing
Specification | Value
--- | ---
Algo | Sha256 (formerly Scrypt)
Nominal Stake Interest | 2% annually

### Multipool
PoW mining has ended, but you can still use your mining rigs to earn ShadowCash by using the [SDC Multipool](https://www.shadowpool.info/). Point your rigs and enter your SDC payout address to begin!

# ShadowCore

## Introduction

ShadowCore is the main engine on which all decentralized actions take place, it is used when referencing to the back end of the program and takes cares of the network bootstrapping and propogation of data throughout it. It is also in charge of synchronising and verifying the blockchain for each node to make sure it can participate in the network.

The data being propogated are encrypted messages and transactions, you can find more information about the workings of these in other sections of this documentation. 

## HTML  (GUI)

Shadow has a HTML cryptobrowser at the core of its graphical user interface (GUI). One thing you may have noticed is that we strive for the best user experience (UX) and that involves a good graphical interface. We chose to use a combination of HTML and Javascript because this allows web designers and developers to help the project. They are very familiair with creating a good user experience through a simple yet beautiful interface.

![Overview](https://cdn-images-1.medium.com/max/1400/0*z-K8SYQqwpRRo6yg.jpg)

![Wallet](https://cdn-images-1.medium.com/max/1400/0*xo9jG8LJvsHi7yWS.jpg)

## Hierarchical Deterministic Wallet (HD)

The [Hierarchical Deterministic](https://bitcoin.org/en/glossary/hd-protocol) (HD) key creation and transfer protocol ([BIP32](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki)), allows users to create [child keys](https://bitcoin.org/en/glossary/child-key) from [parent keys](https://bitcoin.org/en/glossary/parent-key) in a hierarchy.
In essence this means that you only have to back up your wallet once, all private keys are derived from the mnenomic seed (up to 24 words) and they can be retrieved anytime if you have the seed. This means that you'll never have to worry about backups as long as you have one, coins will never be lost.

### Upgrading to a HD wallet
If you're still **on the 1.3.3.2** release and you want to the latest version of Shadow then you should use the following guidelines. 
All wallets **after 1.3.3.2** come will automatically generate a HD wallet, these wallets however do not come with a mnemonic seed (24 words). A back up made of this wallet will automatically restore all private keys, so your coins are always safe.
If you want you can specify a mnenomic seed if you want to make use of the feature, but we've kept this as an option.

<aside class="warning">
ALWAYS BACKUP WALLET.DAT FIRST
</aside>
 
**STEP 1**

1. Save your wallet.dat and rename it.
2. Load the new Shadow Latest client
3. Create a new HD Wallet (Options --> Key Management --> New Key) - give it a "name".
4. Goto (Key Management --> Advanced Management) and make sure that the new "name" account is showing as "default".
5. The wallet will have pre-generated a Default normal and stealth address
6. Send some funds to test (from your old wallet)

So now I would suggest you try a restore of this account to test it!

**STEP 2**

1. Save your wallet.dat and rename it. 
2. Load the Shadow Latest Client 
3. Goto (Options --> Key Management --> Restore) - complete steps 
4. Goto (Help --> Debug --> Console) and type scanforalltxns 590000 
5. You should see your test transaction show up. 


To create a better user experience ShadowCore implemented [BIP39](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki), allowing users to create a HD wallet based on a mnenomic sentence consisting of 24 words and the ability to secure that with a password for plausible deniability.

### Links

- [HD Protocol](https://bitcoin.org/en/developer-guide#term-hd-protocol) — Bitcoin.org Developer Guide
- [BIP32: hierarchical deterministic wallets](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki) — Bitcoin Improvement Proposals
- [Deterministic wallet](https://en.bitcoin.it/wiki/Deterministic_Wallet) — Bitcoin Wiki
 


# Download

## Desktop Wallet
- Latest [Windows x32](http://shadow.cash/downloads/latest/windows32) wallet download
- Latest [Windows x64](http://shadow.cash/downloads/latest/windows64) wallet download
- Latest [Linux x32](http://shadow.cash/downloads/latest/linux32) wallet download
- Latest [Linux x64](http://shadow.cash/downloads/latest/linux64) wallet download
- Latest [OSX](http://shadow.cash/downloads/latest/macosx) wallet download



## Useful Paths
```
Windows
```
>%appdata%\ShadowCoin

```
OSX
```
>~/Library/Application Support/ShadowCoin/

```
Linux
```
>~/.shadowcoin/

<aside class="warning">Warning: deleting the wallet.dat file in this directory will cause you to lose all of your coins if you have no back up.</aside>
These are the paths where your **blockchain data, wallet and pretty much everything related to Shadow** is stored. 

When using the blockchain.zip method these are the location where you extract the blockchain.zip file.

## Bootstrap?

<aside class="notice">Use this method to synchronize your node within 10 minutes!</aside>

When you load the Shadow Wallet for the first time it connects to the peer-to-peer network and starts to synchronise the block chain. **By default the client will configure a full node.** A full node needs an up-to-date, full copy of the ShadowCash block chain on your computer to properly function. 

A full node is very useful for the following reasons:

1. Looking to help further strengthen the network by providing a full peer/node.
2. Already own ShadowCash (SDC) and wish to participate in staking.
3. Plan to run services on the Shadow network that require a full node.


- Refer to "ShadowLite" section if none of the above apply to you but you want a fast-syncing initial startup.

If you decide that a full node is for you then the full sync of the block chain can take quite a while; sometimes up to 24 hours depending on your hardware. To speed this up the team provides compressed backups of the blockchain in a "bootstrap" file. Adding the current bootstrap to your local directory speeds up the syncronization process which will get your wallet up and running much quicker than the default method.

1. Close the Shadow Wallet and [download the latest Blockchain file from GitHub](https://github.com/ShadowProject/blockchain/)
2. Place the ```blockchain.zip``` file in one of the locations as seen above, depending on your operating system
3. Unzip the ```blockchain.zip``` file
4. Start the ShadowCash Wallet again (The client might be unresponsive but don't worry - it's just loading all the blockchain data)

## ShadowLite

ShadowLite is an innovative component of the Shadow platform that brings lightning-fast syncing with the Shadow blockchain.

We've taken a completely different approach to wallet design based on the principles of the "Simplified Payment Verification" or “SPV” system outlined in section 8 of [Satoshi’s white paper](https://bitcoin.org/bitcoin.pdf). Instead of releasing a separate client, we’ve integrated optional lite functionality within the wallet. This allows for startup configuration to determine which mode you are running (thin or full).

ShadowLite mobile users have access to all existing functionality with a reduced bandwidth, storage and memory footprint.

Staking within the Lite wallet has been removed because staking is a reward function for securing the network. Lite wallets, by nature, do not secure the network.

### Instructions

There are two ways to start the wallet in Lite mode, both are described in this section.

#### Method 1:

The first method changes the ```shadowcoin.conf``` and will cause the wallet to permanently boot up in lite mode for as long as it is in the configuration file.

```
For those of you who wish to enable the lite wallet, open your shadowcoin.conf configuration file with a text editor such as nano
```
>nano shadowcoin.conf

```
And add the following line
```
>thinmode=1

#### Method 2:

The second method will boot up an instance in Lite mode, not permanent. In case you always want to boot up in Lite mode we suggest the first method, but if need to make a transaction quickly without having to download the whole blockchain you can start the daemon with the ```-thinmode``` parameter.

```
Alternatively, you can startup the client with the parameter -thinmode. (no graphical interface)
```
>shadowcoind -thinmode

```
Or if you need a graphical interface.
```
> ./shadow -thinmode

# Compiling from source

## Linux

The Linux Wallet comes in two variations:

- **Daemon**
  - Run the "shadowcoind" executable from the linux download to start the Shadow daemon
- **QT GUI Wallet**
  - Run the "shadow" executable from the linux download to run the Shadow QT Wallet

**Warning : never use root to start the QT or daemon!**

## Source Code

ShadowCash its source code is open-source and available at our [GitHub repository](https://github.com/SDCDev/shadow)

## Linux Daemon from Source (shadowcoind)
```
Update and Install dependencies:
```
>sudo apt-get update && apt-get upgrade
>sudo apt-get install git build-essential libssl-dev libdb-dev libdb++-dev libboost-all-dev libqrencode-dev

```
 Download the source code and compile shadowcoind
```
>git clone https://github.com/ShadowProject/shadow
>cd shadow/src
>make -f makefile.unix
>strip shadowcoind

```
Run the daemon
```
>shadowcoind -daemon

```
 On the inital start-up shadowcoind will return an error because it cannot find the configuration file shadowcoin.conf
```
>nano ~/.shadow/shadowcoin.conf

```
Add the following to your config file, changing the username and password to something secure:
```
>daemon=1
>rpcuser=[secure username]
>rpcpassword=[secure password]

```
You can copy the username and password provided in the earlier error message as the username and password is randomly generated and secure

 You can now start the shadowcoind daemon once more
```
>shadowcoind

```
List all commands for shadowcoind
```
>shadowcoind help

```
Update shadowcoind
```
>git pull

```
Stopping shadowcoind
```
>shadowcoind stop


If you wish you can also compile directly from source, follow these instructions to compile latest ShadowCore headless daemon based on Debian/Ubuntu. Please also refer to the build instructions for more detailed information.*

## Graphical Linux Wallet from Source (Shadow Qt)

```
 Update and Install dependencies
```
>sudo apt-get update && apt-get upgrade
>sudo apt-get install git qt5-default qt5-qmake qtbase5-dev-tools qttools5-dev-tools build-essential libboost-dev libboost-system-dev libboost-filesystem-dev libboost-program-options-dev libboost-thread-dev libssl-dev libdb++-dev libminiupnpc-dev libqt5webkit5-dev

```
 Download the source code and compile shadow QT
```
>git clone https://github.com/ShadowProject/shadow
>cd shadow
>qmake
>make

```
Run the executable found within the shadowcoin folder with :
```
>./shadow


* Advanced users only.
If you wish to you can also compile directly from source, follow these instructions to compile latest Shadow QT GUI Wallet based on Debian/Ubuntu. Please also refer to the build instructions for more detailed information.*

```
Update shadow QT
```
>git pull



# ShadowSend v2.0


## Introduction

The ShadowSend protocol uses dual-key stealth addresses, traceable ring signatures layered with non-interactive zero knowledge proofs to create anonymous cryptographic transactions.

Below you will find a presentation of the anonymous cryptographic transaction protocol which utilizes the above mentioned cryptographic principles. We explain how Shadow introduces a much higher level of privacy and anonymity to the network while still preserving the core principles of trustless decentralization, unforgeability and double-spend prevention. We also present performance data of our scheme including proof sizes, signature generation times and verification times in our [white paper](http://shadow.cash/downloads/shadowcash-anon.pdf).

A detailed diagram is available [here](https://i.imgur.com/2XTQhYF.jpg).

<central><iframe src="//www.slideshare.net/slideshow/embed_code/43827434" width="960" height="600" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen></iframe></center>


## ShadowTokens (SDT)


In order to transact anonymously, we have introduced ```an anonymous token```, which we will refer to as Shadow. Shadow can be minted, destroying SDC (ShadowCash) in the process, and outputting a group of Shadow tokens totalling the same value (minus the transaction fee) of the destroyed SDC.
Shadow Tokens take form of outputs on the ShadowCash blockchain and each one of them has its own private and public key.

SDT is only spendable by providing a ```traceable ring signature``` to prove ownership of a token of the same value.

Once a Shadow Token is created, we can claim a different output in pool of the same value, by providing a traceable ring signature. We provide a keyImage of the private key to prevent double spending.

To increase the pool of outputs available for ring signatures, the SDC value is broken up into separate Shadow Tokens for each decimal place of the total value. The tokens are further broken up into values of 1, 3, 4 and 5. For example 1.7 SDC would become 3 tokens of values 1.0, 0.3 and 0.4.

- For clarity: ShadowCash (SDC) is the native *public* token, ShadowTokens - aka Shadow - is the *private* token.

## Dual-key Stealth Addresses
### Introduction, History and Acknowlegements

Dual-key stealth addresses is one of the cornerstones of most anonymous cryptocurrencies currently available. The usage allows the recipient to remain anonymous, even after sharing his stealth address publicly.

Once the stealth address has been revealed to the payer(s), it will enable the payee to receive infinite unlinkable payments.

**That means that each payment to a Stealth address computes a new unused normal address into which the funds will be received. Any eavesdropper will be unable to link the two addresses.**

The original visionaries were the creators of Bytecoin, for whom we are thankful. Their technical documentation link has been included in the references *[1]*.

- The information they provide may not always apply to Shadow.
- Bytecoin is built on Cryptonote codebase.

We would also like to thank **Peter Todd**. Peter figured out how to implement stealth addresses into Bitcoin. You can find a link to his white paper in the references *[2]*.
He is a Bitcoin core developer and has done amazing work on Bitcoin and deserves the mention.

Peter is also associated with DarkWallet, whose wiki provided lots of information on the working of stealth addresses. Again, the link can be found in the references *[3]*.

The documentation at *sx* can also be very helpful to understand the concept of stealth addresses. They also provide tools that explain how they work. *[4]*.


### Address Encoding
```cpp
//formatting function of stealth address
std::string CEKAStealthKey::ToStealthAddress() const
{
    // - return base58 encoded public stealth address
    
    std::vector<uint8_t> raw;
    raw = Params().Base58Prefix(CChainParams::STEALTH_ADDRESS);
    
    raw.push_back(nFlags);
    raw.insert(raw.end(), pkScan.begin(), pkScan.end());
    raw.push_back(1); // number of spend pubkeys is 1
    raw.insert(raw.end(), pkSpend.begin(), pkSpend.end());
    raw.push_back(0); // number of signatures
    raw.push_back(0); // ?
    AppendChecksum(raw);
    
    return EncodeBase58(raw);
}; //extkey.cpp
```

Stealth addresses are generated in a different way than normal bitcoin addresses, but they have a similair structure.
A dual-key stealth address contains a lot more information than a normal Bitcoin address because it requires the sender of a transaction to know the public scan key and the public spend key **which is not stored on the blockchain**.
All data required to perform such transaction is derivable from the stealth address itself.
 
 ![available languages](images/cpp.png)
 
Just like a Bitcoin address, all data below is **Base-58** encoded, which also explains the familiar looking form.


Version | Options | Public Scan Key | # Public Spend Keys | Public Spend Key | # of signatures | Length of prefix | Prefix | Checksum
--- | --- |--- | --- |--- | --- |--- | --- | ---
0x28 | 0  | 33 bytes | 1 | 33 bytes | 0 | 0 | (not used) |  4 bytes

Parameter | value
--- | ---
**Version:**  | The hexadecimal representation (= 0x28) of '40' is used for the current release on the mainnet. The version field to keep track of updates of the protocol.
**Options:** | Field is always set to 0.
**Public scan key:** | This fields holds the public scan key, 33 bytes of data.
**Amount of public spend keys:** | The current protocol uses one public spend key for each Stealth address. The ability to specify multiple spend keys remains in the protocol because it is useful for the implementation of multi-signature addresses.
**Public spend keys:** | This fields holds the public spend key, 33 bytes of data.
**Amount of signatures:** | Field is always set to 0.
**Length of prefix:** | Field is always set to 0.
**Prefix:** | No prefix is used, since length is equal to zero. Other coins do make use of this field, more information can be found [here](https://wiki.unsystem.net/en/index.php/DarkWallet/Stealth#Computing_prefixes)
**Checksum:** | Contains the first 4 bytes of the SHA-256 hash provided by the operation: SHA256(SHA256(previous_data_concatenated)). The same checksum function used in Bitcoin addresses.

### Address Computation and Transaction Format
```

Alice (receiver)
publicSpendKeyAlice = public spend key
privateSpendKeyAlice = private spend key

publicScanKeyAlice = EC point, 33 bytes
privateScanKeyAlice = integer, 32 bytes

This is where it gets a bit more complicated, but no magic, just math!
G = Generator, the primitive root

To continue on, we have to understand how the public addresses are generated.
A public key is the private key multiplied by the primitive root G.

publicSpendKeyAlice = privateSpendKeyAlice * G
publicScanKeyAlice = privateScanKeyAlice * G

Bob (sender)
e = ephem secret key = ephem private key
publicEphemKey = e * G
Knows the public scan key of Alice (publicScanKeyAlice)!

Ephem is short for ephemeral, which means “short lived”. The ephem secret and public key are only used once and change on every stealth transaction.

Bob now publishes the public ephem key (publicEphemKey) to the receiver Alice.

Because of the diffie-hellman algorithm ONLY THE RECEIVER AND SENDER can deduct the shared secret from the public ephem key.

SharedSecret = SHA256(ephem private key  * publicScanKeyAlice) (Formula for Sender)
SharedSecret = SHA256(privateScanKeyAlice * publicEphemKey) (Formula for Receiver)

Bob can now generate the public key to where it should send the coins.
publicKeyToPay = publicSpendKeyAlice + SharedSecret * G

Alice has two different ways of find out the the public key where the coins will go to.
When the wallet is encrypted:
publicKeyToPay = publicSpendKeyAlice + SharedSecret * G

When the wallet is decrypted:
publicKeyToPay = (privateSpendKeyAlice + SharedSecret)* G
```

If Alice would post a normal address publicly, anyone can explore the blockchain and see the transactions that belong to her. Stealth addresses solve this privacy issue. Alice can post her Stealth address publicly, and nobody will be any wiser of what transactions belong to her.

**It's extremely important to note that the payer derives a new NORMAL address from the Stealth address, to which the funds will be sent and in that process only allowing the payee to compute the corresponding private key.**

It uses a clever mathematical principle called the "Diffie-Hellman Key Exchange", which allows two entities to generate a shared secret based on their keypairs. An eavesdropper is unable to compute the shared secret, enabling private communication between the two. In the case an eavesdropper has full control over one of the keypairs (private and public key) then privacy is obviously broken.

It is important to mention that we can not use the ```SharedSecret``` directly to generate the keypair, because that would also allow the sender control over the private key. Instead a bit of mathematical "magic" (BIP32-style derivation) is applied: the ```SharedSecret``` is added to ```PrivateKeyAlice``` and we use that to generate the new keypair.

It uses a system of dual-keys to allow the wallet software to scan for stealth payments (using ```ScanKeyAlice```) but not make any transactions, because that would require decryption of the wallet/stealth key.
All transactions have to be made with the ```SpendKey```, only available after decrypting your wallet.
The dual-key is more of a security practice, it allows a wallet (while encrypted) to scan for transactions. If it weren't implemented, the wallet would have to remain decrypted, rendering the protection provided by the encryption useless.

The payee has to know the ephem public key to compute the ```SharedSecret```, but how is that data transferred from payer to payee? The ephem public key is embedded in the *stealth metadata*.

Any stealth transaction will require at least 2 outputs, the stealth metadata and the actual spendable output.

Each spendable output in a stealth transaction will be preceded by the metadata for that output. Regular spends do not need metadata, because there is no use of ephem keys in normal transactions.

Format goes as following:

Output | Content
--- | ---
out #1 | **metadata for spend A**
out #2 | **stealth spend A**
out #3 | metadata for spend B
out #4 | stealth spend B
out #5 | *regular spend C*
out #6 | metadata for spend D
out #7 | stealth spend D


### References
[1] ByteCoin, *Technical Documentation*, 2015, Available at [https://bytecoin.org/documentation/](https://bytecoin.org/documentation/

[2] Peter Todd, *[Bitcoin-development] Stealth Addresses*, 2014,  Available at  [https://sourceforge.net/p/bitcoin/mailman/message/31813471/](https://sourceforge.net/p/bitcoin/mailman/message/31813471/)

[3] Dark Wallet, *Stealth*, 2015,  Available at [https://wiki.unsystem.net/en/index.php/DarkWallet/Stealth](https://wiki.unsystem.net/en/index.php/DarkWallet/Stealth)

[4] Sx, *Stealth*, 2015,  Available at [https://sx.dyne.org/stealth.html](https://sx.dyne.org/stealth.html)


## Ring signatures
The ring signatures are a crucial part to anonymize the sender of a transaction.

As previously mentioned, all tokens have their own public and private key. It consists of the public key of the token being spent, plus the public keys from 3 to 200 other tokens of the same value as the token being spent. The nature of ring signatures makes it impossible to discover member of the coins in the ring signature is being spent, and transactions are no longer traceable.

[](http://www.texpaste.com/n/xaypn9ni)

<aside class="notice">TO COMPLETE</aside>

### Double Spend Prevention

The ring signature tags (keyImage) of the spent Shadow tokens are embedded in the transaction to prevent double spends. Each tag is unique to the Shadow token, regardless of the other members of the ring signature.

When a new transaction contains a keyImage that has already been used, and thus is present in the blockchain, the new transaction will be rejected by the network.

## Spending Shadow Tokens

There are two ways in which Shadow tokens (SDT) can be spent:

1. SDT can be sent as SDT.

* When sent as Shadow tokens, new tokens are minted for the recipient to the value of the input Shadow minus the transaction fee.*

2. SDT can be redeemed as SDC.

* When redeemed as SDC, new SDC is created to the value of the input Shadow minus the transaction fee.*

In both cases the input tokens become unspendable. The transaction fee for spending Shadow tokens is 100x greater than the fee for standard transactions. This is to cover the cost of the extra activity required by the network to transmit, verify and store shadow transactions, which are larger and require more processing than standard transactions.

In order to spend Shadow, we use ring signatures to sign the transaction. Our scheme consists of three functions, ```generateRingSignature```, ```generateKeyImage```, ```verifyRingSignature```.

For efficiency’s sake, when spending Shadow, we get a list of all anonymous outputs in the system, then we remove coins that don't have enough same value outputs in the system, then we choose the smallest coin or least number of smallest coins that can cover the amount + transaction fee.

Each ShadowToken consist of a unique private key and public key, so what happens when you spend your ShadowToken? When doing a **normal** transaction (like in Bitcoin), you would prove you received an amount of coins by pointing to the transaction that got you the coins in the first place. That's signed with the private to prove you hold the keys to the address. Now for an **anonymous** transaction that procedure is different: we do not point to previous transactions. Rather we take a pool of coins (public keys of other people their coins) that have the same value as the coin we're trying to spend and then we drop our public key. We then say "we own one of the public keys in this pool of coins", or in cryptographical terms: a ring signature. 

## White Paper


Our white paper on ShadowSend 2 can be found [here](https://github.com/shadowproject/whitepapers/blob/master/shadowcash_anon.pdf).



# Encrypted Messaging
## Introduction

Communication is an essential component of doing business. Modern technology gives us cheap, reliable and effortless methods to communicate with others regardless of physical distance.

However, this technology does little to safeguard the content of our messages from the scrutiny of interested observers. We live in an age of constant and ubiquitous surveillance, where it becomes more difficult by the day to retain our privacy. Privacy is paramount when conducting business, the consequences of invasions of privacy can be devastating to both businesses and individuals, whether the attacker is a rival firm, a malicious individual or an overbearing government.

ShadowChat is a P2P (peer-to-peer) Instant Messaging system utilizing  state-of-the-art encryption technology to keep your communications private. All messages are encrypted by the proven **AES-256-CBC algorithm**, and distributed between nodes in such a way as to prevent the recipients of messages from being inferred by assailants utilizing  sophisticated traffic analysis, even if the assailants can view the entire network and/or run nodes of the network.

To eliminate the risk and hassle of sharing passwords, we utilize the proven and trusted method of **Elliptic Curve Diffie-Hellman (ECDH) key exchange**. The Elliptic Curve Digital Signature Algorithm (ECDSA) is used to give you confidence that the messages you received came from the original recipient and remained untouched in propagation. Messages are distributed over the preexisting Shadow P2P network, and a copy of each encrypted message is stored on each node for a period of 48 hours.

## Key Sharing

The Elliptic Curve Diffie-Hellman (ECDH) key exchange method allows a secret key for encryption to be shared between the sender and recipient using the data embedded in the message along with the private keys of ShadowCash addresses held by the sender and recipient.

This allows for distributing messages, of whom nobody knows the recipient of.

In order to send an encrypted message, you must possess the public key of the intended recipient. The public keys embedded in the ShadowCash transaction blockchain when any amount is spent. If you are sending to an address that has not spent a transaction in the blockchain, the public key to that address must be provided manually.

ShadowCash uses curve secp256k1 for all elliptic curve functions. This is the same curve used by bitcoin along with the vast majority of altcoins. With such widespread use underpinning systems of immense value it is extremely unlikely that curve secp256k1 is not secure.

Messages are signed by the keys they were sent with, this allows you to be confident of the origin of the messages you receive and also allows the public key of the sender to be extracted from the message, providing you all the information needed to send a reply.

## Encryption

**Detailed Procedure**

- Get public key *K* from destination address
  - Find in database created from scanning for public keys in the blockchain and user additions.
- Generate 16 random bytes using a secure random number generator. Call them *IV*. Generate a new random EC key pair with private key called *r* and public key called *R*.
- Generate shared secret key *P* using public key *K* and private key *r*.
  - Elliptic Curve Diffie-Hellman
- Use the shared secret key *P* and calculate the SHA512 hash *H*.
  - ECDH_compute_key of OpenSSL
  - Call the first 32 bytes of *H key_e* and the last 32 bytes *key_m*.
- Calculate a 32 byte MAC with HMACSHA256, using *key_m* as salt and (timestamp + destination + cipher text).
  - Message authentication code used
  - By also checking time-stamp and destination, recipients can be certain that these fields have not been tampered with.
- Generate a compact signature from the message data and sender's address.
  - Only if not sending anonymously
  - Recipient can verify that the message came from the sender
  - Also allows the public key to be reconstructed (useful to reply)
- Include address and compact signature in the payload to be encrypted.
- Compress the plain-text message with lz4 if the message is larger than 128 bytes.
- Encrypt the payload data with AES-256-CBC, using *IV* as initialization vector, *key_e* as encryption key.

## Message Propagation

Encrypted Messages are duplicated on every participating node in the ShadowCash network – this prevents adversaries form uncovering the recipient of an encrypted message by using network traffic analysis.

The messages are stored on each node for a maximum period of 48 hours, after which the message is deleted. If the recipient is absent from the network for 48 hours or more the possibility exists that they may not receive messages sent to them. It is recommended to connect to the network each day in order to prevent such an occurrence.

Stored messages are grouped by time in divisions of 1 hour. The system operates on the grouped buckets of messages to save bandwidth.

![Synchronization of buckets between peer nodes](images/shadowchat-message_propagation.png)

## Decryption

For each incoming message a node will attempt to decode the message with every owned address contained in the nodes white-list of addresses to receive messages on.

To speed up the process and allow for any payload format to be used, the Message Authentication Code (MAC) is calculated for the generated shared secret key, if it does not match the MAC provided in the message, decryption will fail and the function ends.

**Detailed Procedure**

- Get *IV* and *R* from the message block
- Get the private key *k* of the recipient used to decrypt.
- Generate shared secret key *P* using with private key *k* and public key *R*.
  - Elliptic Curve Diffie-Hellman
- Use the shared secret key *P* to generate the SHA512 hash *H*.
  - Call the first 32 bytes of *H key_e* and the last 32 bytes *key_m*.
- Calculate MAC' with HMACSHA256, using *key_m* as salt and hash of (time-stamp + destination + cipher text).
- Compare MAC with MAC'.
  - Return if not equal, decryption will fail.
- Decrypt the encrypted payload with AES-256-CBC, using *IV* as initialization vector, *key_e* as decryption key.
- Decompress message portion with lz4 if message is larger than 128 bytes.
- If address and compact signature were included then verify the message
Address and compact signature are not included when message is sent anonymously strip the sender's public key and add it to the public key database.

## White Paper

White paper: [View on github](https://github.com/shadowproject/whitepapers/blob/master/shadowcash_em.pdf)



# ShadowMarket
![ShadowMarket](https://i.imgur.com/A4TETRM.jpg)
## Decentralized Marketplace
The main component of the Shadow platform is the **decentralized marketplace** dubbed 'ShadowMarket'. The decentralized nature of the network makes it very resilient against shutdown attempts and permits for anyone to participate in a true free market without the possibility of interference or eavesdropping by malicious parties. Every node in the network distributes and stores all the open market listings, to prevent bloating the network with outdated and incorrect listings, each one must contain an expiration date and the approriate listing fee must be paid. The blockchain-like mechanism for storing the listings is a technique called Private Information Retrieval and is key to preserving the anonymity and privacy of both the vendor and possible buyer(s).

## Two-party Smart escrow
The **smart escrow system** is devised so neither party can profitably defraud the other party without risk. It is based on mutual assured destrution (MAD): The buyer risks twice the amount required for purchase and the vendor risks the purchase price plus the item that they ship. These funds are locked in a 2-of-2 multisignature address and can only be released when both parties agree and sign the transaction. If they can't agree before a certain expiration date, the funds stay locked indefinitely and the address becomes unspendable. The expiration date is extendable if both parties agree to send the transaction to yet another 2-of-2 multisignature address with a new expiration date.


A new opcode **CHECKLOCKTIMEVERIFY** (CLTV) is implemented to enable the mutual assured destruction, more about the technical specifications of this improvement can be found on the BIP65 github page . Shadow uses a different escrow model than proposed in BIP65, instead we drop both keys when the expiration is reached, essentially destroying the funds.

## Mutual assured destruction (MAD)
This stategy finds its roots in the Ultimatum Game, a well known economic experiment in the field of Game Theory. The key difference between Shadows escrow and the Ultimatum Game is that negotiations are possible in the form of refunds. The payoff matrix exemplifies all the scenarios without the possibility of refund.

![Escrow](escrow.jpg)

**Bad buyer.**  

If the buyer receives the item and decides not to finalize the transaction then the address becomes unspendable after the expiration date and neither party gets their insurance deposit back. The buyer will have effectively paid twice the price but the vendor loses his insurance deposit and the item.  

**Bad vendor.** 

The vendor does not to ship the item, leaving the buyer with the option to finalize the transaction or not: finalizing the transaction causes him to minimalize his loses to one time the price of the item and the vendor makes a profit of one time the item price. If the buyer decides not to finalize the transaction he loses twice the amount of the item price but also causes the vendor to lose his insurance deposit. The buyer is to some extent at a disadvantage and motivated to finalize the transaction to minimize his loses in case of a vendor scam. Both the buyer and the vendor will be motivated to extend the escrow transaction and work towards a refund agreement that both parties are willing to sign.

**Why not use escrow agents then?** 

Because this brings a middleman into the equation which is no means of fairly solving disputes. It is still the buyers word against the vendors. A delivery receipt does not always mean the correct item was received. 

**What if the item was lost in the mail?**

The buyer will have to convince the vendor that he didn't receive the item and both parties must come to a refund agreement that both parties are willing to sign. The vendor may believe the buyer if they have a good history of transactions.  If the vendors thinks you are trying to scam them then he might decide to not deal with you again and you lose your insurance deposit and the vendor loses once the item price and the item lost in the mail.
## Reputation
While two-party escrow with Mutual Assured Destruction is a viable way to prevent most frauds and scams from being profitable, it is not a perfect solution on itself. This is where the reputation system steps in to complement the ecrow system. Each vendor will have a reputation which reflects the (dis)satifisaction of his clients based on their interactions with the vendor.

## Listing fees
The **listing fee**, charged for each market listing, is 0.2 SDC per 4KB per 2 days, so posting a 4KB listing for 4 days will be 0.4 SDC, just as an 8KB ad for 2 days will be 0.4 SDC. Updates to marketplace listings will cost 0.05 SDC and will not add any duration to the listing.

# Hiding your IP
## Tor

**Step 1: Install Tor**
This step is pretty straight forward, install Tor. We advice you to run Tor **as a service**, this means it will start at boot and will always run in the background.

Platform | Service | URL
--- | --- | ---
Windows | No | [Download](https://www.torproject.org/download/download-easy.html.en) 
Ubuntu | yes | apt-get install tor 
Debian |  yes | apt-get install tor
CentOS| yes | yum install tor

Extract the ZIP file if you're on Windows. 
For **Windows** the Tor proxy server will run as long as the *Tor Browser* is open and running. When you close it the connection of Shadow will also drop.
To prevent this from happening we suggest running the Tor daemon as a service, this isn't very hard.

Open up the command line as administator and navigate to the Tor Browser folder.

```cd "C:/what_ever_path/Tor Browser/Browser/TorBrowser/Tor"```

```notepad.exe torrc```

It is extremely important that you add the following to this file: 

```ControlPort auto```

Your Tor Browser will never start up again if you fail to turn the ControlPort on!

```tor.exe --service install --options -f C:/what_ever_path/Tor Browser/Browser/TorBrowser/Tor/torrc```

**Step 2: Download Shadow**
If you truely want to remain anonymous then you should download the Shadow client through Tor.

Open up the Tor-browser and visit https://shadowproject.io/getting-started and download the latest binary for your operating system.
Extract  the ZIP to folder of your choice.

**DOWNLOADING THE BLOCKCHAIN PEER-TO-PEER THROUGH TOR IS VERY SLOW, IT IS ADVISED TO SPEED UP THE PROCESS WITH THE BLOCKHAIN.ZIP METHOD**
Download and put the contents of [the blockchain.zip file](https://github.com/ShadowProject/blockchain/releases/download/latest/blockchain.zip) into your .shadowcoin folder!

**Step 3: Edit settings**
 Open up the Shadow client and go to **Settings > Options > Network**
 
 Enable Proxy settings and set it to:
 Proxy IP: 127.0.0.1
 Port: 9150
 SOCKS Version: 5
 
 Click on OK and you're good to go.
 
**Step 4: Configure the Hidden Service (optional)**

UNFINISHED


For Tor to work in the best configuration you'll want to configure your computer as a hidden service.

Open the following file in your favorite text editor:

Platform | command
--- | ---
Windows | tor-browser_en-US/Browser/TorBrowser/Data/Tor/torrc
Linux | nano tor-browser_en-US/Browser/TorBrowser/Data/Tor/torrc

 Save the file in nano by pressing CTRL + X , enter y to confirm saving and hit enter.

Make sure to replace the **FULL_PATH** with the corresponding path.
For windows this would be something like:
C:/Users/user/Desktop

Linux:
Just type 'pwd' in the terminal and you'll get the path your current folder.

´´´
HiddenServiceDir FULL_PATH/tor-browser_en-US/Browser/TorBrowser/Data/shadow-service/
HiddenServicePort 8333 127.0.0.1:8333
SocksPort 127.0.0.1:9150
´´´



[Click here for a full tutorial](www.sky-ip.org/configure-bitcoin-node-debian-ubuntu.html)


# Support

For support please visit one of the links below:

- Forum: [talk.shadowproject.io](https://talk.shadowproject.io/)
- IRC: freenode.net #shadowcash
- SLACK: [shadowproject.herokuapp.com](https://shadowproject.herokuapp.com/)

# JSON-RPC API Reference

Shadow has many new components meaning we also added extra API calls on top of the original [Bitcoin API.](¶https://bitcoin.org/en/developer-reference#bitcoin-core-apis)


- ```addmultisigaddress``` *adds a P2SH multisig address to the wallet.*
- ```addnode``` *attempts to add or remove a node from the addnode list, or to try a connection to a node once.*
- ```backupwallet``` *safely copies `wallet.dat`<!--noref--> to the specified file, which can be a directory or a path with filename.*
- ```createmultisig``` *creates a P2SH multi-signature address.*
- ```createrawtransaction``` *creates an unsigned serialized transaction that spends a previous output to a new output with a P2PKH or P2SH address. The transaction is not stored in the wallet or transmitted to the network.*
- ```decoderawtransaction``` *decodes a serialized transaction hex string into a JSON object describing the transaction.*
- ```decodescript``` *decodes a hex-encoded P2SH redeem script.*
- ```dumpprivkey``` *returns the wallet-import-format (WIP) private key corresponding to an address. (But does not remove it from the wallet.)*
- ```dumpwallet``` *creates or overwrites a file with all wallet keys in a human-readable format.*
- ```encryptwallet``` *encrypts the wallet with a passphrase.  This is only to enable encryption for the first time. After encryption is enabled, you will need to enter the passphrase to use private keys.*
- ```estimatefee``` *estimates the transaction fee per kilobyte that needs to be paid for a transaction to be included within a certain number of blocks.*
- ```estimatepriority``` *estimates the priority that a transaction needs in order to be included within a certain number of blocks as a free high-priority transaction.*
- ```generate``` *nearly instantly generates blocks (in regtest mode only)*
- ```getaccount``` *returns the name of the account associated with the given address.*
- ```getaccountaddress``` *returns the current Bitcoin address for receiving payments to this account. If the account doesn't exist, it creates both the account and a new address for receiving payment.  Once a payment has been received to an address, future calls to this RPC for the same account will return a different address.*
- ```getaddednodeinfo``` *returns information about the given added node, or all added nodes (except onetry nodes). Only nodes which have been manually added using the `addnode` RPC will have their information displayed.*
- ```getaddressesbyaccount``` *returns a list of every address assigned to a particular account.*
- ```getbalance``` *gets the balance in decimal bitcoins across all accounts or for a particular account.*
- ```getbestblockhash``` *returns the header hash of the most recent block on the best block chain.*
- ```getblock` *gets a block with a particular header hash from the local block database either as a JSON object or as a serialized block.*
- ```getblockchaininfo``` *provides information about the current state of the block chain.*
- ```getblockcount``` *returns the number of blocks in the local best block chain.*
- ```getblockhash``` *returns the header hash of a block at the given height in the local best block chain.*
- ```getblocktemplate``` *gets a block template or proposal for use with mining software.*
- ```getchaintips``` *returns information about the highest-height block (tip) of each local block chain.*
- ```getconnectioncount``` *returns the number of connections to other nodes.*
- ```getdifficulty``` *returns the proof-of-work difficulty as a multiple of the minimum difficulty.*
- ```getgenerate``` *returns true if the node is set to generate blocks using its CPU.*
- ```getmempoolinfo``` *returns information about the node's current transaction memory pool.*
- ```getmininginfo``` *returns various mining-related information.*
- ```getnettotals``` *returns information about network traffic, including bytes in, bytes out, and the current time.*
- ```getnetworkhashps``` *returns the estimated current or historical network hashes per second based on the last 'n' blocks.*
- ```getnetworkinfo``` *returns information about the node's connection to the network.*
- ```getnewaddress``` *returns a new Shadow address for receiving payments. If an account is specified, payments received with the address will be credited to that account.*
- ```getpeerinfo``` *returns data about each connected network node.*
- ```getrawchangeaddress``` *returns a new Shadow address for receiving change. This is for use with raw transactions, not normal use.*
- ```getrawmempool``` *returns all transaction identifiers (TXIDs) in the memory pool as a JSON array, or detailed information about each transaction in the memory pool as a JSON object.*
- ```getrawtransaction``` *gets a hex-encoded serialized transaction or a JSON object describing the transaction.*
- ```getreceivedbyaccount``` *returns the total amount received by addresses in a particular account from transactions with the specified number of confirmations.*
- ```getreceivedbyaddress``` *returns the total amount received by the specified address in transactions with the specified number of confirmations.*
- ```gettransaction``` *gets detailed information about an in-wallet transaction.*
- ```gettxout``` *returns details about a transaction output.  Only unspent transaction outputs (UTXOs) are guaranteed to be available.*
- ```gettxoutsetinfo``` *returns statistics about the confirmed unspent transaction output (UTXO) set.*
- ```getunconfirmedbalance``` *returns the wallet's total unconfirmed balance.*
- ```getwalletinfo``` *provides information about the wallet.*
- ```help` *lists all available public RPC commands, or gets help for the specified RPC.  Commands which are unavailable will not be listed, such as wallet RPCs if wallet support is disabled.*
- ```importaddress``` *adds an address or pubkey script to the wallet without the associated private key, allowing you to watch for transactions affecting that address or pubkey script without being able to spend any of its outputs.*
- ```importprivkey``` *adds a private key to your wallet. The key should be formatted in the wallet import format created by the `dumpprivkey` RPC.*
- ```importwallet``` *imports private keys from a file in wallet dump file format (see the `dumpwallet` RPC). These keys will be added to the keys currently in the wallet.*
- ```keypoolrefill``` *fills the cache of unused pre-generated keys (the keypool).*
- ```listaccounts``` *lists accounts and their balances.*
- ```listaddressgroupings``` *lists groups of addresses that may have had their common ownership made public by common use as inputs in the same transaction or from being used as change from a previous transaction.*
- ```listlockunspent``` *returns a list of temporarily unspendable (locked) outputs.*
- ```listreceivedbyaccount``` *lists the total number of bitcoins received by each account.*
- ```listreceivedbyaddress``` *lists the total number of bitcoins received by each address.*
- ```listsinceblock``` *gets all transactions affecting the wallet which have occurred since a particular block, plus the header hash of a block at a particular depth.*
- ```listtransactions``` *returns the most recent transactions that affect the wallet.*
- ```listunspent``` *returns an array of unspent transaction outputs belonging to this wallet.*
- ```lockunspent``` *temporarily locks or unlocks specified transaction outputs.*
- ```move``` *moves a specified amount from one account in your wallet to another using an off-block-chain transaction.*
- ```ping``` *sends a P2P ping message to all connected nodes to measure ping time.*
- ```prioritisetransaction``` *adds virtual priority or fee to a transaction, allowing it to be accepted into blocks mined by this node (or miners which use this node) with a lower priority or fee.*
- ```sendfrom``` *spends an amount from a local account to a shadow address.*
- ```sendmany``` *creates and broadcasts a transaction which sends outputs to multiple addresses.*
- ```sendrawtransaction``` *validates a transaction and broadcasts it to the peer-to-peer network.*
- ```sendtoaddress``` *sends an amount to a given address.*
- ```setaccount``` *puts the specified address in the given account.*
- ```setgenerate``` *enables or disables hashing to attempt to find the next block.*
- ```settxfee``` *sets the transaction fee per kilobyte paid by transactions created by this wallet.*
- ```signmessage``` *signs a message with the private key of an address.*
- ```signrawtransaction``` *signs a transaction in the serialized transaction format using private keys stored in the wallet or provided in the call.*
- ```stop``` *safely shuts down the Shadow Core server.*
- ```submitblock``` *accepts a block, verifies it is a valid addition to the block chain, and broadcasts it to the network.*
- ```validateaddress``` *returns information about the given Shadow address.*
- ```verifychain``` *verifies each entry in the local block chain database.*
- ```verifymessage``` *verifies a signed message.*
- ```walletlock``` *removes the wallet encryption key from memory, locking the wallet. After calling this method, you will need to call `walletpassphrase` again before being able to call any methods which require the wallet to be unlocked.*
- ```walletpassphrase``` *stores the wallet decryption key in memory for the indicated number of seconds. Issuing the `walletpassphrase` command while the wallet is already unlocked will set a new unlock time that overrides the old one.*
- ```walletpassphrasechange``` *changes the wallet passphrase from 'old passphrase' to 'new passphrase'.*

# Shadow RPC

## anoninfo

```json
anoninfo [recalculate]
```

## anonoutputs

```json
anonoutputs [systemTotals] [show_immature_outputs]
```

## checkwallet
Check wallet for integrity.

## clearwallettransactions
Delete all transactions from wallet - reload with reloadanondata
Warning: Backup your wallet first!

## estimateanonfee

```json
estimateanonfee <amount> <ring_size> [narration]
```

<amount> is a real and is rounded to the nearest 0.000001
Used to estimate the anon fee with a given amount and ring size.


## getnewpubkey

```json
getnewpubkey [account]
```

## getnewstealthaddress

```json
getnewstealthaddress [label]
```

## getstakinginfo

## getsubsidy

```json
getsubsidy [nTarget]
```

## getwork

```json
getwork [data]
```

## getworkex

```json
getworkex [data, coinbase]
```

## help

```json
help [command]
```

## importstealthaddress

```json
importstealthaddress <scan_secret> <spend_secret> [label]
```

## liststealthaddresses

```json
liststealthaddresses [show_secrets=0]
```

List owned stealth addresses.

When used with show_secrets=1 it will return a list of all stealth addresses, the labels, the scan secrets and spend secrets.

## listtransactions

```json
listtransactions [account] [count=10] [from=0] [show_coinstake=1]
```

Returns up to [count] most recent transactions skipping the first [from] transactions for account [account].
If you want to process Stealth transactions (SDT) then you want to use this function.

There a bit of a trick necessary to get the stealth transactions, easier explained in an example:
Stealth address = "smYmoN9xyenTSow9RP4ecf172sdKTeN9k4ZVCiUhFY6MTQRqSS2LRSZSZECwnZSb1a7EaCNc4aPrmrkexBXEs4qeJTZ6m9NjJBgnQE"
=> Account name = "ao smYmoN9xyenTSow9..."

When stealth addresses are generated their account name is "ao first_16_chars...", the 3 dots at the end are important!

## makekeypair

```json
makekeypair [prefix]
```

## nextorphan

```json
nextorphan [connecthash]
```

## reloadanondata
Removes all wallet transactions, anon cache, and rebuilds everything from zero.

## repairwallet
Repair wallet if checkwallet reports any problem

## resendtx

## reservebalance

```json
reservebalance [<reserve> [amount]]
```

## rewindchain

```json
rewindchain <number>
```

## scanforalltxns
Scans for all transactions and overwrites prior history and does update.
```json
scanforalltxns [fromHeight]
```

## scanforstealthtxns
Scans for all Stealth transactions and overwrites prior history and does update.
```json
scanforstealthtxns [fromHeight]
```

## sendalert

```json
sendalert <message> <privatekey> <minver> <maxver> <priority> <id> [cancelupto]
```

## sendanontoanon

```json
sendanontoanon <stealth_address> <amount> <ring_size> [narration] [comment] [comment-to]
```

## sendanontosdc

```json
sendanontosdc <stealth_address> <amount> <ring_size> [narration] [comment] [comment-to]
```


## sendsdctoanon

```json
sendsdctoanon <stealth_address> <amount> [narration] [comment] [comment-to]
```


## sendtostealthaddress

```json
sendtostealthaddress <stealth_address> <amount> [comment] [comment-to] [narration]
```


## setbestblockbyheight <height>

```json
setbestblockbyheight <height>
```


## settxfee

```json
settxfee <amount>
```

## stop

Stop the shadowcoin server


## thinscanmerkleblocks

```json
thinscanmerkleblocks <height>
```

## txnreport

```json
txnreport [collate_amounts] [show_key_images]
```

## thinforcestate

```json
thinforcestate <state>
```

## thinscanmerkleblocks

```json
thinscanmerkleblocks <height>
```

## txnreport

```json
txnreport [collate_amounts] [show_key_images]
```

## validatepubkey

```json
validatepubkey <shadowcashpubkey>
```

# SMSG API
## smsgaddkey
smsgaddkey <address> <pubkey>

```json
smsgaddkey <address> <pubkey>
```

## smsgbuckets [stats|dump]

```json
smsgbuckets [stats|dump]
```

Display some statistics.

## smsgdisable

Disable secure messaging

## smsgenable

Enable secure messaging

## smsggetpubkey

```json
smsggetpubkey <address>
```

Returns the public key for a given address.

```json
Example:
smsggetpubkey tFyq452LPtDotWat8PFwEV5oPoWDqagLNv
Output:
{
"result" : "Success.",
"address in wallet" : "tFyq452LPtDotWat8PFwEV5oPoWDqagLNv",
"compressed public key" : "26S8iEiv2754RskjkWqRZkbZ22iNRYPgK7sUPyRPueXni"
}
```

## smsginbox

```json
smsginbox [all|unread|clear]
```

Decrypt and display all received messages.
"all" will show all messages, "unread" will only show the unread messages.

<aside class="warning">Warning: clear will delete all messages.</aside>



```json
 Example:
smsginbox all

Output:
{
"message" : {
"received" : "2015-09-13 16:19:53 Romance",
"sent" : "2015-09-13 16:19:51 Romance",
"from" : "anon",
"to" : "tFyq452LPtDotWat8PFwEV5oPoWDqagLNv",
"text" : "ShadowCash is awesome"
},
"message" : {
"received" : "2015-09-13 16:18:36 Romance",
"sent" : "2015-09-13 16:18:35 Romance ",
"from" : "anon",
"to" : "tFyq452LPtDotWat8PFwEV5oPoWDqagLNv",
"text" : "This secure messagings is brilliant!"
},
"result" : "2 messages shown."
}
```

## smsglocalkeys
List and manage keys.

```json
smsglocalkeys [whitelist|all|wallet|recv <+/-> <address>|anon <+/-> <address>]
```

## smsgoptions

```json
smsgoptions [list|set <optname> <value>]
```

List and manage the secure message options.


```json
Example 1:
smsgoptions list

Output:
{
"option" : "newAddressRecv = true",
"option" : "newAddressAnon = true",
"result" : "Success."

Example 2:
smsgoptions set newAddressRecv false

Output:
{
"option" : "newAddressRecv = false",
"option" : "newAddressAnon = true",
"result" : "Success."
}
```

## smsgoutbox

```json
smsgoutbox [all|clear]
```

Decrypt and display all sent messages.
<aside class="warning">Warning: clear will delete all sent messages.</aside>

Will also show all messages sent with smsganonsend.

> Example:

```json
smsgoutbox

Output:
{
"message" : {
"sent" : "2015-09-13 16:19:51 Romance",
"from" : "anon",
"to" : "tFyq452LPtDotWat8PFwEV5oPoWDqagLNv",
"text" : "ShadowCash is awesome"
},
"message" : {
"sent" : "2015-09-13 16:18:35 Romance",
"from" : "anon",
"to" : "tFyq452LPtDotWat8PFwEV5oPoWDqagLNv",
"text" : "This secure messaging is brilliant!"
},
"result" : "2 sent messages shown."
}
```

## smsgscanbuckets

Force rescan of all messages in the bucket store.

## smsgscanchain

Look for public keys in the block chain.

## smsgsend <addrFrom> <addrTo> <message>

```json
smsgsend <addrFrom> <addrTo> <message>
```

## smsgsendanon

```json
smsgsendanon <addrTo> <message>
```

Send and anonymous message to an address.

```json
smsgsendanon tFyq452LPtDotWat8PFwEV5oPoWDqagLNv "This secure messagings is brilliant!"

Output:
{
"result" : "Sent."
}
```


# Contribute

Shadow is an Open Source project which is created almost entirely by volunteers. There are lots of ways you can get involved and help the project grow and improve. Here are some ways for you to get started.

## Code

Shadow is controlled by all Shadow users around the world. If you are a developer, you can use your super-powers to do good and contribute. [The Shadow project is hosted on GitHub](https://github.com/ShadowProject/shadow). This is where developers work hard on the next version(s) of the software. To get involved with developing Shadow, check out our detailed contributing guidelines. We credit all contributors to the Shadow project in every major and minor release.

We hold public development meetings and chat in our Slack team. We also maintain a public roadmap and dev blog to give you an idea of what's being worked on right now, and what's coming next. Are you someone who might be interested? Do not hesitate and contact us directly.

## Donate

We are a non-profit and Open Source software project and are trying to build a private economy. We appreciate all the help we can get in making this a reality. Both addresses are managed by Rynomster (lead developer). If applicable, please specify whether you want to remain anonymous. Many thanks to all our sponsors!
 
- Official **BTC donation** address: ```1GiosBkSpN8RS9pm1kgZU8AZUBEnLKYFem```
- Official **SDC development** donation address: ```SdcDevWEbq3CZgZc8UNbST1TaYLA5vLZTS```

## Report

If you think you've found a bug or a problem with Shadow, please let us know! First, search our issue tracker to search to see if someone has already reported the problem. If they haven't, click here to open a new issue, and fill out the template with as much information as possible. The more you can tell us about the problem and how it occurred, the more likely we are to fix it. Please check out our bug and bounty program for our guidelines and more details.

Please do not report security vulnerabilities publicly. The details for responsible disclosure of security issues can be found in our bug and bounty program.

### Bugs & Bounty program

Official bug donation Address: ```Sdcbug68Hcpim7zpnEZsQRRz1rowvz9axS```

According to Linus’ Law, “given enough eyeballs, all bugs are shallow”. That’s one of the reasons why Shadow’s source code is publicly available; but merely making the source code available doesn’t accomplish anything if people don’t read it!

For this reason, Shadow has a series of bug bounties. Similar to the bounties offered by Mozilla and Google, Shadow bug bounties provide an opportunity for people who find bugs to be compensated. Unlike those programs, however, Shadow’s bounties are not limited to security vulnerabilities.

Depending on the type of bug and when it is reported, different bounties will be awarded. Bounties are paid out in SDC, at the 3-day average of each to a fixed US Dollar value.

### Things that do not qualify under the bug bounty

- Bugs found on third-party/community sites, software or services, which is not due to an improper configuration issue specific to us. Please submit any potential issues to the maintainers of that site or providers of that service.
- Vulnerabilities which are too broad or not documented properly (i.e. do not include a specific example relevant to a - Shadow-controlled site or application).
- Bugs or issues with a third-party site, software, or service that we use, which is not due to an improper configuration issue specific to us. Please submit any potential issues to the maintainers of that site or providers of that service.
- Bugs and errors found in software/code that is still undergoing alpha or beta testing.
- Usability issues
- Anything requiring social engineering
- DOS/DDOS attacks
- Missing HSTS (HttpOnly flags), Secure flag, Browser Cache vulnerabilities
- CSRF that doesn’t affect the victim
- Referrer leakage to pages an attacker cannot control.
- The presence of unnecessary files, e.g. for backups, when these files do not expose any sensitive information.
- Anything that is the result of an automated Nessus/PCI scans (too general)
- DNS issues (e.g. lack of an SPF record)
- SSL certificate issues
- Bugs that have received mainstream tech media or community attention before the date of your disclosure.

### Bug Bounties and Rewards

- **$1500** Deanonymize ShadowChat or ShadowSend (proof that a protocol is not anonymous)
- **$750** A flaw in the protocol that allows for theft or loss of funds
- **$500** A bug in the reference client that leads to consensus issues
- **$250** ~ 1 BTC A bug which causes data corruption or loss
- **$100** A bug which causes the application to crash
- **$50** Other non-harmless bugs
- **$10** ‘Harmless’ bugs, e.g. cosmetic errors

### How to report a bug

#### Security-related issues

Contact the developers privately by sending an e-mail to [bounties@shadow.cash](mailto:bounties@shadow.cash) with the details of the issue. Do not post the issue on github or anywhere else until the issue has been resolved.

#### Code issues

We would strongly prefer if you create a pull-request on Github in the proper repository with the necessary fix (along with your SDC address to claim the bounty). For more information, see this link.
