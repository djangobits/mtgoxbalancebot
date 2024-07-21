## UPDATE 2024/07/21

On July 17, 2024 the trustee has gain moved coins. This time from 16eAGJEjqsUqngMfcysQECvp7TMU37P9gX and 16ArP3SPFJwq6X5fTZRLu2UcEAn1dXVqdF. The same day creditors who registered with Kraken as their exchange of choice to receive the payments, have received an email from the trustee confirming the "Completion of BTC/BCH Repayment". in an Email Kraken confirmed to have received the funds and forsees 7-14 days for the distribution to the creditor's accounts to be completed.

The two transactions from the trustees addresses were:  
[2493c16bb8621e4034df73b4e1b67bcae07831c72e43f1356e1e3f077c2cec8f](https://mempool.space/tx/2493c16bb8621e4034df73b4e1b67bcae07831c72e43f1356e1e3f077c2cec8f)  
[d938a3d267b9027879d58f8e3ba45e1d0bc8ab7584c38b9b3ab8df014c807f17](https://mempool.space/tx/d938a3d267b9027879d58f8e3ba45e1d0bc8ab7584c38b9b3ab8df014c807f17)  

If we check these transactions, we see both sending certain amounts to 1JbezDVd9VsK9o1Ga9UqLydeuEvhKLAPs6 which acted as intermediary address to prepare transactions before. I assume this to be an address in control of the trustee, used to prepare transactions in a safe way. From 1Jbez, 48'641.24283577 BTC were onpassed to 3JQieEzccKjFS34oW8KZSGBDndiH1YyFrE. It can be assumed that this is an address under control of Kraken. Both originating addresses did split off some change.

I am going to assume that the two new addresses which did receive the split off amounts are new change addresses from the trustee 1HRAprcXCzx1YqYv7dcCcDzf3vYVGPv3b2 and 18vjnBHWAxU4CPGPqF7Gp9JyqdVBHDct9b. 


Therefor the bot will now track these addresses, even if there is a slight risk that 1HRAp and 18vjn might not be change addresses from teh trustee.

[1HeHLv7ZRFxWUVjuWkWT2D5XFbXXvHoV68](https://mempool.space/address/1HeHLv7ZRFxWUVjuWkWT2D5XFbXXvHoV68) ‎0.00000546 BTC, initial consolidation address  
[1AsHPP7WcGnDLzxW2bUa2FcbJP3eZVEqpx](https://mempool.space/address/1AsHPP7WcGnDLzxW2bUa2FcbJP3eZVEqpx) ‎‎47'228.73330409 BTC, initial consolidation address  
[16eAGJEjqsUqngMfcysQECvp7TMU37P9gX](https://mempool.space/address/16eAGJEjqsUqngMfcysQECvp7TMU37P9gX) ‎‎0.00004786 BTC, initial consolidation address  
[16ArP3SPFJwq6X5fTZRLu2UcEAn1dXVqdF](https://mempool.space/address/16ArP3SPFJwq6X5fTZRLu2UcEAn1dXVqdF) ‎0 BTC, initial consolidation address  
[1HRAprcXCzx1YqYv7dcCcDzf3vYVGPv3b2](https://mempool.space/address/1HRAprcXCzx1YqYv7dcCcDzf3vYVGPv3b2) ‎526.95226408 BTC, Change address after Kraken transfers (jul 17)  
[18vjnBHWAxU4CPGPqF7Gp9JyqdVBHDct9b](https://mempool.space/address/18vjnBHWAxU4CPGPqF7Gp9JyqdVBHDct9b) ‎42'587.49101799 BTC, Change address after Kraken transfers (jul 17)  

### NOTE: ATTENTION ASSUMPTIONS
I did make some assumptions based on the observed transfers and the communication by the trustee as well as the users feedback in the MtGox creditors community. I could be wrong. But Arkham seems to come to teh same conclusions, see: [https://platform.arkhamintelligence.com/](https://platform.arkhamintelligence.com/)




## UPDATE 2024/07/09

On July 5th, 2024 the trustee has moved coins from 1HeHLv7ZRFxWUVjuWkWT2D5XFbXXvHoV68, while 1AsHPP7WcGnDLzxW2bUa2FcbJP3eZVEqpx and 16eAGJEjqsUqngMfcysQECvp7TMU37P9gX remained untouched. This is the corresponding transaction: [https://mempool.space/tx/f95aa78a405007e702e6bb69732e3bbe7a0b3de75dc6e7b9b0dcc85e5e597c8e](f95aa78a405007e702e6bb69732e3bbe7a0b3de75dc6e7b9b0dcc85e5e597c8e)

The full balance of 1HeHLv7ZRFxWUVjuWkWT2D5XFbXXvHoV68 was moved, ‎2'701.78112302 BTC was split off and was sent to 16ArP3SPFJwq6X5fTZRLu2UcEAn1dXVqdF and to 1JbezDVd9VsK9o1Ga9UqLydeuEvhKLAPs6 from where it was split again and moved to bc1qkjcuq5hgqd3y735vxl52htd2ja9xvyv8cq3gllhpwp23c3d7tdyq2ug68h and 1PKGGMh5cGYMMJq32aVY8gfCzsmUiszwzV, see transaction here: [https://mempool.space/tx/3a0672bb5b831b886aaff6e276dcfeadeb8256ec4124c40ef50002cfe2f599f7](3a0672bb5b831b886aaff6e276dcfeadeb8256ec4124c40ef50002cfe2f599f7).

On the same day, the trustee published this: [https://www.mtgox.com/img/pdf/20240705_01_announcement_en.pdf](https://www.mtgox.com/img/pdf/20240705_01_announcement_en.pdf) where he declares having started to distribute Bitcoin and Bitcoin Cash "to some of the rehabilitation creditors". Also the same day, reports popped up of users of SBI VCTRADE and [https://www.reddit.com/r/mtgoxinsolvency/comments/1dvryt9/coins_credited_into_my_account/](Bitbank) on Telegram an reddit. We can assume that the 2,701.78112302 BTC were sent to these two exchanges to refund creditors.

We can also assume that the remaining ‎44'526.95228894 BTC sitting now sitting on [https://mempool.space/address/16ArP3SPFJwq6X5fTZRLu2UcEAn1dXVqdF](16ArP3SPFJwq6X5fTZRLu2UcEAn1dXVqdF) is still under the trustee's control. Therefor it was added to the mtgoxbalancebot.

Addresses monitored by mtgoxbalancebot on July 9, 2024:  
[1HeHLv7ZRFxWUVjuWkWT2D5XFbXXvHoV68](https://mempool.space/address/1HeHLv7ZRFxWUVjuWkWT2D5XFbXXvHoV68) 	‎0.00000546 BTC  
[1AsHPP7WcGnDLzxW2bUa2FcbJP3eZVEqpx](https://mempool.space/address/1AsHPP7WcGnDLzxW2bUa2FcbJP3eZVEqpx) ‎47'228.73329863 BTC  
[16eAGJEjqsUqngMfcysQECvp7TMU37P9gX](https://mempool.space/address/16eAGJEjqsUqngMfcysQECvp7TMU37P9gX) ‎47'228.73385638 BTC  
[16ArP3SPFJwq6X5fTZRLu2UcEAn1dXVqdF](https://mempool.space/address/16ArP3SPFJwq6X5fTZRLu2UcEAn1dXVqdF) ‎44'526.95228894 BTC  

Total: 138'984.41944941 BTC

BCH also moved and 2'701.75561618 BCH were split of in a similar fashion. The remaining BCH sit in one address. Transaction here: [https://www.blockchain.com/explorer/transactions/bch/d213dd13f3155d347592bae277af22385f9214c435bfedc189e28788af12a1a5](d213dd13f3155d347592bae277af22385f9214c435bfedc189e28788af12a1a5)


## UPDATE 2024/06/04

On May 30, 2024 the trustee has consolidated all BTC in 3 addresses and all BCH in one address and published this message:

[https://www.mtgox.com/img/pdf/20240528_announcement_en.pdf](https://www.mtgox.com/img/pdf/20240528_announcement_en.pdf)


#### BTC
[1AsHPP7WcGnDLzxW2bUa2FcbJP3eZVEqpx](https://mempool.space/address/1AsHPP7WcGnDLzxW2bUa2FcbJP3eZVEqpx), ‎47'228.73311546 BTC  
[1HeHLv7ZRFxWUVjuWkWT2D5XFbXXvHoV68](https://mempool.space/address/1HeHLv7ZRFxWUVjuWkWT2D5XFbXXvHoV68), 47'228.73385092 BTC  
[16eAGJEjqsUqngMfcysQECvp7TMU37P9gX](https://mempool.space/address/16eAGJEjqsUqngMfcysQECvp7TMU37P9gX), 47'228.73385092 BTC  

Total: 141'686.2008173 BTC

#### BCH
[qqprdmqf4yc2cvrk9jmqp6luxwpp7wr98ulgshyeah](https://www.blockchain.com/explorer/addresses/BCH/qqprdmqf4yc2cvrk9jmqp6luxwpp7wr98ulgshyeah)

Total: 142'846.01000000 BCH  

BSV has not been consolidated, and sits on the known addresses.


## About the bot

The twitter bot [@MtGoxBalanceBot](https://twitter.com/mtgoxbalancebot) observes the current balances and outgoing transactions on all known MtGox BTC addresses supposedly held by the MtGox trustee. 

Outgoing transactions are also tracked and will result in a tweet containing the address and amount sent. 

This bot builds on public APIs and services from blockchain.info, cryptocurrencyalerting.com and make.com. Please note, all of these services can fail, be delayed or might undergo changes which break the bot. Always verify the output yourself.

The addresses observed have been identified by Kim Nilsson ([@nikuhodai](https://twitter.com/nikuhodai)) of WizSecurity ([@wizsecurity](https://twitter.com/wizsecurity)). The list was published in this [reddit comment](https://www.reddit.com/r/mtgoxinsolvency/comments/82m0dl/comment/dvd2vre/). Please follow Kim and WizSecurity on Twitter and check out his blog at [wizsec.com](https://blog.wizsec.jp/), he has excellent content, not only MtGox related. Also, please consider a donation to the BTC address on the bottom of his blog site.

## Note

An outgoing transaction from one of these addresses does not necessarily mean these coins will be distributed or sold shortly after. It just means they are being moved. Might also be reorganisation in preparation of distribution. Don't jump to conclusions too quick.


## Made by

This bot was stitched together by [@djangobits](https://twitter.com/djangobits), a longtime crypto enthusiast and MtGox creditor. If you think this bot is useful, then please consider a BTC donation to 1PHSzi84dPmRD6pbiaJpivQX9S6BuRo9rZ. Current cost for the bot is 29$ per month. 

## Frequently asked questions about MtGox coins

### What balances is the trustee currently holding)?
As declared in documents published during creditors meetings ([document here](http://www.mtgox.com/img/pdf/20191001_report.pdf)), the trustee currently (2022/09/21) holds ***141,686.35371099 BTC (Bitcoin)*** and ***142,846.35166254 BCH (Bitcoin Cash)*** as well as 69'776'002'441 JPY (483’512’808 USD) from BTC sales in 2018 and MtGox bank accounts. The trustee also has a similar amount of BSV (Bitcoin Shitty Version) on the same addresses, but according to the Rehabilitation Plan, all other forks except BCH will be dumped, which would include BSV.

### Will the trustee dump all crypto holdings for fiat?
No. Creditors will be able to select, if they want their share to be paid in crypto or in fiat. If they select crypto, they can claim them with the exchange designated by the trustee. If they select fiat, the trustee or the designated exchange will probably sell those coins and payout fiat. We have no information if this will be done on the open market or OTC.

### When will the MtGox coins be released?
Nobody (maybe except the trustee) currently (2024/01/02) knows. On September 15, 2022, the ***Setting of Assignment, etc. Restriction Reference Period*** started as announced [here](http://www.mtgox.com/img/pdf/20220831_announcement_en.pdf). A previous deadline of End of October 2023 for ELSP (Early Lump Sum repayments) and IP (Intermediate Repayments) was pushed back to End of October 2024.

### OK. But when MtGox coins?
What we know is that ***some things need to happen before any fiat or crypto payments from the trustee can be expected*** (a ticked checkbox indicates if this was already done): 

- [x]  All creditors will need to go through KYC with the trustee
- [x]  The Trustee has to inform creditors about the "Intermediate Repayment" option which would allow those creditors who will choose the "Final Payment" (FP) option (in contrast to the "Early Lump Sum Payment" (ELSP) option), to receive something together with those who have chosen ELSP.
- [x]  Creditors need to select ELSP or FP in "The System"
- [x]  Creditors need to select payout in crypto or fiat in "The System" (the trustee already asked about this, but only as an opinion poll, not as a binding decision)
- [x]  In order to receive the fiat payments all creditors are entitled to, bank account info has to be collected in "The System"
- [x]  The trustee needs to inform about the exchanges / agents he selected for the distribution of crypto
- [x]  Creditors need to register with these exchanges and probably go through KYC again (assuming that KYC data won't be passed from the trustee to the exchange.
- [ ]  Coins need to move to the designated exchanges

The latest deadline set by the trustee to repay all creditors who selected ELSP (Early Lump Sum Repayments) and to send Intermedia Payments to those who selected Final repayment (FP), is end of October 2024. A previous deadline of October 2023 was pushed back as announced [here](https://www.mtgox.com/img/pdf/20230921_announcement_en.pdf). The trustee has a history of delaying and not respecting his self-imposed deadlines. The truth is that nobody knows when crypto payments will happen.

### Will all crypto holdings be released at once?
No. There will be three phases with bigger releases (while the order and size cannot be known yet): 

- A) When the trustee or the designated exchange sell the BTC of those who selected fiat payments. 
- B) The distribution to those who selected ELSP and Intermediate Repayments. 
- C) The distribution of the Final Payment. 

Those creditors who choose the "Final Payment" option will most likely get their last portion once pending ligitation (eg. by Coinlab) is resolved. These creditors will be able to get an early crypto payment through the "Intermediate Repayment", which should happen together with the "Early Lump Sum Payments". It's unknown how many creditors selected fiat payments of their crypto holdings. It's also unknown how many selected ELSP or FP.

Additionally, the exchanges which will be used to transfer the crypto, annouced that they will need between two weeks and 90 days to process the payments. This makes it very unlikely for big amounts to be released on a single day.

### Will MtGox creditors sell all their coins, once they get them?
We don't know. But imagine you were a creditor, seeing BTC going to 69k$ in 2021, would you then sell them below 50k$ in 2024? Those creditors in urgent need of money had the occasion to sell their claims to claim buyers and some already did. In an informal vote in a telegram group of creditors, more than 62% of 327 creditors indicated they won't sell any of their crypto once they get it. Only 16% indicated they would sell it all. Some said they would even buy more for the fiat portion they will receive from the trustee. While this is all anectotal, it seems obvious to me that most creditors, which are crypto OGs, won't sell all at once.

### What was this story about Paypal and bank payments? Does the MtGox trustee dump it all and repay in fiat?
Nope. All creditors are entitled to some fiat payments. Only a minority of creditors are expected to have selected fiat instead of crypto repayments and only a minority are fiat-only creditors. These fiat payments are done by bank transfers or by Paypal, for those who preferred that option. At the end of 2023, some hundred creditors reported they received fiat payments via Paypal between a couple of hundreds of USD to up to USD 10k USD. Also some japanese creditors reported to have received fiat bank transfers. International wire transfers have not been reported at the end of 2023.  

### Who are the biggest MtGox creditors?
The biggest creditors are the claim buyers from Fortress (Michael Hourigan), Capital 507 (Thomas Braziel) and Bitcoinbuilder (Josh Jones). We know that Bitcoinbuilder selected ELSP and their users will be paid through BitGo where tehy needed to register according to bitcoinbuilder.com.

### What does it mean wthen the bot shows a negative amount that was transferred out?
Then that amount was transferred in. Sometimes funny people send tiny amounts to some of the addresses. The bot reports that with a negative amount "being transferred out". 

### Questions?
If you have questions, remarks or corrections, please let me know via Twitter,
Sincerly yours,
[@djangobits](https://twitter.com/djangobits)


### Appendix 1 - List of all known addresses used by the MtGox trustee

Links lead to block explorers of BTC, BCH and BSV

#### addresses added after 2024/05/30

##### BTC
[1AsHPP7WcGnDLzxW2bUa2FcbJP3eZVEqpx](https://mempool.space/address/1AsHPP7WcGnDLzxW2bUa2FcbJP3eZVEqpx), ‎47'228.73311546 BTC  
[1HeHLv7ZRFxWUVjuWkWT2D5XFbXXvHoV68](https://mempool.space/address/1HeHLv7ZRFxWUVjuWkWT2D5XFbXXvHoV68), 47'228.73385092 BTC  
[16eAGJEjqsUqngMfcysQECvp7TMU37P9gX](https://mempool.space/address/16eAGJEjqsUqngMfcysQECvp7TMU37P9gX), 47'228.73385092 BTC  

##### BCH
[qqprdmqf4yc2cvrk9jmqp6luxwpp7wr98ulgshyeah](https://www.blockchain.com/explorer/addresses/BCH/qqprdmqf4yc2cvrk9jmqp6luxwpp7wr98ulgshyeah)

#### addresses which existed before 2024/05/30

12KkeeRkiNS13GMbg7zos9KRn9ggvZtZgx [BTC](https://blockchair.com/bitcoin/address/12KkeeRkiNS13GMbg7zos9KRn9ggvZtZgx) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/12KkeeRkiNS13GMbg7zos9KRn9ggvZtZgx) [BSV](https://whatsonchain.com/address/12KkeeRkiNS13GMbg7zos9KRn9ggvZtZgx)  
12T4oSNd4t9ty9fodgNd47TWhK35pAxDYN [BTC](https://blockchair.com/bitcoin/address/12T4oSNd4t9ty9fodgNd47TWhK35pAxDYN) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/12T4oSNd4t9ty9fodgNd47TWhK35pAxDYN) [BSV](https://whatsonchain.com/address/12T4oSNd4t9ty9fodgNd47TWhK35pAxDYN)  
13ahgw8sM95EDbugT3tdb8TYoMU46Uw7PX [BTC](https://blockchair.com/bitcoin/address/13ahgw8sM95EDbugT3tdb8TYoMU46Uw7PX) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/13ahgw8sM95EDbugT3tdb8TYoMU46Uw7PX) [BSV](https://whatsonchain.com/address/13ahgw8sM95EDbugT3tdb8TYoMU46Uw7PX)  
13dXFMyG22EsUsvaWhCqUo7SXuX7rBPog6 [BTC](https://blockchair.com/bitcoin/address/13dXFMyG22EsUsvaWhCqUo7SXuX7rBPog6) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/13dXFMyG22EsUsvaWhCqUo7SXuX7rBPog6) [BSV](https://whatsonchain.com/address/13dXFMyG22EsUsvaWhCqUo7SXuX7rBPog6)  
13sXfpp2V16nnxYvW9FHHoBdMa3k98uJw8 [BTC](https://blockchair.com/bitcoin/address/13sXfpp2V16nnxYvW9FHHoBdMa3k98uJw8) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/13sXfpp2V16nnxYvW9FHHoBdMa3k98uJw8) [BSV](https://whatsonchain.com/address/13sXfpp2V16nnxYvW9FHHoBdMa3k98uJw8)  
13xGCc4TPSYY9GYxBGVNox82KxyjkFnxMX [BTC](https://blockchair.com/bitcoin/address/13xGCc4TPSYY9GYxBGVNox82KxyjkFnxMX) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/13xGCc4TPSYY9GYxBGVNox82KxyjkFnxMX) [BSV](https://whatsonchain.com/address/13xGCc4TPSYY9GYxBGVNox82KxyjkFnxMX)  
1439q4Na8v88kPBqoyg8F4ueL9SYr8ANWj [BTC](https://blockchair.com/bitcoin/address/1439q4Na8v88kPBqoyg8F4ueL9SYr8ANWj) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1439q4Na8v88kPBqoyg8F4ueL9SYr8ANWj) [BSV](https://whatsonchain.com/address/1439q4Na8v88kPBqoyg8F4ueL9SYr8ANWj)  
14mP6caC5dFhHdVAPCjPKM8Nm36MBDR5pM [BTC](https://blockchair.com/bitcoin/address/14mP6caC5dFhHdVAPCjPKM8Nm36MBDR5pM) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/14mP6caC5dFhHdVAPCjPKM8Nm36MBDR5pM) [BSV](https://whatsonchain.com/address/14mP6caC5dFhHdVAPCjPKM8Nm36MBDR5pM)  
14p4w3TRCd6NMRSnzTmgdvQhNnbrAmzXmy [BTC](https://blockchair.com/bitcoin/address/14p4w3TRCd6NMRSnzTmgdvQhNnbrAmzXmy) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/14p4w3TRCd6NMRSnzTmgdvQhNnbrAmzXmy) [BSV](https://whatsonchain.com/address/14p4w3TRCd6NMRSnzTmgdvQhNnbrAmzXmy)  
14USZ558Rr28AZwdJQyciSQkN4JT1cEoj2 [BTC](https://blockchair.com/bitcoin/address/14USZ558Rr28AZwdJQyciSQkN4JT1cEoj2) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/14USZ558Rr28AZwdJQyciSQkN4JT1cEoj2) [BSV](https://whatsonchain.com/address/14USZ558Rr28AZwdJQyciSQkN4JT1cEoj2)  
155FsTtEFq4eGCcBxDseuwLKPbmtWbyHJR [BTC](https://blockchair.com/bitcoin/address/155FsTtEFq4eGCcBxDseuwLKPbmtWbyHJR) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/155FsTtEFq4eGCcBxDseuwLKPbmtWbyHJR) [BSV](https://whatsonchain.com/address/155FsTtEFq4eGCcBxDseuwLKPbmtWbyHJR)  
156HpsWfgkWYLT63uhTAGUSUF3ZMnB9WWj [BTC](https://blockchair.com/bitcoin/address/156HpsWfgkWYLT63uhTAGUSUF3ZMnB9WWj) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/156HpsWfgkWYLT63uhTAGUSUF3ZMnB9WWj) [BSV](https://whatsonchain.com/address/156HpsWfgkWYLT63uhTAGUSUF3ZMnB9WWj)  
15kNZcrhxeFZgVVLK2Yjzd69tRidbFdJEZ [BTC](https://blockchair.com/bitcoin/address/15kNZcrhxeFZgVVLK2Yjzd69tRidbFdJEZ) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/15kNZcrhxeFZgVVLK2Yjzd69tRidbFdJEZ) [BSV](https://whatsonchain.com/address/15kNZcrhxeFZgVVLK2Yjzd69tRidbFdJEZ)  
15QcKCa84ZCHxbsqXDoKhi5XbmQB8jPEAd [BTC](https://blockchair.com/bitcoin/address/15QcKCa84ZCHxbsqXDoKhi5XbmQB8jPEAd) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/15QcKCa84ZCHxbsqXDoKhi5XbmQB8jPEAd) [BSV](https://whatsonchain.com/address/15QcKCa84ZCHxbsqXDoKhi5XbmQB8jPEAd)  
15SeCwVCFx5cWyrcdD1Zp1D1zxjH2SELPg [BTC](https://blockchair.com/bitcoin/address/15SeCwVCFx5cWyrcdD1Zp1D1zxjH2SELPg) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/15SeCwVCFx5cWyrcdD1Zp1D1zxjH2SELPg) [BSV](https://whatsonchain.com/address/15SeCwVCFx5cWyrcdD1Zp1D1zxjH2SELPg)  
15U4VsmWG1cdXAtizvQsW4r7iMxzp64Tgu [BTC](https://blockchair.com/bitcoin/address/15U4VsmWG1cdXAtizvQsW4r7iMxzp64Tgu) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/15U4VsmWG1cdXAtizvQsW4r7iMxzp64Tgu) [BSV](https://whatsonchain.com/address/15U4VsmWG1cdXAtizvQsW4r7iMxzp64Tgu)  
16jZZkMYqjUWUtQ9DfDvHdH5ko5BcnH9XQ [BTC](https://blockchair.com/bitcoin/address/16jZZkMYqjUWUtQ9DfDvHdH5ko5BcnH9XQ) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/16jZZkMYqjUWUtQ9DfDvHdH5ko5BcnH9XQ) [BSV](https://whatsonchain.com/address/16jZZkMYqjUWUtQ9DfDvHdH5ko5BcnH9XQ)  
16W4XcUAKPmSES9MiUCio28msSCp8rDZgs [BTC](https://blockchair.com/bitcoin/address/16W4XcUAKPmSES9MiUCio28msSCp8rDZgs) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/16W4XcUAKPmSES9MiUCio28msSCp8rDZgs) [BSV](https://whatsonchain.com/address/16W4XcUAKPmSES9MiUCio28msSCp8rDZgs)  
16w6sZBDP58yyeyZAcvnxcEGJpwR9amM6g [BTC](https://blockchair.com/bitcoin/address/16w6sZBDP58yyeyZAcvnxcEGJpwR9amM6g) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/16w6sZBDP58yyeyZAcvnxcEGJpwR9amM6g) [BSV](https://whatsonchain.com/address/16w6sZBDP58yyeyZAcvnxcEGJpwR9amM6g)  
17etv2L3nhk6SCcWSNW4eoZkBy84izAm17 [BTC](https://blockchair.com/bitcoin/address/17etv2L3nhk6SCcWSNW4eoZkBy84izAm17) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/17etv2L3nhk6SCcWSNW4eoZkBy84izAm17) [BSV](https://whatsonchain.com/address/17etv2L3nhk6SCcWSNW4eoZkBy84izAm17)  
17KcBp8g76Ue8pywgjta4q8Ds6wK4bEKp7 [BTC](https://blockchair.com/bitcoin/address/17KcBp8g76Ue8pywgjta4q8Ds6wK4bEKp7) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/17KcBp8g76Ue8pywgjta4q8Ds6wK4bEKp7) [BSV](https://whatsonchain.com/address/17KcBp8g76Ue8pywgjta4q8Ds6wK4bEKp7)  
17Tf4bVQaCzwWrDWGRPC97RLCHnU4LY8Qr [BTC](https://blockchair.com/bitcoin/address/17Tf4bVQaCzwWrDWGRPC97RLCHnU4LY8Qr) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/17Tf4bVQaCzwWrDWGRPC97RLCHnU4LY8Qr) [BSV](https://whatsonchain.com/address/17Tf4bVQaCzwWrDWGRPC97RLCHnU4LY8Qr)  
18hcZVFPqDNAovJmb9vA6hEJrDz6uWXNGh [BTC](https://blockchair.com/bitcoin/address/18hcZVFPqDNAovJmb9vA6hEJrDz6uWXNGh) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/18hcZVFPqDNAovJmb9vA6hEJrDz6uWXNGh) [BSV](https://whatsonchain.com/address/18hcZVFPqDNAovJmb9vA6hEJrDz6uWXNGh)  
18KDS3q6a4YV9Nn8jcyMvNoVPfcrfemeag [BTC](https://blockchair.com/bitcoin/address/18KDS3q6a4YV9Nn8jcyMvNoVPfcrfemeag) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/18KDS3q6a4YV9Nn8jcyMvNoVPfcrfemeag) [BSV](https://whatsonchain.com/address/18KDS3q6a4YV9Nn8jcyMvNoVPfcrfemeag)  
18M1Z337NqLtK9V69bssnQUYsvb7hmfSFS [BTC](https://blockchair.com/bitcoin/address/18M1Z337NqLtK9V69bssnQUYsvb7hmfSFS) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/18M1Z337NqLtK9V69bssnQUYsvb7hmfSFS) [BSV](https://whatsonchain.com/address/18M1Z337NqLtK9V69bssnQUYsvb7hmfSFS)  
18ok25NTkdrUzdByFJCNVsqVYkujZ8aP45 [BTC](https://blockchair.com/bitcoin/address/18ok25NTkdrUzdByFJCNVsqVYkujZ8aP45) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/18ok25NTkdrUzdByFJCNVsqVYkujZ8aP45) [BSV](https://whatsonchain.com/address/18ok25NTkdrUzdByFJCNVsqVYkujZ8aP45)  
18YDgRhxsomuBZ1g9d8Y1JuRmxDhF8Bvff [BTC](https://blockchair.com/bitcoin/address/18YDgRhxsomuBZ1g9d8Y1JuRmxDhF8Bvff) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/18YDgRhxsomuBZ1g9d8Y1JuRmxDhF8Bvff) [BSV](https://whatsonchain.com/address/18YDgRhxsomuBZ1g9d8Y1JuRmxDhF8Bvff)  
195HvmjXgoF3M5vFaBC8swZPhwrE7VhxRD [BTC](https://blockchair.com/bitcoin/address/195HvmjXgoF3M5vFaBC8swZPhwrE7VhxRD) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/195HvmjXgoF3M5vFaBC8swZPhwrE7VhxRD) [BSV](https://whatsonchain.com/address/195HvmjXgoF3M5vFaBC8swZPhwrE7VhxRD)  
199Yxz2TJGtND3QKsHTptTJivqSaUZBvku [BTC](https://blockchair.com/bitcoin/address/199Yxz2TJGtND3QKsHTptTJivqSaUZBvku) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/199Yxz2TJGtND3QKsHTptTJivqSaUZBvku) [BSV](https://whatsonchain.com/address/199Yxz2TJGtND3QKsHTptTJivqSaUZBvku)  
19c8sUa54yQuRTVDfJa3iDkkCaFkzBJLPB [BTC](https://blockchair.com/bitcoin/address/19c8sUa54yQuRTVDfJa3iDkkCaFkzBJLPB) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/19c8sUa54yQuRTVDfJa3iDkkCaFkzBJLPB) [BSV](https://whatsonchain.com/address/19c8sUa54yQuRTVDfJa3iDkkCaFkzBJLPB)  
19Cr4zXpKw43xLJhFZW9iv4DDNtQk2TDeB [BTC](https://blockchair.com/bitcoin/address/19Cr4zXpKw43xLJhFZW9iv4DDNtQk2TDeB) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/19Cr4zXpKw43xLJhFZW9iv4DDNtQk2TDeB) [BSV](https://whatsonchain.com/address/19Cr4zXpKw43xLJhFZW9iv4DDNtQk2TDeB)  
19eihBKk6e5YD2QXAe4SVUsxRLLnTDKsfv [BTC](https://blockchair.com/bitcoin/address/19eihBKk6e5YD2QXAe4SVUsxRLLnTDKsfv) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/19eihBKk6e5YD2QXAe4SVUsxRLLnTDKsfv) [BSV](https://whatsonchain.com/address/19eihBKk6e5YD2QXAe4SVUsxRLLnTDKsfv)  
19KiFrafXEyJCUDYFEv3B6tBUwyfFo7kNU [BTC](https://blockchair.com/bitcoin/address/19KiFrafXEyJCUDYFEv3B6tBUwyfFo7kNU) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/19KiFrafXEyJCUDYFEv3B6tBUwyfFo7kNU) [BSV](https://whatsonchain.com/address/19KiFrafXEyJCUDYFEv3B6tBUwyfFo7kNU)  
1Ar6meJQCkNoC9wnPcyRNNpzX5fBDaGcKd [BTC](https://blockchair.com/bitcoin/address/1Ar6meJQCkNoC9wnPcyRNNpzX5fBDaGcKd) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1Ar6meJQCkNoC9wnPcyRNNpzX5fBDaGcKd) [BSV](https://whatsonchain.com/address/1Ar6meJQCkNoC9wnPcyRNNpzX5fBDaGcKd)  
1AZu7TQmKBAes2duNDctYwjAB9nhHczUnA [BTC](https://blockchair.com/bitcoin/address/1AZu7TQmKBAes2duNDctYwjAB9nhHczUnA) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1AZu7TQmKBAes2duNDctYwjAB9nhHczUnA) [BSV](https://whatsonchain.com/address/1AZu7TQmKBAes2duNDctYwjAB9nhHczUnA)  
1B6kJM75iu5ty1HAHMMz6tT1HhjoGNTCa9 [BTC](https://blockchair.com/bitcoin/address/1B6kJM75iu5ty1HAHMMz6tT1HhjoGNTCa9) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1B6kJM75iu5ty1HAHMMz6tT1HhjoGNTCa9) [BSV](https://whatsonchain.com/address/1B6kJM75iu5ty1HAHMMz6tT1HhjoGNTCa9)  
1BDZBTb4KE5oq6wAgA6EvAe3uCFRrAbPao [BTC](https://blockchair.com/bitcoin/address/1BDZBTb4KE5oq6wAgA6EvAe3uCFRrAbPao) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1BDZBTb4KE5oq6wAgA6EvAe3uCFRrAbPao) [BSV](https://whatsonchain.com/address/1BDZBTb4KE5oq6wAgA6EvAe3uCFRrAbPao)  
1BXyJc6BVuTFnHQCcjiWX2xmCPNVfaSZeb [BTC](https://blockchair.com/bitcoin/address/1BXyJc6BVuTFnHQCcjiWX2xmCPNVfaSZeb) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1BXyJc6BVuTFnHQCcjiWX2xmCPNVfaSZeb) [BSV](https://whatsonchain.com/address/1BXyJc6BVuTFnHQCcjiWX2xmCPNVfaSZeb)  
1BzK87zuqidZn489Wb2oLSktrjKrX7TLKe [BTC](https://blockchair.com/bitcoin/address/1BzK87zuqidZn489Wb2oLSktrjKrX7TLKe) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1BzK87zuqidZn489Wb2oLSktrjKrX7TLKe) [BSV](https://whatsonchain.com/address/1BzK87zuqidZn489Wb2oLSktrjKrX7TLKe)  
1C5aU4Xnpd3txbxehk46UZgiuNB8QdpHCH [BTC](https://blockchair.com/bitcoin/address/1C5aU4Xnpd3txbxehk46UZgiuNB8QdpHCH) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1C5aU4Xnpd3txbxehk46UZgiuNB8QdpHCH) [BSV](https://whatsonchain.com/address/1C5aU4Xnpd3txbxehk46UZgiuNB8QdpHCH)  
1CRjKZJu8LvTutnSKq4zTJ4yiqrzMAArYW [BTC](https://blockchair.com/bitcoin/address/1CRjKZJu8LvTutnSKq4zTJ4yiqrzMAArYW) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1CRjKZJu8LvTutnSKq4zTJ4yiqrzMAArYW) [BSV](https://whatsonchain.com/address/1CRjKZJu8LvTutnSKq4zTJ4yiqrzMAArYW)  
1CZsoJfkknbnW5fKrt1oR7N1ALE5WmDGP1 [BTC](https://blockchair.com/bitcoin/address/1CZsoJfkknbnW5fKrt1oR7N1ALE5WmDGP1) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1CZsoJfkknbnW5fKrt1oR7N1ALE5WmDGP1) [BSV](https://whatsonchain.com/address/1CZsoJfkknbnW5fKrt1oR7N1ALE5WmDGP1)  
1DedUxzgwErg4ipNi988wPgLk5thwciKcc [BTC](https://blockchair.com/bitcoin/address/1DedUxzgwErg4ipNi988wPgLk5thwciKcc) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1DedUxzgwErg4ipNi988wPgLk5thwciKcc) [BSV](https://whatsonchain.com/address/1DedUxzgwErg4ipNi988wPgLk5thwciKcc)  
1Drshi4RAuvxk4T6Bkq959ZvLbvy7b1wvD [BTC](https://blockchair.com/bitcoin/address/1Drshi4RAuvxk4T6Bkq959ZvLbvy7b1wvD) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1Drshi4RAuvxk4T6Bkq959ZvLbvy7b1wvD) [BSV](https://whatsonchain.com/address/1Drshi4RAuvxk4T6Bkq959ZvLbvy7b1wvD)  
1EiiKCCnFgHjEvPZdu29qqgdBm8zTvpU3U [BTC](https://blockchair.com/bitcoin/address/1EiiKCCnFgHjEvPZdu29qqgdBm8zTvpU3U) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1EiiKCCnFgHjEvPZdu29qqgdBm8zTvpU3U) [BSV](https://whatsonchain.com/address/1EiiKCCnFgHjEvPZdu29qqgdBm8zTvpU3U)  
1EK8vW7UYaYHKiW4TZmYJKtwcZLM14VjvP [BTC](https://blockchair.com/bitcoin/address/1EK8vW7UYaYHKiW4TZmYJKtwcZLM14VjvP) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1EK8vW7UYaYHKiW4TZmYJKtwcZLM14VjvP) [BSV](https://whatsonchain.com/address/1EK8vW7UYaYHKiW4TZmYJKtwcZLM14VjvP)  
1FhRuUkk8Bfx8FJDemtxhKAR4F8GCNKrXG [BTC](https://blockchair.com/bitcoin/address/1FhRuUkk8Bfx8FJDemtxhKAR4F8GCNKrXG) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1FhRuUkk8Bfx8FJDemtxhKAR4F8GCNKrXG) [BSV](https://whatsonchain.com/address/1FhRuUkk8Bfx8FJDemtxhKAR4F8GCNKrXG)  
1FrV9hv1AW34BGJvobJatyzUWYDWB9epRW [BTC](https://blockchair.com/bitcoin/address/1FrV9hv1AW34BGJvobJatyzUWYDWB9epRW) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1FrV9hv1AW34BGJvobJatyzUWYDWB9epRW) [BSV](https://whatsonchain.com/address/1FrV9hv1AW34BGJvobJatyzUWYDWB9epRW)  
1Fu4YgM3Y9CxvioGPqkSzkydAC8MVaPN1D [BTC](https://blockchair.com/bitcoin/address/1Fu4YgM3Y9CxvioGPqkSzkydAC8MVaPN1D) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1Fu4YgM3Y9CxvioGPqkSzkydAC8MVaPN1D) [BSV](https://whatsonchain.com/address/1Fu4YgM3Y9CxvioGPqkSzkydAC8MVaPN1D)  
1G23Uzwj55k2A9TRwaTknqGav66oDTkWCu [BTC](https://blockchair.com/bitcoin/address/1G23Uzwj55k2A9TRwaTknqGav66oDTkWCu) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1G23Uzwj55k2A9TRwaTknqGav66oDTkWCu) [BSV](https://whatsonchain.com/address/1G23Uzwj55k2A9TRwaTknqGav66oDTkWCu)  
1GkZQcDy8V6pmHFZqUBUBCnN9dc2hoWasD [BTC](https://blockchair.com/bitcoin/address/1GkZQcDy8V6pmHFZqUBUBCnN9dc2hoWasD) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1GkZQcDy8V6pmHFZqUBUBCnN9dc2hoWasD) [BSV](https://whatsonchain.com/address/1GkZQcDy8V6pmHFZqUBUBCnN9dc2hoWasD)  
1GyDutntMuYyA2vQGW5HFcKLfx4cbDdbJq [BTC](https://blockchair.com/bitcoin/address/1GyDutntMuYyA2vQGW5HFcKLfx4cbDdbJq) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1GyDutntMuYyA2vQGW5HFcKLfx4cbDdbJq) [BSV](https://whatsonchain.com/address/1GyDutntMuYyA2vQGW5HFcKLfx4cbDdbJq)  
1H4K3dGfNbAN4AUfyUrpkGpjrd83sntDpV [BTC](https://blockchair.com/bitcoin/address/1H4K3dGfNbAN4AUfyUrpkGpjrd83sntDpV) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1H4K3dGfNbAN4AUfyUrpkGpjrd83sntDpV) [BSV](https://whatsonchain.com/address/1H4K3dGfNbAN4AUfyUrpkGpjrd83sntDpV)  
1Hb8DmmvvtTYv5RBLuGtDxznkZwVpd5Vjy [BTC](https://blockchair.com/bitcoin/address/1Hb8DmmvvtTYv5RBLuGtDxznkZwVpd5Vjy) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1Hb8DmmvvtTYv5RBLuGtDxznkZwVpd5Vjy) [BSV](https://whatsonchain.com/address/1Hb8DmmvvtTYv5RBLuGtDxznkZwVpd5Vjy)  
1HdKXsNQtzDcfB6PGM7DWTgX9vhBWsz1ak [BTC](https://blockchair.com/bitcoin/address/1HdKXsNQtzDcfB6PGM7DWTgX9vhBWsz1ak) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1HdKXsNQtzDcfB6PGM7DWTgX9vhBWsz1ak) [BSV](https://whatsonchain.com/address/1HdKXsNQtzDcfB6PGM7DWTgX9vhBWsz1ak)  
1Hm6XDmhKCHz68wDEYTapN9MEanke8iwUk [BTC](https://blockchair.com/bitcoin/address/1Hm6XDmhKCHz68wDEYTapN9MEanke8iwUk) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1Hm6XDmhKCHz68wDEYTapN9MEanke8iwUk) [BSV](https://whatsonchain.com/address/1Hm6XDmhKCHz68wDEYTapN9MEanke8iwUk)  
1HuPVqz2xvf1rdNFUqd62vRTyxP3jeX9Ch [BTC](https://blockchair.com/bitcoin/address/1HuPVqz2xvf1rdNFUqd62vRTyxP3jeX9Ch) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1HuPVqz2xvf1rdNFUqd62vRTyxP3jeX9Ch) [BSV](https://whatsonchain.com/address/1HuPVqz2xvf1rdNFUqd62vRTyxP3jeX9Ch)  
1HweN9p41BY2RBunsPqyVuheEq7gVoxA9u [BTC](https://blockchair.com/bitcoin/address/1HweN9p41BY2RBunsPqyVuheEq7gVoxA9u) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1HweN9p41BY2RBunsPqyVuheEq7gVoxA9u) [BSV](https://whatsonchain.com/address/1HweN9p41BY2RBunsPqyVuheEq7gVoxA9u)  
1HX4s3JeFU3x1eQgPNQVAdx6FoCtbb1hr8 [BTC](https://blockchair.com/bitcoin/address/1HX4s3JeFU3x1eQgPNQVAdx6FoCtbb1hr8) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1HX4s3JeFU3x1eQgPNQVAdx6FoCtbb1hr8) [BSV](https://whatsonchain.com/address/1HX4s3JeFU3x1eQgPNQVAdx6FoCtbb1hr8)  
1HzEPuenagLEWj68igDXBBXrzc293RuR5V [BTC](https://blockchair.com/bitcoin/address/1HzEPuenagLEWj68igDXBBXrzc293RuR5V) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1HzEPuenagLEWj68igDXBBXrzc293RuR5V) [BSV](https://whatsonchain.com/address/1HzEPuenagLEWj68igDXBBXrzc293RuR5V)  
1JtgU6Uo1RAt5eiMf34EehyatUezBQP36C [BTC](https://blockchair.com/bitcoin/address/1JtgU6Uo1RAt5eiMf34EehyatUezBQP36C) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1JtgU6Uo1RAt5eiMf34EehyatUezBQP36C) [BSV](https://whatsonchain.com/address/1JtgU6Uo1RAt5eiMf34EehyatUezBQP36C)  
1JVmoJT3471FjsX5H4hAeR1RyrDgpkHbpm [BTC](https://blockchair.com/bitcoin/address/1JVmoJT3471FjsX5H4hAeR1RyrDgpkHbpm) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1JVmoJT3471FjsX5H4hAeR1RyrDgpkHbpm) [BSV](https://whatsonchain.com/address/1JVmoJT3471FjsX5H4hAeR1RyrDgpkHbpm)  
1JVU43LNKXqa9W5fCh8tppxDDEWgfeNg46 [BTC](https://blockchair.com/bitcoin/address/1JVU43LNKXqa9W5fCh8tppxDDEWgfeNg46) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1JVU43LNKXqa9W5fCh8tppxDDEWgfeNg46) [BSV](https://whatsonchain.com/address/1JVU43LNKXqa9W5fCh8tppxDDEWgfeNg46)  
1JztCg7eKSkb1vi7NzGJynXpLZmoaFtYud [BTC](https://blockchair.com/bitcoin/address/1JztCg7eKSkb1vi7NzGJynXpLZmoaFtYud) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1JztCg7eKSkb1vi7NzGJynXpLZmoaFtYud) [BSV](https://whatsonchain.com/address/1JztCg7eKSkb1vi7NzGJynXpLZmoaFtYud)  
1KFDUSZuapMv7YaDmL6cyrHTQhma1MtFYs [BTC](https://blockchair.com/bitcoin/address/1KFDUSZuapMv7YaDmL6cyrHTQhma1MtFYs) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1KFDUSZuapMv7YaDmL6cyrHTQhma1MtFYs) [BSV](https://whatsonchain.com/address/1KFDUSZuapMv7YaDmL6cyrHTQhma1MtFYs)  
1LLc8aA9C9LLULGbYCYSFKXgxKP2DXdCqP [BTC](https://blockchair.com/bitcoin/address/1LLc8aA9C9LLULGbYCYSFKXgxKP2DXdCqP) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1LLc8aA9C9LLULGbYCYSFKXgxKP2DXdCqP) [BSV](https://whatsonchain.com/address/1LLc8aA9C9LLULGbYCYSFKXgxKP2DXdCqP)  
1LS5EFRRMDgMQusW6zokQUHjzNUfy6HHCQ [BTC](https://blockchair.com/bitcoin/address/1LS5EFRRMDgMQusW6zokQUHjzNUfy6HHCQ) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1LS5EFRRMDgMQusW6zokQUHjzNUfy6HHCQ) [BSV](https://whatsonchain.com/address/1LS5EFRRMDgMQusW6zokQUHjzNUfy6HHCQ)  
1LueUjEuBgc7cQhsWT8zAfTjcWmrNBZXaR [BTC](https://blockchair.com/bitcoin/address/1LueUjEuBgc7cQhsWT8zAfTjcWmrNBZXaR) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1LueUjEuBgc7cQhsWT8zAfTjcWmrNBZXaR) [BSV](https://whatsonchain.com/address/1LueUjEuBgc7cQhsWT8zAfTjcWmrNBZXaR)  
1LXi3x7hyt17cxncscGE887WCrC6XDNZ4P [BTC](https://blockchair.com/bitcoin/address/1LXi3x7hyt17cxncscGE887WCrC6XDNZ4P) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1LXi3x7hyt17cxncscGE887WCrC6XDNZ4P) [BSV](https://whatsonchain.com/address/1LXi3x7hyt17cxncscGE887WCrC6XDNZ4P)  
1LzwbLgdKd4eFLkpRdeajkH1YJkVCip2zj [BTC](https://blockchair.com/bitcoin/address/1LzwbLgdKd4eFLkpRdeajkH1YJkVCip2zj) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1LzwbLgdKd4eFLkpRdeajkH1YJkVCip2zj) [BSV](https://whatsonchain.com/address/1LzwbLgdKd4eFLkpRdeajkH1YJkVCip2zj)  
1MkyfwJf7uhWTmVGGQXfcT5ip31DoHMxsz [BTC](https://blockchair.com/bitcoin/address/1MkyfwJf7uhWTmVGGQXfcT5ip31DoHMxsz) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1MkyfwJf7uhWTmVGGQXfcT5ip31DoHMxsz) [BSV](https://whatsonchain.com/address/1MkyfwJf7uhWTmVGGQXfcT5ip31DoHMxsz)  
1Mm9brripN4RPTzkGnRrbt5uDWdqbfk2iX [BTC](https://blockchair.com/bitcoin/address/1Mm9brripN4RPTzkGnRrbt5uDWdqbfk2iX) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1Mm9brripN4RPTzkGnRrbt5uDWdqbfk2iX) [BSV](https://whatsonchain.com/address/1Mm9brripN4RPTzkGnRrbt5uDWdqbfk2iX)  
1MPJJzRaT8vLhowNB4dVyWRxxu79dq7WkB [BTC](https://blockchair.com/bitcoin/address/1MPJJzRaT8vLhowNB4dVyWRxxu79dq7WkB) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1MPJJzRaT8vLhowNB4dVyWRxxu79dq7WkB) [BSV](https://whatsonchain.com/address/1MPJJzRaT8vLhowNB4dVyWRxxu79dq7WkB)  
1MvpYtqgBH7CXbTutrSVCTNHPzm9vakuRy [BTC](https://blockchair.com/bitcoin/address/1MvpYtqgBH7CXbTutrSVCTNHPzm9vakuRy) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1MvpYtqgBH7CXbTutrSVCTNHPzm9vakuRy) [BSV](https://whatsonchain.com/address/1MvpYtqgBH7CXbTutrSVCTNHPzm9vakuRy)  
1N5X4kcZ56uRh24XrZoztS9Vb8G7j1Joop [BTC](https://blockchair.com/bitcoin/address/1N5X4kcZ56uRh24XrZoztS9Vb8G7j1Joop) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1N5X4kcZ56uRh24XrZoztS9Vb8G7j1Joop) [BSV](https://whatsonchain.com/address/1N5X4kcZ56uRh24XrZoztS9Vb8G7j1Joop)  
1NA3Tj4b1jtx9eGELe31Jw4DrzTqKP3ayH [BTC](https://blockchair.com/bitcoin/address/1NA3Tj4b1jtx9eGELe31Jw4DrzTqKP3ayH) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1NA3Tj4b1jtx9eGELe31Jw4DrzTqKP3ayH) [BSV](https://whatsonchain.com/address/1NA3Tj4b1jtx9eGELe31Jw4DrzTqKP3ayH)  
1Pq7hooZbEAz5y3QMnqFY8C5xqTdrjUwcA [BTC](https://blockchair.com/bitcoin/address/1Pq7hooZbEAz5y3QMnqFY8C5xqTdrjUwcA) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1Pq7hooZbEAz5y3QMnqFY8C5xqTdrjUwcA) [BSV](https://whatsonchain.com/address/1Pq7hooZbEAz5y3QMnqFY8C5xqTdrjUwcA)  
1PRXQEoL8vzEzoJJ9hbtAP6NaV2daccAUn [BTC](https://blockchair.com/bitcoin/address/1PRXQEoL8vzEzoJJ9hbtAP6NaV2daccAUn) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1PRXQEoL8vzEzoJJ9hbtAP6NaV2daccAUn) [BSV](https://whatsonchain.com/address/1PRXQEoL8vzEzoJJ9hbtAP6NaV2daccAUn)  
1PxGTuJzDx1ceFHx4Z5CHaWuhiPBNovmZD [BTC](https://blockchair.com/bitcoin/address/1PxGTuJzDx1ceFHx4Z5CHaWuhiPBNovmZD) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/1PxGTuJzDx1ceFHx4Z5CHaWuhiPBNovmZD) [BSV](https://whatsonchain.com/address/1PxGTuJzDx1ceFHx4Z5CHaWuhiPBNovmZD)  
13Wv5hGhubAWgSPWtXYh6s1s7HX2N1psYg [BTC](https://blockchair.com/bitcoin/address/13Wv5hGhubAWgSPWtXYh6s1s7HX2N1psYg) [BCH](https://bitinfocharts.com/de/bitcoin%20cash/address/13Wv5hGhubAWgSPWtXYh6s1s7HX2N1psYg) [BSV](https://whatsonchain.com/address/13Wv5hGhubAWgSPWtXYh6s1s7HX2N1psYg)  


If you intend to use this list for your own purpose, please consider a donation to [Kim Nilsson](https://twitter.com/nikuhodai) of WizSecurity who traced and compiled this list. You'll find his BTC address on the bottom of his blog site: https://blog.wizsec.jp/



