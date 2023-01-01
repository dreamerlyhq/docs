---
Title: Apple App Store's app-specific shared secret
Subtitle: Get your App Store Connect's app-specific shared secret.
References:
  - https://www.revenuecat.com/docs/itunesconnect-app-specific-shared-secret
---

# Apple App Store's app-specific shared secret

The app-specific shared secret allows Dreamerly to connect with Apple on your behalf and verify purchase receipts.

## Setup

### 1. Generate an app-specific shared secret

- Sign in to your [App Store Connect account](https://appstoreconnect.apple.com)
- Click [My Apps](https://appstoreconnect.apple.com/apps) and select your app
- Navigate to the **Features** tab in the left-side menu, and select **Subscriptions**.
- Select **Manage** under the **App-Specific Shared Secret** section

{% image src="https://dreamerly-prod-site-assets.s3.amazonaws.com/docs/appstoreconnect-app-specific-shared-secret-20221223.webp" alt="Where to find your app-specific shared secret" %}
Where to find your app-specific shared secret.
{% /image %}

- Click **Generate** in the pop-up window, if you don't already have a shared secret
- Copy your shared secret

### 2. Enter the shared secret in Dreamerly

In your app settings for your iOS app in Dreamerly enter the key in the App Store configuration section.
