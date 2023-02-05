---
title: "Prepaid Plans"
description: ""
lead: ""
date: 2023-02-06T00:53:54+05:30
lastmod: 2023-02-06T00:53:54+05:30
draft: false
images: []
menu:
docs:
parent: ""
identifier: "prepaid-plans-9a1375c92b14df4633a0144569c4c1cb"
weight: 60
toc: true
---

### Endpoint URL

```bash
/api/v1/plans
```

### Description

This endpoint provides access to the latest prepaid plans information for a specific operator.

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

| Parameter  | Type   | Description                                                                            | Required |
|------------|--------|----------------------------------------------------------------------------------------|----------|
| `operator` | String | The name of the operator for which you want to retrieve the prepaid plans information. | Yes      |
