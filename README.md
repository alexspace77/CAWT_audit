# CAWT

Ver 0.1

Legend:

CAWT - token contract (ticket)

CAWTSale - describes how user buys a token (ticket)

CAWTFarming - describes BNB farming process

CAWTLottery - describes interactions with a lottery

Functions’ description:

- CAWTFarming
    - deposit
    - pendingReward (amount of tickets farmed)
    - claim (withdraw tickets farmed)
    - withdraw (withdraw staked BNB)
- CAWTLottery
    - create lottery (owner creates a lottery with fixed conditions)
    - participate (user chooses a lottery and a ticket number)
    - ticket left (amount of tickets left)
    - send prize (random generator (not implemented yet) states the winning number and sends BNB to a winner)
- CAWTsale
    - setPrice (owner sets ticket price)
    - buy (user buys token with BNB)
