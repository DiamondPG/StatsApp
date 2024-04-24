---
layout: default
title: L02CV-B
nav_order: 1
parent: L02CV
grand_parent: Error Codes
---

# L02CV-B - Error Retrieving Releases

This error occurs in the second section of the `CheckVersion()` function. This is an error cross-checking the version number with the github releases. Exception will detail the issue.

## Probable Causes
- **No Internet Connection**

Reconnect to the internet so that the version check can work correctly.

- **Server-side Error**

An error on the server-side can cause issues with this version check.

- **Authentication failed**

Authentication with Github's servers failed.
