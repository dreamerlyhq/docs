---
Title: Retrieve a transaction
Subtitle: This endpoint is to fetch information about an NFT transaction.
References:
  - https://docs.opensea.io/reference/getting-assets
---

# Retrieve a transaction

Retrieves a transaction.

## Parameters

`transaction_id`: The id of the transaction.

## Headers

`x_api_key` (string): Your API Key.

```curl
curl --request GET 'https://test-api.dreamerly.com/nfts/{TRANSACTION_ID}' \
--header 'x-api-key: {YOUR_API_KEY}' \
```
