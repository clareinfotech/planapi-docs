---
title: "Prepaid Mapping"
description: ""
lead: ""
date: 2023-02-06T01:36:32+05:30
lastmod: 2023-02-06T01:36:32+05:30
draft: false
images: []
menu:
docs:
parent: "mapping"
identifier: "prepaid-3ecc1a2756324714bf3683e5907fc25d"
weight: 100
toc: true
---

### Endpoint URL

```bash
/api/v1/operator_map/prepaid
```

### Description

This endpoint provides specific prepaid operator details for mobile number.

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
