---
Title: API keys
Subtitle: Manage your API keys to authenticate with Dreamerly.
References:
  - https://www.revenuecat.com/docs/authentication
  https://stripe.com/docs/keys
---

# API keys

Dreamerly authenticates requests from the REST API and the SDK using your API keys. All requests must include a valid API key.

Your API key should be kept secret and used on the server-side only. By default, you can use your API key to perform any API request without restriction.

## Obtain API keys

You can use the [the Profile page on the Dreamerly Dashboard](https://app.dreamerly.com/profile) to reveal your secret API key. Your key is listed under the **API key** section.

{% image src="https://dreamerly-prod-site-assets.s3.amazonaws.com/docs/keys-20230102.webp" alt="Find the API key on your Profile page" %}
Find the API key on your Profile page.
{% /image %}

{% callout title="Protect your API key" type="warning" %}
Never embed secret API keys in your app or website.
{% /callout %}

## Keeping API keys safe

The API key can be used to make any API request on behalf of your Dreamerly account, such as creating NFT collections and minting NFTs. Use the following best practices to keep your keys safe:

- Grant access only to those who need it.
- Ensure the key is kept out of any version control system you might be using.
- Control access to your key using a password manager or secrets management service.
- Don't embed your API key in mobile applications or other places from where the key could be extracted.
