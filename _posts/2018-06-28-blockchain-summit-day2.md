---
title:  "Notes from Blockchain Summit London, Day 2"
---
Day 2 of the Blockchain Summit had a developer track and I particularly wanted to see the session on Performance Engineering for Blockchain Applications, presented by [Ankur Banerjee](https://twitter.com/ankurb?lang=en) from Accenture, before I headed back to the office.

Blockchain currently has a reputation for poor performance; On day 1 James Allerton Austin compared VISA's 16K transactions per second with Blockchain's around 10-250 tps.

I arrived in time to see the tail end of a talk on Blockchain [Redaction](https://www.accenture.com/gb-en/insight-editing-uneditable-blockchain), which provides a redactable blockchain, allowing parties to rewrite blocks if there is consensus. This addresses commercial concerns arising from blockchain's core immutability, about correcting data which may be used for making business decisions, or supporting the right to be forgotten for individuals.

![Blockchain Redaction]({{site.url}}/assets/blockchain-redaction.png)

The blockchain engineering session had a fun warm up act from Elliot Callender and colleague from [Nodeunlock](https://www.nodeunlock.io/) with audience participation on the following questions:

- Would you rather solve governance or interoperability?
- Would you rather develop on a public chain or a private/consortium chain?
- If you have to choose one over the other, would you rather choose security or usability?
- When thinking about regulation ... would you rather have lots of government involvement, or very little?
- If you had to choose only one consensus mechanism would you rather use PoW forever (without access to anything else) or PoS?
- Would you rather all ICO's go through a rigorous filtering system before being public or have a free market where anyone can raise an ICO?

Performance engineering is not just about how your using the core layer. It’s about how your users are integrating with it.

![Blockchain Core Layer]({{site.url}}/assets/blockchain-core-layer.png)

Blockchain Congestion on the core layer boils down to a queueing problem.

Bitcoin typically needs 6 confirmations.

![Consensus Mechanisms]({{site.url}}/assets/consensus-mechanisms.png)

On Ethereum every node executes every single transaction. A lot of very clever people are looking at ways of changing that.

Bitcoin/Ethereum consensus protocols are use-case specific. This is different on other platforms or use cases.

Fabric and other solutions in the enterprise space try to establish consensus use the Byzantine Generals approach. Corda does node-to-node consensus.

A lot of ICO projects aren’t proof of work or proof of stake, but leader-based protocols.

Performance tuning on traditional databases is very common. This is where most of the current efforts are. For now, think databases when considering scaling.

![Database-like Blockchain]({{site.url}}/assets/database-like-blockchain.png)

Bigger blocks is like buses on the highway. Fitting more passengers in a bus eases congestion.

![Blockchain Bus]({{site.url}}/assets/blockchain-bus-analogy.png)

Performance gains for bigger blocks are pretty significant right off the bat.

They got a gain of 600% on Fabric by increasing the block size.

This results on a lot more compute across the network. This might be fine on  a permission network. But it could have an impact on Ethereum network since every node calculates the transaction.

Hyperledger uses CouchDB. You need to load balance it.

Ethereum is looking at sharing. Every full Ethereum node has to process every transaction. Sharding creates partitions so they don’t have to do that.

Nielsen’s law - the bandwidth that the average user has grows a lot more slowly then their processing power.

Do some work off-chain, and do some coordination on-chain. A lot of the heavy compute that’s done doesn’t need to be done on-chain.

We are going back to a level of centralisation to achieve the scale. This will be the case over the next 2-3 years. Then we’ll come up with another strategy.

**How Can Governments and Cities Benefit from Blockchain Technology**

The developer session finished early, so I joined in with this session that had already started. Given the amount of background noise from the hall it was initially very difficult to heard what was being said. However we moved to a side room, which helped.

The main speakers were Jonas Svensson from UNOPS, Amit Varma from Citibank, and Sami Benyakoub from Journal du Coin.

Jonas stated that the viable projects for the UN are UN priorities donations in crypto ... sending the money to where it's needed, and identity projects.

Amit posted that blockchain allows tracking movement across borders. It could lead to new definitions of national boundaries. It's about managing people within boundaries.

Also legal issues .. how can we manage social and antisocial behaviour?

Health ... in some countries health is private and limited. How can we help the many?

Could overnments collaborate to create a [51% attack](https://www.coindesk.com/blockchains-feared-51-attack-now-becoming-regular/)?

Voting is a practical application for governments.

Jonas mentioned that refugees are currently given pre-paid cards to buy essentials. When they cross from one country to another and the currency changes, the cards are tossed. We could do better with blockchain.  Refugees all have phones.






