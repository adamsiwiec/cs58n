---
title: Smart Contracts and the Communication Layer
date: 2021-03-10
---

**Smart Contracts**

In its essence, blockchain is a native digital medium for value – that is, it allows for the exchange, transaction and management of anything of value. From money, to music or votes, this concept allows the user to give and receive elements without double-spending.
<!-- more -->
Now that we’ve taken a deep look into the underlying technology that enables a blockchain (see Figure 1), we can analyze the last layer: the transaction programs. This is the icing on the blockchain cake, as it integrates all the previous layers into a programmable exchange.

   
<a href="https://imgbb.com/"><img src="https://i.ibb.co/FJ7V5pM/image1.png" alt="image1" border="0"></a>
Figure 1 Layer Cake Diagram of blockchain technology

## Current state

There’s a problem common to the very nature of trade that we still haven’t solved properly: trust. A clear example of this can be found in global trade. Imagine the case of a new flower store in California that wants to order a container of tulips from the Netherlands just in time for Valentine’s day. After finding a suitable supplier and receiving a quote for the products, the inevitable question arises: Who should pay first? Should the flower store send the money to the supplier first and risk bankruptcy if the farmer just stops answering its emails? Or should the supplier send its tulips first, and then risk not receiving any money for its flowers?

Maersk analyzed this situation in **_2018_** and found out that, in order to generate trust between two parties in the uncertainty of global trade, 90% of companies use brokers and at least 80 people get involved in building a large paper trail for every shipment that takes place. From banks to third party intermediaries, this is a largely inefficient process – smart contracts bring a simpler alternative.

## What is it?

The concept of a smart contract finds its counterpart in conventional contracts. In this sense, both a smart contract and a conventional contract are a legally enforceable agreement between two (or more) parties. Moreover, both should have an offer, consideration, and acceptance to make it valid. However, the key difference is that the terms in a smart contract are programmed in a computer and then committed to a blockchain. Therefore, they are executed no matter what.

Both the code and the conditions in the contract are publicly available on the ledger they are a part of, which ensures transparency and accountability from all parts involved. This concept is akin to the system used in your monthly Netflix subscription, where if a month goes by then your credit card is automatically charged.

## How does it work?

The principle used in programming smart contracts is based on simple programming logic: if **_A_** happens, then do **_B_**. In this case, **_A_** is called a “trigger event” and it can be used to encode the conditions one of the parties has to meet before a transaction is completed. For instance, a trigger event could be an expiration date or a target price. After all trigger events have been met, then the contract’s code executes.

Therefore, after the basic conditions have been met, the contract automatically transfers the value to the relevant parties. An interesting property of smart contracts is that value can take multiple forms, from cryptocurrency to documents or objects, which gives it a great flexibility as well.

Finally, the transfer of value is recorded in the blockchain to allow for accountability – this step is called the settlement. This procedure ensures accountability, and is of great value for auditors given that it enables three important factors:

1.   	Each auditor has access to the current state of the chain, including balances and coded contracts

2.   	Any party can compute the effect of a transaction, since it has access to all the information, and verify its outcome

3.   	Any party can confirm the existence of any block in the blockchain, which would potentially avoid fraud in transactions

All in all, smart contracts don’t build trust between parties: they eliminate the need for trust altogether. In other words, neither the florist nor the farmer needs to trust each other: they both trust the code with their assets. In theory, it will enable users to build a bullet-proof contract, which only (but surely) executes when certain conditions are met. If one of the parties fails to meet its part of the agreement, the contract simply holds the goods. Certainly, we believe this is a big step in terms of public accountability, since all validators can verify all transactions in the blockchain.

## Looking forward

According to Mckinsey & Co. (2018), potential applications of smart contracts include automation of insurance-claim payouts, healthcare record access for research, and temporary employment contracts. However, some drawbacks of the technology lie in the difficulty of its widespread adoption, the difficulty of learning how to code and revise a contract’s code, and the process to invalidate a contract if a bug occurs or (for instance) one of the parties signs it under coercion. If you’re interested in other practical uses of smart contracts, look into the Applications section for more information.

## Additional readings

Accenture,[ Mapping new trade routes to trust](https://www.accenture.com/_acnmedia/pdf-79/accenture-blockchain-mapping-trade-routes-to-trust.pdf)

WTO,[ Can blockchain revolutionize international trade?](https://www.wto.org/english/res_e/booksp_e/blockchainrev18_e.pdf)

Mckinsey & Co,[ Blockchain technology for supply chains: a must, or a maybe?](https://www.mckinsey.com/business-functions/operations/our-insights/blockchain-technology-for-supply-chainsa-must-or-a-maybe)

**Communication layer**

A blockchain is built on consensus between all blocks when it comes to any individual action. Therefore, the process of building a blockchain needs have a network protocol that allows effective interaction between blocks – this is the role of the communication layer.

The communication layer undergoes two main procedures when taking a decision: a communication step and a broadcast procedure.

Imagine the case of proposing the addition of a new block to the blockchain. The communication step would involve the proposal of a new block through the internet, and a group voting procedure via consensus protocol to ensure that dishonest blocks don’t compromise the integrity of the blockchain (see: consensus layer).

Moreover, after the decision is taken, it must be broadcasted. At the most basic level, any block can communicate directly to its immediate neighbors. However, given that the design of the blockchain allows for some nodes to be separated from others by one (or multiple) degrees of separation, a broadcast method is also employed. Therefore, in these cases, the intermediary nodes can act as a relay for the message, sending it to its nearest neighbors repeatedly. This principle allows for every node to communicate with the entire blockchain, as seen in Figure 2.

<a href="https://imgbb.com/"><img src="https://i.ibb.co/pJHHLk9/image2.png" alt="image2" border="0"></a>

Figure 2 Relay communication between nodes in a blockchain

## Additional readings:

Packt, Exploring Blockchain and BaaS

David Xiao, The Four Layers of the Blockchain

Sankar, G et al., A reference Architecture for Blockchain-based Peer-to-Peer IoT Applications

Lamport, L et al., The Byzantine Generals Problem

**Predictions (!)**

- By 2030, Blockchain will be widely used in the management of letters of credit for global trade.

 