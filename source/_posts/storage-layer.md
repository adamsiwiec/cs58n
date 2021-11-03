---
title: The Storage Layer
date: 2021-03-10

---

In this article, I will outline what this “storage layer” is in blockchain.  The storage layer is the basic foundation on which the blockchain is built.  In essence, this layer is just the blocks that link to one another. <!-- more -->  These blocks are the individual information units (i.e. if a blockchain were storing information about financial transactions, one block would have information about one financial transaction).  Blocks have been compared to the page of a ledger or a record book.  However, these blocks do not only just store information, they also link to the previous block in order to maintain this “chain.”  Visually:



<a href="https://ibb.co/vwcrTgS"><img src="https://i.ibb.co/6nypTVk/image1.jpg" alt="image1" border="0"></a>



Depending on the function of the blockchain, each block could have different types of information stored, as well as hashed (i.e. hidden) information attached to it.  For most types of blockchains, blocks also store values about who initiated or received the information.  Normally, this data ought to be private, so that’s when information gets stored as a hash value-- usually the “digital signature.”  

However, the blocks themselves are identifiable as well.  That is why (as seen in the visual above) that each block has an associated unique value.  Here, hash values are used yet again in order to tell it apart from other blocks.  This is the basic outline of what composes a block.  For each blockchain, there might be small details such as the types of information stored and the type of information hashed, but the basic premise is maintained.

For more information about the basics of a block in a blockchain: 

[Learn Me A Bitcoin](https://learnmeabitcoin.com/beginners/blocks)

[Blockchain Explained](https://www.investopedia.com/terms/b/blockchain.asp)


