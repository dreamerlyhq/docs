---
Title: Apple's App Store Server Notifications
Subtitle: Sending the App Store's server notifications to Dreamerly.
References:
  - https://www.revenuecat.com/docs/apple-server-notifications
---

# Apple's App Store Server Notifications

By default, Dreamerly only triggers NFT minting on the blockchain 48 hours after an in-app purchase for an NFT is made. Setting up App Store Server Notifications with Dreamerly ensures that if the customer successfully requests a refund, no NFT minting takes place.

## Setup

[App Store Server Notifications](https://developer.apple.com/documentation/storekit/in-app_purchase/enabling_server-to-server_notifications) should be set up in App Store Connect with the URL provided in your [Profile page](https://app.dreamerly.com/profile). On the **Profile** page, scroll to the **API key** section, and copy the **Apple Notification URL** value.

{% image src="https://dreamerly-prod-site-assets.s3.amazonaws.com/docs/apple-server-notifications-20230105.webp" alt="View your iOS apps" %}
Copy the Apple Notification URL.
{% /image %}

Go to [App Store Connect](https://developer.apple.com/support/app-store-connect/) > [My Apps](https://developer.apple.com/support/app-store-connect/apps) and select your app.

Under the **App Information** > **App Store Server Notifications** section, paste the entire URL from Dreamerly in both the **Production Server URL** field and the **Sandbox Server URL** field. You can use either Version 1 or Version 2 notifications.
