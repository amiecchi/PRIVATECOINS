# PRIVATECOINS

## Why we need private coins?

Right now, digital payments are fundamentally lacking in privacy — they are surveilled, analyzed, collected, and sold. With every online purchase, your metadata for that transaction is stored (from what IP you used, to your physical location, to your purchase history, and more).

Privacy leads to innovation, social evolution.

Blockchain is an open distrubuted ledger that can record transactions between teo parties in a verifiable and permanent way but it is open soucrce anybody can see your transactions. Due to open source nature of blockchain people can see your tractions and how much cryptos you have and how you are spending it it leads to various types of concerns thats why we need private coins 

Private coins  can secure your  tranactions as well as hide your identity 

“The lack of financial privacy is detrimental to most cryptocurrency use cases,” they continue. “We do believe if users were using the technology in a sound way or a privacy-focused wallet software would have helped them and abstracted away potential privacy leaks.

# How the transaction take place in crypto coins 

## UTXO'S (UNSPENT TRANSACTION OUTPUT)
The term UTXO refers to the amount of digital currency someone has left remaining after executing a cryptocurrency transaction such as bitcoin. The letters stand for unspent transaction output. Each bitcoin transaction begins with coins used to balance the ledger. UTXOs are processed continuously and are responsible for beginning and ending each transaction. Although confirmation of transaction results in the removal of spent coins from the UTXO database, a record of the spent coins still exists on the ledger. 

### How a UTXO Works?
UTXO transactions sound complicated, but they really are fairly simple. UTXO or unspent transaction outputs are used in cryptocurrency transactions. These are the transactions that are left unspent after someone completes a transaction, similar to the change someone receives after conducting a cash transaction at the store.


Here's how it works. A UTXO database is used to store change from cryptocurrency transactions. This database or ledger is initially set to empty or zero. As transactions multiply, the database becomes populated with change records from various transactions. When a transaction is completed and there are outputs that aren't spent, they are deposited back into a database as inputs that can be used at a later date for a new transaction. Cryptocurrency transactions—such as those used for bitcoins—are similar to cashier checks. You cannot exchange them for custom amounts and must spend the entire amount stored in that data byte.

But cryptocurrencies like bitcoin are also unique in that transactions can be conducted using fractions of the cryptocurrency. This means spending does not take place using a single data byte. Instead, multiple fractions of bitcoin are retrieved by the algorithm to fulfill a spending request. For example, a purchase worth 1 bitcoin may retrieve 0.6 BTC from one byte and 0.4 BTC from another. Change from each of these fractions is then sent to the UTXO database to be spent at a later date.

