---
title: Server Side Receipt Validation - Google Play
date: 2021-01-10 19:17:27
tags: google-play
---

### How

There is a good answer in [stackoverflow](https://stackoverflow.com/questions/35127086/android-inapp-purchase-receipt-validation-google-play).

### API

- [purchases.products.get](https://developers.google.com/android-publisher/api-ref/rest/v3/purchases.products/get)

    Checks the purchase and consumption status of an inapp item.

- [purchases.subscriptions.get](https://developers.google.com/android-publisher/api-ref/rest/v3/purchases.subscriptions/get)

    Checks whether a user's subscription purchase is valid and returns its expiry time.

### Authorization

There is the [authorization](https://developers.google.com/android-publisher/authorization) doc.
