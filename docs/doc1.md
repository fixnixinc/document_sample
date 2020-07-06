---
id: doc1
title: FixNix Infosec Solutions Pvt. Ltd
sidebar_label: Stripe
---

Check our other [products](https://freshgrc.com) here.

## Balance

This is an object representing your Stripe balance. You can retrieve it to see the balance currently on your Stripe account.

You can also retrieve the balance history, which contains a list of transactions that contributed to the balance (charges, payouts, and so forth).

The available and pending amounts for each currency are broken down further by payment source types.

Related guide: Understanding Connect Account Balances.

## The Balance Object

```
available array of hashes
Funds that are available to be transferred or paid out, whether automatically by Stripe or explicitly via the Transfers API or Payouts API. The available balance for each currency and payment type can be found in the 

source_types property.
```

## Balance Transaction

Balance transactions represent funds moving through your Stripe account. They're created for every type of transaction that comes into or flows out of your Stripe account balance.

## Charges

To charge a credit or a debit card, you create a Charge object. You can retrieve and refund individual charges as well as list all charges. Charges are identified by a unique, random ID.

## Create a Charge

Phasellus pulvinar ex id commodo imperdiet. Praesent odio nibh, sollicitudin sit amet faucibus id, placerat at metus. Donec vitae eros vitae tortor hendrerit finibus. Interdum et malesuada fames ac ante ipsum primis in faucibus. Quisque vitae purus dolor. Duis suscipit ac nulla et finibus. Phasellus ac sem sed dui dictum gravida. Phasellus eleifend vestibulum facilisis. Integer pharetra nec enim vitae mattis. Duis auctor, lectus quis condimentum bibendum, nunc dolor aliquam massa, id bibendum orci velit quis magna. Ut volutpat nulla nunc, sed interdum magna condimentum non. Sed urna metus, scelerisque vitae consectetur a, feugiat quis magna. Donec dignissim ornare nisl, eget tempor risus malesuada quis.
