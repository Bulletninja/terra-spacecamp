# Simple NFT Market

## State

owner

bid
- amount
- bidder

ask
- amount

(token, bidder) -> bid
token -> ask

## Messages

```
- mint() # includes ask
- set_bid()
- accept_bid()
```

## User stories

1. Alice mints NFT with an ask of 5 tokens and becomes the owner.
2. Bob bids 3 tokens.
3. Alice accepts Bob's bid.
