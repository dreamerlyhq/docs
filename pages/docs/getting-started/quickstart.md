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

## 2. Add an NFT collection

An NFT collection is a set of NFTs or digital collectibles whose metadata is stored on the blockchain. Before you can start using Dreamerly to mint NFTs, you must create an NFT collection and deploy its smart contract. In the test mode, Dreamerly deploys NFT smart contracts on the Polygon Mumbai testnet.

To create a new NFT collection, click on the **Create collection** button on the [Collections page](https://app.dreamerly.com/collections). A smart contract corresponding to the NFT collection will be deployed to the blockchain. Note the "COLLECTION ID" value of the NFT collection, as you will use it to mint NFTs to your end users.

{% image src="https://dreamerly-prod-site-assets.s3.amazonaws.com/docs/quickstart-20230102-1.webp" alt="Create and deploy your NFT collection" %}
Create and deploy your NFT collection.
{% /image %}

## 3. Connect with the App Store's backend

The Apple App Store's app-specific shared secret needs to be set up for Dreamerly to connect with Apple and verify purchase receipts on your behalf. See our [App Store Connect's app-specific shared secret guide](/docs/appstoreconnect-app-specific-shared-secret) for more information.

## 4. Configure the App Store's products

To enable your in-app purchase product offerings, configure your products in the App Store. See our [iOS product setup guide for App Store Connect](/docs/ios-products) for help navigating this process.

If you are selling iOS products, be sure to sign your Paid Applications Agreement and fill out your banking and tax information in [App Store Connect](https://appstoreconnect.apple.com/) > [Agreements, Tax, and Banking](https://appstoreconnect.apple.com/WebObjects/iTunesConnect.woa/da/jumpTo?page=contracts). This needs to be completed before you can test any purchases.

{% image src="https://dreamerly-prod-site-assets.s3.amazonaws.com/docs/quickstart-20230102.webp" alt="Complete your banking and tax information in App Store Connect" %}
Complete your banking and tax information in App Store Connect.
{% /image %}

{% callout title="Want to skip the store setup while testing?" type="info" %}
On iOS, you can delay configuring products in App Store Connect by testing with StoreKit Configuration files instead. These config files require minimal setup and are configurable via Xcode directly.
{% /callout %}

## 5. Using the Dreamerly SDK

Our SDK seamlessly implements NFT purchases and transactions across platforms while syncing tokens with the Dreamerly server.

## Sample apps

To download more complete examples of integrating the SDK, head over to our sample app resources.
