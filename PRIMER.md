# The Kapela Project
> A Primer

Overview: Kapela is a blockchain-powered messaging and payment platform. Messages and payments can be sent as anonymously and securely as one would require, and with a decentralized structure, there is no single point of failure where stored data can be accessed without the permission of a user's private key signature. This results in a cross-platform method of transacting that we are all used to, but without the censorship we face on a daily basis.

**Last Updated:** June 19, 2018

###### [← Return to Main Page](https://github.com/kapela-project/kapela/)

**PLEASE NOTE: THE COINS REFERRED TO IN THIS PRIMER REFER TO CRYPTOGRAPHIC MONETARY UNITS ON A LAUNCHED BLOCKCHAIN/PLATFORM THAT ADOPTS THE KAPELA SOFTWARE. THEY DO NOT REFER TO ANY TRACKABLE TOKENS OR METHODS USED IN PRE-DISTRIBUTION DUE TO THE FEATURES NOT BEING AVAILBLE FOR USE UNTIL AFTER THE KAPELA NETWORK IS LIVE.**

Copyright (c) 2018 The Kapela Project

Without permission, anyone may use, reproduce or distribute any material in this Primer for non-commercial and educational use (i.e., other than for a fee or for commercial purposes) provided that the original source and the applicable copyright notices are cited.

**DISCLAIMER:** This Kapela Primer is for information purposes only. Neither Kapela Communications nor The Kapela Project guarantee the accuracy of, or the conclusions reached, in this Primer, and this Primer is provided “as is”. Neither Kapela Communications nor The Kapela Project make and expressly disclaims all representations and warranties, express, implied, statutory or otherwise, whatsoever, including, but not limited to: (i) warranties of merchantability, fitness for a particular purpose, suitability, usage, title or noninfringement; (ii) that the contents of this Primer are free from error; and (iii) that such contents will not infringe third-party rights. The Kapela Project and its affiliates shall have no liability for damages of any kind arising out of the use, reference to, or reliance on this Primer or any of the content contained herein, even if advised of the possibility of such damages. In no event will Kapela Communications, The Kapela Project, or its affiliates be liable to any person or entity for any damages, losses, liabilities, costs or expenses of any kind, whether direct or indirect, consequential, compensatory, incidental, actual, exemplary, punitive or special for the use of, reference to, or reliance on this Primer or any of the content contained herein, including, without limitation, any loss of business, revenues, profits, data, use, goodwill or other intangible losses.


## Main Idea:

The main idea of The Kapela Project was to fork the DigitalNote project. The decline of DigitalNote can be found in the lack of developer support, as the community seems to still pursue activity and growth, but are not receiving the support needed to even operate the software efficiently. We have no plans on picking up a project from the ashes without receiving a large stake in such project, and with no central authority to dictate such stakes, we are left with the clear solution of forking the software and consuming the previous community base.

In order to expand Kapela as fast a possible, we decided it would be best to rebuild the C++ implementation using JavaScript. This would allow us to focus on a web application, and with a few tweaks we can get both desktop and mobile versions launched. Once the JavaScript implementation is live, we will scrap the old DigitalNote C++ code, and build new software in Go for miners and nodes. At this point, we would have a completely in-house operation with no main code coming from the old DigitalNote team.

TL;DR: C++ to JavaScript. Web, Desktop, and Mobile applications. Source and tools in Go for miners and nodes.


## Extended Idea:

The extended idea of The Kapela Project is to develop a Proof-of-Stake decentralized full-suite communications platform and payment gateway. With a PoS consensus model, the average, and majority, of users will not have to sync with the blockchain or even run a node to participate in the network. By initiating simple P2P verification with a validator node, gateway node or similar, a user has full operational capabilities on the network. This of course allows anyone with a computer and some coins the ability to upkeep the network in a similar manner as a Proof-of-Work miner on a common blockchain, but with less computational restrictions. This is especially important since the target audience will be mobile users who simply want secure uncensorable communications and a fluid method of transacting and storing their digital assets. Due to the projected audience, the mobility of the Kapela network will play a major part in its growth.

