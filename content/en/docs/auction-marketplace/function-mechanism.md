---
title: Function, Mechanism
draft: false
images: []
weight: 320
lastmod: 2022-12-12T19:08:04.030Z
---

Condition for upload song (music works count as song unit):
Artists upload their songs to Artist Pool using the best recording quality available. If the upload fails, it means that the artist who uploaded the song did not meet the above criteria.


Artists do not have the right to upload the same Song more than once.
Any song in the Artist Pool can become an NFT depending on the artist who owns that Pool's need to sell and open an auction.

# The Concept
## Upload a song
The system will need your original audio file to process it, so make sure your prepared song is the best one and ready to distribute.

If you have any legal files that related to the audio, you should attach it beside the audio, this will help the reviewing process faster.

## Reviewing
Our reviewing system will process your audio manually, and your will got APPROVED or REJECTED status in your email.

You will become an Artist if your first three songs are APPROVED.

When the song is approved, our system will use it and produce other song qualities (128 kbps, 192 kbps, 320 kbps and Lossless).

> Kindly note that the original file still be kept in our safe only and not for distributing.

## Minting
Your audio file is now ready to mint into the blockchain. You will need some ETH for the gas fee. Just click Mint and accept the action through the Smart Contract.

After some block confirmations from the blockchain, the audio file will be marked as MINTED in the system, you can check it through **Profile > Item Management > My items**

From this point, your audio file is minted and broadcasted in the blockchain, you will be able to use this file to sell it on the marketplace.

## Listing
There are some values that you need to think about before making a listing
* When it's start and end?
* Your starting price

When you are ready, click the LISTING button, there is a form that you need to fill in.
Another Smart Contract form will ask you to confirm that you will sell your song to the marketplace. This will take some of your ETH for gas fee.

If your start time is in the future, the song will be listed as COMING, and BIDDING when its on sale time.

## Bidding
Traveling through the Explore screen, you will see many songs that are listing on the marketplace. When you have an account, you would be able to do bid on any song you want.

> You can, however, bid without any additional funds. We recommend that you add a wallet and use it through the marketplace; it will provide you with numerous benefits in the future.

In the early version, our bidding system worked in a straightforward manner: you put a highest price to a song (based on starting price)and when the timer runs out, the song is yours.

To make a bid, just put your desired price on the song listing, then click Bid button. A Smart Contract form will ask you to confirm the bid. This will take some of your ETH for gas fee.

> The Smart Contract will keep the highest bid value to make sure the bid session worked and the item can be distributed correctly after the bid is settled. All lower bids will be refunded to your wallet if there is any new highest value is added to the bid session.

## Settle a bid
When the ending time reached, the item owner will be able to finalize the bid, this action will:
* Transfer the item ownership to the winner.
* The seller will receive the tokens after taxes are deducted (including income tax and DCBA pool).

This will take some of your ETH for gas fee.

## Fees
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

## Notes
* If the bid is made and the seller (artist/collector) did not take action to settle the bid within 72 hours, the marketplace will distribute automatically, but with the fee at 2.5% of the won price.
