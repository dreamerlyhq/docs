---
Title: Quickstart
Subtitle: Get up and running with mobile NFT transactions.
References:
  - https://www.revenuecat.com/docs/getting-started
  - https://docs.dyte.io/getting-started

TODO: Replace the callout with:

{% callout title="Test mode and Live mode" %}
Each Dreamerly account includes a test and live mode in two separate environments:

- Test: [https://test-app.dreamerly.com](https://test-app.dreamerly.com)
- Live: [https://app.dreamerly.com](https://app.dreamerly.com)

Test mode is used to configure projects with smart contracts that are deployed to a testnet. Live mode is for mainnet smart contracts.

{% /callout %}
---

# Quickstart

This guide will walk you through how to get up and running with NFT transactions and Dreamerly's SDK with only a few lines of code.

{% callout title="Test mode" type="caution" %}
Dreamerly is in test mode. We only support smart contracts deployed to the Polygon testnet at the moment. The live mode for mainnet smart contracts will launch soon.
{% /callout %}

## 1. Create a Dreamerly account

Sign up for a new Dreamerly account [here](https://app.dreamerly.com). If you cannot find the verification email, check your spam folder.

We recommend using a company account when registering for Dreamerly.

## 2. Get test MATIC tokens on the Polygon Mumbai testnet

Dreamerly's test mode uses the Polygon Mumbai testnet. To deploy an NFT smart contract, you need to fill your wallet with some test MATIC tokens.

See [Get test tokens](/docs/get-test-tokens) to add test MATIC tokens to your wallet address.

## 3. Add an NFT collection

An NFT collection is a set of NFTs or digital collectibles whose metadata is stored on the blockchain. Before you can start using Dreamerly to mint NFTs, you must create an NFT collection and deploy its smart contract. In the test mode, Dreamerly deploys NFT smart contracts on the Polygon Mumbai testnet.

To create a new NFT collection, click on the **Create collection** button on the [Collections page](https://app.dreamerly.com/collections). Note the `collection_id` parameter of the NFT collection, as you will use it to mint NFTs to your end users.

**ADD SCREENSHOT HERE**

## 4. Connect with the App Store's backend

The Apple App Store's app-specific shared secret needs to be set up for Dreamerly to connect with Apple and verify purchase receipts on your behalf. See our [App Store Connect's app-specific shared secret guide](/docs/appstoreconnect-app-specific-shared-secret) for more information.

## 5. Configure app store's products

TBD

## 6. Using the Dreamerly SDK

Our SDK seamlessly implements NFT purchases and transactions across platforms while syncing tokens with the Dreamerly server.

## Sample apps

To download more complete examples of integrating the SDK, head over to our sample app resources.