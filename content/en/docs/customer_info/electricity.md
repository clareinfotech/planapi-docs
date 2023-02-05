---
title: "Electricity Customer Info"
description: ""
lead: ""
date: 2023-02-06T01:38:49+05:30
lastmod: 2023-02-06T01:38:49+05:30
draft: false
images: []
menu:
docs:
parent: "customer_info"
identifier: "electricity-b1c08d24cf0950677682e914bf900039"
weight: 150
toc: true
---

### Endpoint URL

```bash
/api/v1/customer_info/electricity
```

### Description

This endpoint provides specific electricity customer information and bill information for given details.

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
| `number`   | String | The customer ID or account number associated with the electricity operator.           | Yes      |
| `field1`   | String | An optional field for additional customer information.                                | No       |
| `field2`   | String | An optional field for additional customer information.                                | No       |
| `field3`   | String | An optional field for additional customer information.                                | No       |
