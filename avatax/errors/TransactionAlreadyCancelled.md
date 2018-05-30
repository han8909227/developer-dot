---
layout: page
title: TransactionAlreadyCancelled
number: 198
categories: [AvaTax Error Codes]
disqus: 1
---

## Summary

The transaction has already been cancelled

## Example

```json
{
  "code": "TransactionAlreadyCancelled",
  "target": "Unknown",
  "details": [
    {
      "code": "TransactionAlreadyCancelled",
      "number": 198,
      "message": "The transaction has already been cancelled.",
      "description": "The transaction '-0-' is already in a 'Cancelled' status. There is nothing to be done.",
      "faultCode": "Client",
      "helpLink": "http://developer.avalara.com/avatax/errors/TransactionAlreadyCancelled",
      "severity": "Error"
    }
  ]
}
```

## Explanation

Your transaction has already been cancelled, to create a new one please call CreateTransaction API.
