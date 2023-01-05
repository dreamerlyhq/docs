---
Title: Mint an NFT
Subtitle: This endpoint is to mint an NFT from your NFT smart contract.
References:
  - https://docs.opensea.io/reference/getting-assets
---

# Mint an NFT

Mints an NFT.

## Data

A JSON object that includes:

`to_address`: The address of the recipient (your end user).

`collection_id`: The ID of your NFT collection (found in the Dreamerly Dashboard's [Collections](https://app.dreamerly.com/collections) page).

`metadata`: Attach arbitrary key-value data to the NFT object.

## Headers

`x_api_key` (string): Your API Key.

```curl
curl --request POST 'https://test-api.dreamerly.com/nfts' \
--header 'x-api-key: {YOUR_API_KEY}' \
--header 'Content-Type: application/json' \
--data-raw '{
    "to_address": "{TO_ADDRESS}",
    "collection_id": "{COLLECTION_ID}",
    "metadata": {
        "name": "Dreamerly Mint API",
        "image": "https://uploads-ssl.webflow.com/6297408732daee649fa48f62/63657a5f372ceccb5b9ab457_SEO%20IMG.jpg",
        "description": "Test NFT created by the Dreamerly Minting API"
    }
}'
```