In order to meet the cross-platform standards, all of the internal systems and modules of Kapela that are client side will be written and handled in JavaScript. With the release of an initial alpha web application, users will be able to utilize their browser for test connections to peers, at which point they can send instant messages and basic coin transfers. As we develop closer to beta version for the web application, all of the described features and technology in this Primer will be implemented. The source code for the web application will then be tweaked for integration with both [Electron](https://electronjs.org/) for cross-platform desktop application, and with [React Native](https://facebook.github.io/react-native/) for cross-platform mobile applications.

With different functionality being present in different segments of Kapela, there are different nodes that are utilized for these features to work in scale:
- **Validator Nodes:** for blockchain consensus
- **Gateway Nodes:** for extended access to the network
- **Storage Nodes:** for sharded file storage
- **Client Nodes:** all base users on the network<br>
    - **Verified Nodes:** verified clients for social networking

All nodes are in contact with the Validator Nodes in some way, and by conducting operations, these nodes earn coin emissions on the network as well as any fees for intensive transactions by users.


## Plans:

### Chat Protocol

### Coin Protocol

### Storage Protocol

### Exchange Protocol

### Web Application

The web application for Kapela is an essential function that we believe will enhance our users experience. The ability to use a web application over a desktop application or mobile application we believe is a strong feature that many will love. The web application will consist of all major features that the desktop and mobile applications have. A big advantage of having a web application for our users is the ability to have a broad range dashboard that will be able to be customized with ease. You will be able to have direct API functionality for popular applications within Kapela as well. 

### MacOS Application

With MacOS being a forefront in emerging technology our main priority of focus was towards our development of a fully functional MacOS application. The Mac application will consist of all the features that Kapela has to offer and will have direct integration with popular applications that exist in MacOS such as: Contacts, Calendar, File sharing, notes and several other popular features that Mac has to offer. These features along with others are can be enabled and disabled through your preference menu located within the Kapela application.

### Linux Application

### Windows Application

The Windows application will be a very big essential to the deployment of Kapela. Windows capatible devices are 4x more common in households according to several recent studies. With that being said we want to make sure we reach all the users that are custom to Windows. All features will be available within the application and will be able to have several integrations such as: Contacts, notes, file sharing, along with several other features. All of which can be enabled and disabled through your preference menu located within the Kapela application.

### iOS Application

### Android Application

### Chrome Extension


## Features:

### Always Encrypted and Private

Messages, calls, videos, file transfers, payments, etc are all secured with end-to-end encryption. User personal information and data is also encrypted using the user's private key in order to ensure there are no possible breaches, leaks or publications unless the user authorizes it. Only your private key can access your data.

With correct authentication, one account can works on multiple devices, with your data being encrypted for each device. Just sign in with your account information or invoke your private key to unlock your account on the device and prove authentication. With Kapela being able to work cross-platform on web, mobile, and desktop; being able to access your account on multiple devices while keeping your data in sync will be a major reason to use our platform.

### Instant Messaging

Instant messaging refers to the instantaneous exchanging of text-based messages and binary entities, such as pictures, videos, and files between users on the network. Users can send messages directly 1:1, in groups, supergroups, or channels. All private data exchanges within Kapela are subject to end-to-end encryption with the direct intention of providing users with a strong degree of privacy and security. Message exchanges are also cryptographically programmed with forward and backward secrecy, so a compromised key has minimal impact.

Forward secrecy is designed to prevent the compromise of a long-term secret key from affecting the confidentiality of past conversations, however, it does not protect against cryptanalysis of the underlying ciphers being used, which such attacks decrypt messages without the key, as forward secrecy only protects keys, not the ciphers themselves. By using one-time keys for transactions, sessions, and for every message exchange, we can greatly reduce any possibility of cryptanalysis due to above-industry standard encryption methods and our key management system. Any attempt at decryption would be extremely computationally expensive or simply futile.

### Audio and Video Messages

Users can record memos and video clips inside the Kapela app, and then send these as messages within any direct or group chat. The audio and video clips are encrypted and uploaded to the Kapela storage system where only the user's account can have access or authorize external access to other accounts. The ability to send quick voice bits instead of written text has become very popular among people in Asia, the Middle East and South America.

### Voice Calls

### Video Calls

### Secure File Sharing

### Private File Storage

### Rich Conversations

### Timed Messages

### Digital Assets

### Payment Gateway

### Simple Smart Contracts


## Technology:

### Peer-to-Peer Communications:

### Public Key Cryptography:

### Byzantine-Fault Tolerant State Machine Replication:

### One-time Keys:

### Ring Signatures:

### Proof-of-Stake Consensus:

### Internal Bandwidth Valuation Monetary Units:

### Smooth Emissions:

### Double-spending Proof:

### Blockchain Analysis Resistant:

### Adaptive Parameters and Limits:
