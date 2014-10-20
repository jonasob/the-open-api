---
category: Legal services
path: '/legal/support:q'
title: 'Get legal support'
type: 'GET'
layout: nil
tags:
 - sflc
 - fsfe
---

This method allows the user to get help with a question in a supporty
fashion!

### Request

* **`:q`** is the question for which an answer is sought.

### Response

Sends back an answer.

```Status: 200 Answered```
```{
    code: 200,
    message: 'In response to your question, ...'
}```

For errors responses, see the [response status codes documentation](#response-status-codes).
