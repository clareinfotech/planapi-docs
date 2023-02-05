---
title: "Dth Mapping"
description: ""
lead: ""
date: 2023-02-06T01:36:42+05:30
lastmod: 2023-02-06T01:36:42+05:30
draft: false
images: []
menu:
  docs:
    parent: "mapping"
    identifier: "dth-95b797d7e0339b696ab0fc28d15a66a6"
weight: 120
toc: true
---

### Endpoint URL

```bash
/api/v1/operator_map/postpaid
```

### Description

This endpoint provides specific dth operator details for customer number.

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

| Parameter | Type   | Description                                                                 | Required |
|-----------|--------|-----------------------------------------------------------------------------|----------|
| `number`  | String | The dish customer number for which operator information is being requested. | Yes      |
