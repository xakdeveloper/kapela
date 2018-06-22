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

The Windows application will be a very big essential to the deployment of Kapela. Windows compatible devices are 4x more common in households according to several recent studies. With that being said we want to make sure we reach all the users that are custom to Windows. All features will be available within the application and will be able to have several integrations such as: Contacts, notes, file sharing, along with several other features. All of which can be enabled and disabled through your preference menu located within the Kapela application.

### iOS Application

The ability to access Kapela on the go is an integral step in our development of Kapela. Everywhere you go around the world you will see people using their smart phones either texting, calling, playing games, etc. It is essential for a messaging application to be accessible to your personal wherever you are located so the development of Kapela for iOS was of upmost importance. You will be able to have all the popular features that we have to offer as well as multiple integrations that are located within iOS devices. You will be able to download the application via the App Store.

### Android Application

Like the iOS applicaiton, the ability to access the Kapela app on the go is of upmost importance for a successful project. With Android being the second most popular mobile device software used to communicate around the world it was essential that Kapela will be able to operate on Android. Users will have access to all core functions of Kapela and like the iOS application, be able to sync contacts, link applicable applications, and much more. The Kapela application will be accessible via the Google play store.

### Chrome Extension

The Chrome Extension will enable users to have shortcuts to Kapela while doing everyday web browsing on the Google Chrome application. When promoted for a payment, messages, contact info, etc, there will be a direct link where Kapela will be able to fill the field necessary. You will be able to link the Kapela extension to your desktop application for quick access.

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

Kapela is the first of its kind. Never before has there been an effective voice call application hosted on the blockchain. With Kapela, you will be able to call your associates via their username. No need to remember phone numbers or have to worry about number changing. With the ability to call users by their username you will be able to access a broad range of new individuals. Most individuals who use social media platforms generally have the same or similar user name as a different platform.

You will be able to simply type a name and it will search through our database with profile names and usernames that are similar to a name or directly type in a username to host a voice call. If you are worried that you could be spammed with calls, no need to worry you will only be able to see notifications from users on your friend list or if you enable a setting 'allow calls from all users'.

### Video Calls

Video calling has been a huge explosion as a form of communication in the recent years, particular the application called 'Facetime' that is available on iOS devices. However, the big issue with Facetime is that there is currently no ability to have multiple people in one call. We have read feedback from iOS users regarding this issue and we created a way that solves their concerns.

With Kapela, not only will it be hosted on a blockchain but on it you will be able to have a group video call with your associates. With a simple click of a button you can call whoever you like and add your friends as well. We strongly believe that this feature will be a huge success and very popular amongst our users.

### Secure File Sharing and Storage

Our secure file sharing is protected with IPFS, which provides for a totally complete decentralized environment for our users to secure their files. Only you will have access to your cloud and you will be able to store as many files as you would like according to your specific cloud database.

In order to share files, users will navigate to their file browser and will be able to share the invidual file/folder with your associates by simply typing in their username in the share box and send it off. The receiver of the file will then have full access or specific access according to the limitations that you have set forth. For example, if you have a word document that you do not want edited but needs to be shared, you can send it to a username with the title 'read' to prevent the user(s) from editing the document.

### Rich Conversations

In the modern society we have multiple ways of communicating via messages. There are Emojis, Gifs, Files, Pictures, etc that can all be sent through popular messaging platforms. In Kapela we wanted to embody those specific features to enable our users to have the best expiernce possible. Users will be able to customize your message in terms of color, font, and size. Users will be able to copy/send specic items from websites and open without leaving the application. All will be available in group messages as well with no limit on the amount of users in a thread. Users will be able to have the experience like no other in terms of full customization and unlimited messaging.

### Timed Messages

Ever worried about someone accessing your messaging application or confused on how to delete sensitive material on the application... No need to worry, Kapela comes equipped with a self set timer that the sender will be able to select the duration of the message. If a timed message is sent then the certain message will be deemed 'sensitive' and therefor will notify the sender if a screenshot or screen record is taken of the message. You can use this feature by holding down the send button and selecting 'add timer'. You can enable and disable this feature in your Kapela preference menu.

### Digital Assets

Users will be able to send, receive, and store the KAP coins via the Kapela application. We wanted to make sure that your assets are as simple to manage as possible. The Kapela dashboard will enable users to track their balance, transactions, and purchases. Users will never have an issue forgetting where something went or what it was used for. In each transaction box, users can type a short description to remember what has transpired according to each individual transaction. Popular coins such as BitCoin, Ethereum, and Litecoin will be easily exchanged into KAP via the Kapela application. Each conversion is logged with the value of each token involved in the exchange, dated, and timestamped to ensure 100% accuracy.

### Payment Gateway

### Simple Smart Contracts

On the Kapela application users will be able to deploy their own smart contracts for their projects. Like Ethereum this is a strong method that we believe will take Kapela to the next level and grow and thrive the crypto space. 


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
