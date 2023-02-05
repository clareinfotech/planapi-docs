---
title: "Error & Status Code"
description: ""
lead: ""
date: 2023-02-06T02:16:10+05:30
lastmod: 2023-02-06T02:16:10+05:30
draft: false
images: []
menu:
  docs:
    parent: "error_status_code"
    identifier: "overview-d47d3219d037cd1bc185cc601500493e"
weight: 999
toc: true
---

When using the Mobile Sim Operators Plans API, there may be instances where errors are encountered. Listed below are
common errors and the corresponding responses that may be returned.

| Error | 	Response             | 	Description                                                                                                                                                                                    |
|-------|-----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 401   | Unauthorized          | 	{"error": "Invalid or missing authentication token"}	This error is returned when the authentication token is either invalid or missing. Please ensure that a valid token is being used.        |
| 400   | Bad Request           | 	{"error": "Missing required parameters"}	This error is returned when required parameters are missing from the request. Please ensure that all required parameters are included in the request. |
| 404   | Not Found             | 	{"error": "Endpoint not found"}	This error is returned when the requested endpoint could not be found. Please check the endpoint URL and ensure that it is correct.                            |
| 500   | Internal Server Error | 	{"error": "An unexpected error has occurred"}	This error is returned when an unexpected error has occurred on the server. Please try again later or contact support if the issue persists.     |

Please note that these are only examples of common errors and responses, and other error messages may also be returned
depending on the specific endpoint and request being made.
