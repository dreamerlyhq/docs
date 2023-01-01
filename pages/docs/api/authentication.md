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

Every Dreamerly project has a unique alphanumerical API key. A project's API key is not a secret value. In front-end implementation, such as our Javascript library, this key will be available to anyone visiting your page.

With that in mind, it is important to note that a project's API key is not a form of authorization. It is an identification sent along with each piece of data you send to your project.

All API requests must be made over HTTPS. Calls made over plain HTTP will fail. API requests without authentication will also fail.
