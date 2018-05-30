---
layout: page
title: InvalidAuditMessage
number: 1410
categories: [AvaTax Error Codes]
disqus: 1
---

## Summary

Please review your audit message and ensure no special characters are used.

## Example

```json
{
  "code": "InvalidAuditMessage",
  "target": "Unknown",
  "details": [
    {
      "code": "InvalidAuditMessage",
      "number": 1410,
      "message": "The audit message provided in request header contains invalid characters: -0-.",
      "description": "Please avoid using '<' or '>' characters in your audit message.",
      "faultCode": "Client",
      "helpLink": "http://developer.avalara.com/avatax/errors/InvalidAuditMessage",
      "severity": "Error"
    }
  ]
}
```

## Explanation

For detail on which character is causing this error, please see the description on your error.