[UTXO'S](https://youtu.be/hKft6E4K8KY)

## TECHNOLOGY AROUND PRIVATE COINS

##### 1.COIN JOIN

CoinJoin is a trustless method for combining multiple Bitcoin payments from multiple spenders into a single transaction to make it more difficult for outside parties to determine which spender paid which recipient or recipients.

CoinJoin is an anonymization strategy that protects the privacy of Bitcoin users when they conduct transactions with each other, obscuring the sources and destinations of BTC used in transactions.


CoinJoin requires multiple parties to jointly sign a digital smart contract to mix their coins in a new Bitcoin transaction, where the output of the transaction leaves the participants with the same number of coins, but the addresses have been mixed to make external tracking difficult.


The process is also known as coin mixing.

###### KEY TAKEAWAYS


CoinJoin is a process used to anonymize Bitcoin transactions online.
CoinJoin involves a multi-party Bitcoin transaction where all parties to the transaction put in and get out the same amount of Bitcoin, but the addresses are mixed in the transaction making the origin of the coins difficult to trace.
CoinJoin is typically performed automatically by dedicated services that carry it out. Performing a CoinJoin without such a tool is difficult and requires advanced coding skills.

#### 2. MIMBLEWIMBLE

Mimblewimble is a ridiculously-named technology that stops blockchains from blabbing personal information. It’s named after a Harry Potter spell that stops people from spilling secrets.

Harry Potter — Warners Bros — Mimblewimble
Satoshi Nakamoto’s Bitcoin paper has a section titled ‘Privacy,’ in which Nakamoto is very realistic about Bitcoin’s privacy limitations. These limitations have gotten worse as adversaries have gotten better at using the data Bitcoin spills to dox/deanonymise Bitcoin users. This surprised some people who thought Bitcoin was private because it doesn’t disclose names. Let’s look at what data it does disclose, and why —
Bitcoin blabs three secrets to fulfill two requirements

Bitcoin blabs three secrets about every transaction:
Sender’s address
Amount of coins sent
Receiver’s address
Bitcoin doesn’t reveal these because it hates privacy. It reveals them because any money system — gold, cash, barter— has to fulfill two requirements:
It has to verify that the amount received is equal to the amount sent. A cryptocurrency would be hopelessly broken if I could make a transaction sending 1 coin from one address, and receiving 2 at another address. If I put 5 euros in your hand, 5 euros leave my hand, and 5 enter your hand. I lose five, you gain five, no money is created from thin air during the transaction, and none vanishes.
I cannot initiate a wire transfer from your bank account, but rather only from my own. We have to verify that the transaction is sent by the holder of the debit card and PIN, or the online banking password, or the private key in the case of cryptocurrencies.
Bitcoin fulfills the two requirements by spilling the three secrets above.
Bitcoin transactions contain the amount and the receiver’s address in plaintext. That is enough to meet the first requirement; we see that 5 bitcoins went into the transaction, and 5 came out.
To verify that the second requirement is fulfilled, Bitcoin uses public addresses with corresponding private keys. The public address owns the bitcoins. The sender generates a signature using the corresponding private key, and signs his transaction (which, I repeat, contains the amount and the receiver’s address in plaintext). Everyone can check that the signature comes from the private key behind the address that holds the coins; this way we know the signature comes from the guy with authority to initiate the transaction.

#### 3.ZERO KNOWLEDGE SHILDED TRANSACTIONS

Zero Knowledge Protocol (or Zero Knowledge Password Proof, ZKP) is a way of doing authentication where no passwords are exchanged, which means they cannot be stolen. This is cool because it makes your communication so secure and protected that nobody else can find out what you’re communicating about or what files you are sharing with each other.





ZKP allows you proving that you know some secret (or many secrets) to somebody at the other “end” of communication without actually revealing it. The very term “zero knowledge” originates from the fact that no (“zero”) information about the secret is revealed, but the second party (called “Verifier”) is (rightfully) convinced that the first party (called “Prover”) knows the secret in question. Why would you need to prove you know the secret without telling it? When you don’t trust the other person, but still need to persuade them that you know it. So what does the process look like?





Candy bars and millionaires
Let’s illustrate it with the help of Bob and Alice who got some chocolate bars for Halloween.

They would like to know if they received the same amount of candy, without disclosing their number of chocolates because they don’t want to share.

Let’s assume they can have exactly 10, 20, 30, or 40 chocolate bars in their trick-or-treat bags.

To compare the number of chocolate bars they got without sharing the actual number, Bob gets 4 lockable boxes and puts a label in each that says 10, 20, 30 or 40 (chocolate bars).

Then Bob throws away all the keys except for the key to the box that corresponds to the number of chocolate bars he’s got (let’s say he has 20 chocolate bars) and leaves.

Alice takes 4 small pieces of paper and writes “+” on one of them and “-” on all the others.

Then she slips the “+” piece through a slot into the box with the number that corresponds to the number of candies she’s got (let’s say she has 30 candy bars) and slips the pieces of paper with “-” on them into the rest of the boxes and also leaves.


Bob returns and opens the one box he still has the key to — the one that corresponds to the amount of candy he’s got — and sees if it contains “+” or “-”.

If it is a “plus”, Alice has the same number of chocolate bars in her bag. If the slip of paper says “-”, it means that they have a different amount of candy (but still will not share with each other).

We know that Bob’s bag contains 20 chocolate bars and Alice’s — 30 chocolate bars. By opening the box and finding the piece of paper with a “minus” on it, Bob learns that he and Alice have different amount of candy. But he has no way of finding out whether Alice has more or fewer chocolate bars.

Alice also returns and sees that Bob has a piece of paper with a “minus” on it. So he has a different amount of candy. But both Alice and Bob still don’t know how many chocolate bars each of them has. They only know that they don’t have the same amount.

Such example, in a slightly different form, is widely known as Yao’s Millionaire’s Problem where two millionaires want to find out if they have the same amount of money without disclosing the exact amount. This is one simple example of how ZKP works.


#### 4.CONFIDENTIAL TRANSACTIONS 

Confidential Transactions keep the amount and type of assets transferred visible only to participants in the transaction (and those they choose to reveal the blinding key to), while still cryptographically guaranteeing that no more coins can be spent than are available.

This goes a step beyond the usual privacy offered by Bitcoin’s blockchain, which relies purely on pseudonymous (but public) identities. This matters, because insufficient financial privacy can have serious security and privacy implications for both commercial and personal transactions. Without adequate protection, thieves can focus their efforts on high-value targets, competitors can learn business details, and negotiating positions can be undermined.

#### 5. STEALTH ADRESSESS


Stealth addresses are used in transactions done via cryptocurrencies on a blockchain network to obscure public access to the parties involved in the transactions. Stealth addresses operate by having the sender use a one-time address for every transaction, even if multiple transactions are done with the same recipient. As a result, stealth addresses are helpful with ensuring the privacy of the receivers of cryptocurrency payments and their financial details.


However, stealth addresses have faced scrutiny from regulators and tax authorities as non-public addresses can be used for illegal behavior, including money laundering, the drug trade, and funding terrorist activity.


KEY TAKEAWAYS
Stealth addresses are a technique for obscuring public blockchain transactions by generating one-time addresses for each transaction.
Blockchain networks involve pseudonymous transactions, meaning once personal information is linked to a crypto key, transactions using that key can be traced on the blockchain.
Stealth addresses have grown in popularity due, in part, to concerns about hackers gaining access to digital wallets and stealing cryptocurrency coins.
Stealth addresses have faced scrutiny from regulators and tax authorities since they can be used for illegal behavior, including money laundering.


#### 6. RING SIGNATURES 

The Basics
In cryptography, a ring signature is a type of digital signature that can be performed by any member of a group of users that each have keys. Therefore, a message signed with a ring signature is endorsed by someone in a particular group of people. One of the security properties of a ring signature is that it should be computationally infeasible to determine which of the group members' keys was used to produce the signature.

For instance, a ring signature could be used to provide an anonymous signature from "a high-ranking White House official", without revealing which official signed the message. Ring signatures are right for this application because the anonymity of a ring signature cannot be revoked, and because the group for a ring signature can be improvised (requires no prior setup).

#### 7. MIXING

Cryptocurrency tumbler or cryptocurrency mixing service is a service offered to mix potentially identifiable or 'tainted' cryptocurrency funds with others, so as to obscure the trail back to the fund's original source. This is usually done by pooling together source funds from multiple inputs for a large and random period of time, and then spitting them back out to destination addresses. As all the funds are lumped together and then distributed at random times, it is very difficult to trace exact coins. Tumblers have arisen to improve the anonymity of cryptocurrencies, usually bitcoin (hence Bitcoin mixer), since the currencies provide a public ledger of all transactions.

## DIFFRENT TYPES OF PRIVATE COINS 

# 1. Z CASH

ZCash is a cryptocurrency with a decentralized blockchain that seeks to provide anonymity for its users and their transactions. As a digital currency, ZCash is similar to Bitcoin. Like Bitcoin, ZCash also has an including its open-source code, but their major differences lie in the level of privacy and fungibility that each provides.


KEY TAKEAWAYS
ZCash is a cryptocurrency with a decentralized blockchain that seeks to provide anonymity for its users and their transactions.
ZCash increases user privacy by using zero-knowledge proofs (zk-SNARKs) to validate transactions without revealing information that could compromise a user's privacy.
ZCash is built on the Bitcoin framework, and, in many respects, is identical to Bitcoin.

##### Zcash Weaknesses & Disadvantages
Potential for Misallocation of ZEC Quantity: In the Zcash protocol's present state, if the network is exposed to a bug that allowed for people to generate more Zcash coins than the intended money supply, the resulting inflation would crash the price of Zcash for speculators

#### MONERO

Monero is a digital currency that offers a high level of anonymity for users and their transactions. Like Bitcoin, Monero is a decentralized peer-to-peer cryptocurrency, but unlike Bitcoin, Monero is characterized as a more anonymous or privacy-oriented digital cash.


KEY TAKEAWAYS
Monero is a popular blockchain-based cryptocurrency, or altcoin.
Monero has several privacy-enhancing features that improve upon Bitcoin.
Like Bitcoin, Monero is open source and created from decentralized, grass-roots development.

##### Some notable weaknesses of Monero:
Privacy. I would argue that Monero is the most private currency around, but it is not perfect. ...
Mining centralization. ...
No phone wallets. ...
Transaction size. ...
Limited use. ...
Development difficulty. ...
Limited merchant tools. ..

#### DASH

Launched in 2014, the cryptocurrency Dash was originally known as Xcoin. After being rebranded as Darkcoin, it landed on its current name, Dash, in March 2015. When it was initially created, it was designed to ensure user privacy and anonymity. The cryptocurrency’s whitepaper, co-authored by Evan Duffield and Daniel Diaz, describes it as a privacy-centric cryptocurrency based on Bitcoin founder Satoshi Nakamoto’s work.1


KEY TAKEAWAYS
Dash aims to become a medium for daily transactions as a digital currency that can be used as cash, credit card, or via PayPal.
In 2018, the digital cash company expanded into Venezuela, the cryptocurrency's first foray into an economically-distressed country.2
Dash is run by a subset of its users, which are called "masternodes."
All masternodes have a starting stake, which is equal to 1,000 DASH in their systems.
While it still features strong encryption features, the company has since recast its ambitions. Dash now aims to become a medium for daily transactions as a digital currency that can be used as cash, credit card, or via PayPal. Dash is an open-source project which includes a decentralized payment network.

##### WEAKNESS OF DASH
We still explore how it scales for many concurrent users.
At some point, you will need more sophisticated components than Dash provides by default.
You'll have to write your own components in React.js.
Or you'll have to port already existing components from React.js to Dash.

##### GRIN 

GRiN — THE MIMBLEWIMBLE BLOCKCHAIN

Grin is a privacy-preserving digital currency built openly by developers distributed all over the world.

Grin has no amounts and no addresses. Transactions can be trivially aggregated. To hide the origin of a newly created transaction, it gets relayed among a sub-set of peers before it is widely broadcasted.

Grin is not controlled by any company, foundation or individual. The coin distribution is designed to be as fair as possible, with an emission of 1 GRIN per second.

Mimblewimble leverages cryptography to allow past transaction data to be removed with no compromise on security. This avoids Grin collapsing under the weight of data having to be kept on chain.

##### WEAKNESS OF GRIN COIN

the degree of decentralization and sheer mining power securing the network. regulatory and censorship risk (not of the protocol, but points of weakness around it: on-boarding, off-boarding, services leveraging Grin and individual users themselves) a need for a privacy-focused digital cash

#### 5. IRONFISH

Iron Fish is a decentralized, proof-of-work (PoW) based, censorship-resistant, and publicly accessible blockchain project. It is designed to support strong privacy guarantees on every transaction. Similarly to how the invention of the SSL/TLS layer in the 90s paved the way to e-commerce and benefited countless industries, we believe that privacy is a fundamental requirement to protect the user and expand the use of cryptocurrency.

We have designed Iron Fish to be a new cryptocurrency from the ground up to enable easy-to-use, fully-private payments by closely following the Sapling protocol. Every account is equipped with a view-key to grant its holder read-only permission for the details of that account.

With this protocol we are challenging previous patterns of full node usability. The Iron Fish networking layer supports WebRTC with WebSockets, making it trivial for all users to make a true P2P connection with no other setup requirements. Our first Iron Fish implementation is built such that it can be extended to run a full node directly in the browser in future iterations. And our focus is to lower the barrier to entry so that any person with a computer feels comfortable enough to run a full node.


