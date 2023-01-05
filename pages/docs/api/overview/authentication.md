---
Title: Authentication
Subtitle: Explaining Dreamerly API's authentication methods.
References:
  - https://stripe.com/docs/api/authentication
  - https://developer.mixpanel.com/reference/authentication
  - https://developer.mixpanel.com/reference/project-token
---

# API Reference

## Overview

The Dreamerly APIs use API keys to authenticate requests. You can view and manage your API keys in the Dreamerly Dashboard.

Every Dreamerly project has a unique alphanumerical API key. Your API keys carry many privileges, so be sure to keep them secure! Do not share your secret API keys in publicly accessible areas such as GitHub, client-side code, and so forth.

All API requests must be made over [HTTPS](http://en.wikipedia.org/wiki/HTTP_Secure). Calls made over plain HTTP will fail. API requests without authentication will also fail.