---
visibility: hidden
---

# TODO

- Every time a user hits a milestone of certain amount of TAP then it enables some power ups
- Users holding TAP earn interest that pays out daily in their pending balance
- Concept of pending versus actual wallet balance
- TAP coin should have 6 decimal places
  - Unsure how much the total supply should be
- Create a Discord
- Create a Subreddit

# Deployment

configure master db with proper security

# Random Notes

PA = num days payout interval / days in year _ interest rate
= 7 / 365 _ 10%

```
let accountInfo = await indexerClient.searchAccounts()
        .assetID(assetIndex)
        .currencyGreaterThan(currencyGreater).do();
```

# Reference

https://developer.algorand.org/docs/get-details/indexer/
https://developer.algorand.org/docs/get-details/transactions/#setting-first-and-last-valid
https://github.com/algorand/js-algorand-sdk
https://developer.purestake.io/
https://developer.algorand.org/docs/get-details/indexer/#search-transactions-for-a-specific-account
https://developer.algorand.org/docs/get-details/asa/
https://dappradar.com/blog/algorand-dapp-development-2-standard-asset-management/#ASA
