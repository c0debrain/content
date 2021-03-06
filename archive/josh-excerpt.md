# What is Cryptocurrency?
topics: **bitcoin, blockchain, decentralization, transactions**

briefs: *digital signatures, wallets, store of value, source of truth*

## Cryptocurrencies
  Cryptocurrencies are a way to represent value, digitally.  The first major cryptocurrency is called Bitcoin.  You may be familiar with Bitcoin already: you may have heard it was used on the  "darkweb" or heard about it skyrocketing over 50 times it's value in less than a year. ~~You can think of cryptocurrencies as a digital store of value(**im uneasy about saying this.  techincally it has no value, we just kinda pretend it does which makes it so -Kevin**)~~ A cyptocurrency's value is based on supply and demand: if more people want it and are willing to pay for it, its price goes up(**thoughts?**).  If people don't want it, its price moves down.  Similar to how if you wanted to make a purchase of a 1000$ laptop at a store with your debit card, the point-of-sale machine reads your card, determines your account information, then checks to see if you have enough money to make the purchase. Cryptocurrencies(**factcheck**) accomplish this by using what's called a blockchain(**link**).  Suppose there are two people, Alice and Bob, who want to make a transaction, using a cryptocurrency (like Bitcoin). In simple terms, Alice wants to send 3 bitcoins to Bob. Alice's transaction is digitally signed(**modal about signatures**) to prove it came form her wallet(**modal about wallets**). To check if Alice has enough money for the transaction, we look at a list of every transaction to every wallet since the start of Bitcoin (true for Bitcoin, not for everything; see Eth -Kevin).
	
{picture example of list of transactions}

## Blockchains
  By looking through every transaction that's ever been made (**or a "current status" dictionary like in Eth**), we can see, without a doubt, the exact amount of Bitcoin every person has. Consider this example: there are 100 people trading cryptocurrencies.  Whenever anyone in this group wants to send money to anyone else in this group, they must first come to me and tell me the details of the transaction (**what are we making an example for here?** -Kevin).  I record these in a big notebook:  When Person #1 tells me he wants to give 10$ to Person #2, I check their ID (and signature) to make sure it's really them, then read my notebook from start to finish, and calculate all the money that has come in and out of Person #1's account.  If he has enough money for the transaction, I write it down in my notebook, subtracting the money from Person 1 and adding it to Person 2.  Simple right?  But you might see a problem: Cryptocurrencies don't have a physical representation like dollars or euros.  Because all of their wealth is represented in my notebook, if I accidentally write down the wrong amount, or maliciously change someone's wealth, I have the single source of truth, so everyone would just have to believe me.  This might happen in the real world, with a bank having a software bug causing them to misplace their customer's money, or a greedy executive changing the ledgers and "cooking the books".

## Decentralization
  A benefit to these cryptocurrencies that are based on blockchains is that they are decentralized. Instead of Person #1 coming up to me to make a transaction, imagine Persons #10-#20 check every transaction, come to the agreement of what's correct, then send a copy of the up-to-date notebook to every other person, so we all see everything adds up exactly how it should. This means if I dropped my notebook in the pool and it got ruined, I could just get a full up to date copy from someone else, and nothing would be lost.  If I was the only person with the notebook of transactions(Fight Club ending spoiler alert) and I lost that log, I'd have no way of knowing how much money anyone else has.  This is the benefit to decentralization: every party is the source of truth, so the truth can't be manipulated.

(51% attack simplification, solutions)

(incentives for keeping the ledger honest)


## What makes a cryptocurrency worth anything at all?

  You may be wondering how bits on the computer can possibly be worth anything at all.  Lets break it down using familiar examples.
  The US Dollar: a currency used to buy things in the United States.  A dollar is simply a piece of paper with some numbers on it.  What makes it worth anything more than a cryptocurrency?  You may be thinking, "isn't the dollar backed by gold?", but you'd be wrong.  It hasn't been backed by gold since [1934](https://www.federalreserve.gov/faqs/currency_12770.htm).  But for the sake of simplicity, lets pretend we took a small trip back in time.  Gold has **intrinsic value**.  It can be made into jewelry, it's conductive, so it can be used in electrical applications(such as your computer or smartphone) yet resists oxidation, unlike copper.  There is also a limited amount of gold; while you technically can make gold, the process is too expensive to make it worthwhile to sell it afterwards.  These factors contribute to why gold has value.
  But what about cryptocurrencies?  
* Are they a limited resource?

  For most cryptocurrencies, there is a limited number of "coins" in circulation at any given time.  You can't simply "create" a bitcoin and add it to your wallet, due to complex cryptography and transaction logging.  These coins are currently created by "miners"(**explain**) who form the backbone of any cyptocurrency using Proof of Work(**explain**).  Proof of Stake is a new concept that is going to be implemented into Ethereum so mining won't be necessary anymore.
  
* Do they have intrinsic value?

  Well, yes and no.  For example, Bitcoin can be seen as a "store of value", with its price being dictated by supply and demand.  The more people that think bitcoins are worth something, the more people buy into it, and consequently the price goes up.  Ethereum has intrinsic value because the blockchain provides the backbone for running "smart contracts", which can basically be a program of any kind.  You can interact with these contracts by sending Eth.  People who believe Ethereum is going to become more popular buy into it, and its price increases.
  
* Who's buying cryptocurrencies?

  People buy into cryptocurrencies for a few different reasons.
  	* They want to make money off them by purchasing them when their price is low, and selling them when the price is high.
	This is similar to playing the stock market.  Cryptocurrencies are much more volatile, and can possibly gain or lose upwards of 20% in a single day.  This makes them an ideal target for people interested in day trading them to try to out perform the market.
	* They believe in the underlying technology.
	Some people believe that cryptocurrencies are a natural progression for society.  They believe that eventually, cryptocurrencies like Bitcoin or Ethereum will be commonplace, and used for everything from paying your electricity bill to purchasing food at a restaurant.

