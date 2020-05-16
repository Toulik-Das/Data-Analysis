# Exploring the Bitcoin Cryptocurrency Market

Since the launch of Bitcoin in 2008, hundreds of similar projects based on the blockchain technology have emerged. We call these cryptocurrencies (also coins or cryptos in the Internet slang). Some are extremely valuable nowadays, and others may have the potential to become extremely valuable in the future1. In fact, on the 6th of December of 2017, Bitcoin has a market capitalization above $200 billion.
![bitcoint_market_cap_2017](https://user-images.githubusercontent.com/39211262/82115487-af3f7100-9780-11ea-8f25-eab7ac7e188e.png)

## Installation : 
 - Python
 - matplotlib
 - Pandas

##  How big is Bitcoin compared with the rest of the cryptocurrencies :
At the time of writing, Bitcoin is under serious competition from other projects, but it is still dominant in market capitalization. Let's plot the market capitalization for the top 10 coins as a barplot to better visualize this.

![Screenshot (404)](https://user-images.githubusercontent.com/39211262/82115608-6fc55480-9781-11ea-8e7a-330f529b9ea4.png)

## Making the plot easier to read and more informative :
While the plot above is informative enough, it can be improved. Bitcoin is too big, and the other coins are hard to distinguish because of this. Instead of the percentage, let's use a log10 scale of the "raw" capitalization. Plus, let's use color to group similar coins and make the plot more informative1.

For the colors rationale: bitcoin-cash and bitcoin-gold are forks of the bitcoin blockchain. Ethereum and Cardano both offer Turing Complete smart contracts. Iota and Ripple are not minable. Dash, Litecoin, and Monero get their own color.

![Screenshot (404)](https://user-images.githubusercontent.com/39211262/82115647-aac78800-9781-11ea-8042-066a0112eb10.png)

### Well, we can already see that things are a bit crazy :
It seems you can lose a lot of money quickly on cryptocurrencies. Let's plot the top 10 biggest gainers and top 10 losers in market capitalization.

![Screenshot (405)](https://user-images.githubusercontent.com/39211262/82115665-d9456300-9781-11ea-898c-61b2c94132fc.png)

### Ok, those are... interesting. Let's check the weekly Series too :
800% daily increase?! Why are we doing this tutorial and not buying random coins?

After calming down, let's reuse the function defined above to see what is going weekly instead of daily.

![Screenshot (406)](https://user-images.githubusercontent.com/39211262/82115686-0b56c500-9782-11ea-94bd-8f7523f233aa.png)

### Most coins are tiny :
Note that many coins are not comparable to large companies in market cap, so let's divert from the original Investopedia definition by merging categories.

![Screenshot (407)](https://user-images.githubusercontent.com/39211262/82115744-3ccf9080-9782-11ea-8dae-5f337a986242.png)



 

