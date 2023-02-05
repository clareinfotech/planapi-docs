---
title: "Postpaid Mapping"
description: ""
lead: ""
date: 2023-02-06T01:36:38+05:30
lastmod: 2023-02-06T01:36:38+05:30
draft: false
images: []
menu:
docs:
parent: "mapping"
identifier: "postpaid-27293d40c5efc2a20c7c2b209e36ed88"
weight: 110
toc: true
---

### Endpoint URL

```bash
/api/v1/operator_map/postpaid
```

### Description

This endpoint provides specific postpaid operator details for mobile number.

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

| Parameter | Type   | Description                                                                   | Required |
|-----------|--------|-------------------------------------------------------------------------------|----------|
| `number`  | String | The 10-digit mobile number for which operator information is being requested. | Yes      |
