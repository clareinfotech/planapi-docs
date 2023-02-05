---
title: "Dth Plans"
description: ""
lead: ""
date: 2023-02-06T00:54:00+05:30
lastmod: 2023-02-06T00:54:00+05:30
draft: false
images: []
menu:
docs:
parent: ""
identifier: "dth-plans-53e87e76e95a4f3d9ba7a6f2882d2176"
weight: 70
toc: true
---

### Endpoint URL

```bash
/api/v1/dth_plans
```

### Description

This endpoint provides access to the latest dth plans information for a specific operator.

### Method

GET

### Authentication

Token-based authentication is used for API access. API documentation provides detailed information on how to obtain an
API token and how to use it in API requests.

#### Header Parameters

| Parameter      | Description                                       | Required |
|----------------|---------------------------------------------------|----------|
| authentication | The authentication token from the plansapi panel. | Yes      |

### Query Parameters

| Parameter | Description                                                                            | Required |
|-----------|----------------------------------------------------------------------------------------|----------|
| operator  | The name of the operator for which you want to retrieve the prepaid plans information. | Yes      |
