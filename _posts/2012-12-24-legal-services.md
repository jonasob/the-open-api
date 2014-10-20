---
category: Legal services
tags: sflc
path: '/legal/services:q'
title: 'Get legal services'
type: 'GET'

layout: nil
---

This method allows the user to get help with a question.

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
