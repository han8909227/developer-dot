---
layout: page
title: InvalidExemptionOperation
number: 1212
categories: [AvaTax Error Codes]
disqus: 1
---

## Summary

Filtering operation is not supported

## Example

```json
{
  "code": "InvalidExemptionOperation",
  "target": "Unknown",
  "details": [
    {
      "code": "InvalidExemptionOperation",
      "number": 1212,
      "message": "Filtering operation is not supported",
      "description": "The API -0- does not currently support the -1- filter command.",
      "faultCode": "Client",
      "helpLink": "http://developer.avalara.com/avatax/errors/InvalidExemptionOperation",
      "severity": "Error"
    }
  ]
}
```

## Explanation

This API (see your error message) does not support filter command
