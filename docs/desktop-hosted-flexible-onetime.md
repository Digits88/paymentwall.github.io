---
id: desktop-hosted-flexible-onetime
title: Onetime payment
sectionid: docs
permalink: hosted/flexible/onetime
---

# Onetime Payments

By using onetime payments of flexible products, your customer do a instant payment for only one time. Non recurring billing will be applied.

## API Call

The parameter ```ag_type``` should be set as ```fixed``` in API call. See code sample for [onetime payments](/API-Reference#section-hosted-flexible-onetime) to perform API Call.

## Duplicate order

Our widget allows users to refresh the website to redo payments, which may result in a fact that you will receive two [pingbacks](/default-pingback) with different ref ID for same order id of your application.
 
You can add ```merchant_order_id``` as a ```OWN``` type [custom pingback parameter](/pingback-custom-parameters) to void duplicate order event.

> You will also need to contact [devsupport@paymetnwall.com](mailto:devsupport@paymentwall.com) to activate associated settings.

## Next Step

After implementing the paylet you need to implement the server side pingback script in order to receive the payments confirmations.

> [Pingbacks](/default-pingback).

Below links may also be helpful for you.

> [Test payment method](/sandbox/test-payment).

> [SpiderPipe](/spiderpipe-home).