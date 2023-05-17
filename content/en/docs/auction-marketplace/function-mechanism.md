---
title: Function, Mechanism
draft: false
images: []
weight: 320
lastmod: 2022-12-12T19:08:04.030Z
---

- Conditions for upload song (music works count as song unit):
Artists upload their songs to Artist Pool using the best recording quality available. If the upload progress is failed, it means that the artist who uploaded the song did not meet the above criteria.

- Artists do not have the right to upload the same song more than once.

- Any song in any Artist Pool can be minted to an NFT depending on the artist whom owns that Pool whether need to sell and open an auction.

## The Concept

### Upload a song

When you start uploading your music work (song), the system then will require your original audio file to process it, so make sure your prepared audio file is the best one and ready to be distributed.

If you have your owned copyright or any legal file that related to your uploaded audio file, you should attach it beside the audio file, this action will help the reviewing process runs faster and protect yourself.

### Reviewing

Our reviewing system will process your audio file manually, and you will be delivering APPROVED or REJECTED status in your email.

You will become an Artist if your first three songs are APPROVED and completely uploaded.

When the song is approved, our system will use it and produce other song qualities (128 kbps, 192 kbps, 320 kbps or Lossless).

> Kindly note that the original file still be kept in our safe only and not for distributing.

### Minting

Your audio file is now ready to be minted into the blockchain. You will need some ETH for the gas fee. Just click Mint and accept the action through the Smart Contract.

After some block confirmations from the blockchain, the audio file will be marked as MINTED in the system, you can check it through **Profile > Item Management > My items**

From this point, your audio file is minted and broadcasted in the blockchain, you will be able to use this file to sell it on the marketplace by openning an auction.

### Listing

There are some values that you need to think about before making an auction listing:
* When it's start and end?
* Your starting price

When you are ready, click the LISTING button, there is a form that you need to fill in.
Another Smart Contract form will ask you to confirm that you will sell your song to the marketplace. This will take some of your ETH for gas fee.

If your start time is in the future, the song will be listed as COMING, and BIDDING when its on sale time.

> Please note that: Once you proceed an auction listing, you are now agree to sell the copy-right of your music work to anyone whom would be the bidding winner.

### Bidding

Traveling through the Explore screen, you will see many songs that are listed as NFT on the marketplace. When you have any account from Decibling system, you would be able to bid on any NFT that you want.

> You can, however, bid without any additional funds. We recommend that you add a wallet and use it through the marketplace; it will provide you with numerous benefits in the future.

In the early version, our bidding system worked in a straightforward manner: you put a highest price to a song (based on starting price)and when the timer runs out, the song is yours.

To make a bid, just put your desired price on the song listing, then click Bid button. A Smart Contract form will ask you to confirm the bid. This will take some of your ETH for gas fee.

> The Smart Contract will keep the highest bid value to make sure the bid session worked and the item can be distributed correctly after the bid is settled. All lower bids will be refunded to your wallet if there is any new highest value is added to the bid session.

### Cancel a bid

In the following scenarios, the item owner will be able to cancel a bid when the end time has reached:
* Have a winner, but the item owner no longer wishes to sell it.
* Ended bid had no bidders in that bid session.

This will take some of your ETH for gas fee.

### Settle a bid

When the ending time reached, the item owner will be able to finalize the bid, this action will:
* Transfer the item ownership to the winner.
* The seller will receive the tokens after taxes are deducted (including income tax and DCBA pool).

This will take some of your ETH for gas fee.

### Fees

This table decribe all of fees that the marketplace collected on the first sale:
|         | Artist | Collector |
|---------|--------|-----------|
| Minting | Gas fee       |           |
| Listing | Gas fee       |           |
| Bidding |        | Gas fee          |
| Settle  | 10% income tax<br/>2.5% DCBA pool       | 2.5% DCBA pool (optional)          |

> Optional: when you won a bid, you will be able to receive the profits from DCBA pool if you transfer to the DCBA pool the required percent as noted above.

### Examples

#### First sale
* Artist A mints and lists the item with starting price at 10 FROY
* Bidding...
* Collector C wons at 50 FROY

Item ownership transfered from A to C, and A receives:

**50 FROY - (10% income tax + 2.5% DCBA pool) = 50 - (5 + 1.25) = 43.75** (with ETH gas fee).
#### Second sale (and more)
* Collector C lists the item with starting price at 50 FROY
* Bidding...
* Collector C1 wons at 100 FROY

Item ownership transfered from C to C1, and C receives:

**100 FROY - (10% income tax) = 100 - 10 = 90** (with ETH gas fee).
