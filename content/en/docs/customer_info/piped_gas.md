---
title: "Piped Gas Customer Info"
description: ""
lead: ""
date: 2023-02-06T01:38:59+05:30
lastmod: 2023-02-06T01:38:59+05:30
draft: false
images: []
menu:
docs:
parent: "customer_info"
identifier: "piped_gas-b89992f783cab5d349c426bbf2f31672"
weight: 160
toc: true
---

### Endpoint URL

```bash
/api/v1/customer_info/piped_gas
```

### Description

This endpoint provides specific piped gas customer information and bill information for given details.

### Method

GET

### Authentication

Token-based authentication is used for API access. API documentation provides detailed information on how to obtain an
API token and how to use it in API requests.

#### Header Parameters

| Parameter        | Type   | Description                                       | Required |
|------------------|--------|---------------------------------------------------|----------|
| `authentication` | String | The authentication token from the plansapi panel. | Yes      |

### Query Parameters

| Parameter  | Type   | Description                                                                           | Required |
|------------|--------|---------------------------------------------------------------------------------------|----------|
| `operator` | String | The name of the piped gas operator for which customer information is being requested. | Yes      |
| `number`   | String | The customer ID or account number associated with the piped gas operator.             | Yes      |
| `field1`   | String | An optional field for additional customer information.                                | No       |
| `field2`   | String | An optional field for additional customer information.                                | No       |
| `field3`   | String | An optional field for additional customer information.                                | No       |
