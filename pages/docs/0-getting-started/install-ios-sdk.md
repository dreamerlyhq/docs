---
Title: Install the iOS SDK
Subtitle: Instructions for installing the Dreamerly SDK for iOS.
References:
  - https://www.revenuecat.com/docs/ios
---

# Install the iOS SDK

## Requirements

Xcode 13.3.1+
Minimum target: iOS 11.0+

## Install via Swift Package Manager

You can use the Swift Package Manager to add the iOS SDK to your Xcode project. Select **File** > **Swift Packages** > **Add Package Dependency** and enter the Dreamerly iOS SDK's repository URL: [https://github.com/dreamerlyhq/dreamerly-ios-sdk](https://github.com/dreamerlyhq/dreamerly-ios-sdk).

You can also navigate to your target’s **General** pane, and in the **Frameworks, Libraries, and Embedded Content** section, click the **+** button, select **Add Other**, and choose **Add Package Dependency**.

{% image src="https://dreamerly-prod-site-assets.s3.amazonaws.com/docs/install-ios-sdk-20230104.webp" alt="Add package dependency" %}
Add package dependency to your Xcode project.
{% /image %}

Once you enter the URL, select "Branch" as the **Dependency Rule**. Enter "main" in the input field for branch name.
