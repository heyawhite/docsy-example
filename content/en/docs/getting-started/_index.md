---
title: "Getting Started with Perspective API"
linkTitle: "Getting Started"
weight: 1
description: >
  Get started quickly authenticating and using the API.
---

## Prerequisites

You'll need a Google Cloud project to authenticate (but not necessarily host) your API requests. Go to the [Google Cloud console](https://console.developers.google.com/) and either use an existing project, or follow these steps to create a new one:

1. Sign in with your Google account, if necessary.

1. Click **Create**, or click the "Project" drop-down at the top of the page and then click **New Project**.

1. Name the project.

1. Click **Create** again. The project is now included in the "Project" drop-down at the top of the page.

## Enable the API

### Command line

Run  `gcloud services enable commentanalyzer.googleapis.com` in the command line to enable the API.

### Web UI

Navigate to the [Perspective API's overview page](https://console.developers.google.com/apis/api/commentanalyzer.googleapis.com/overview) and click **Enable**.

### Authenticate your requests

Go to the [API credentials page](https://console.developers.google.com/apis/credentials), click **Create credentials**, and choose "API Key".

> **Warning**: If you make requests from a client-side language like JavaScript, your API key will be exposed to all visitors. We strongly recommend that you [add key restrictions](https://cloud.google.com/docs/authentication/api-keys#api_key_restrictions) so that only your production server can use that key.
	
Note that it typically takes only a few minutes for a new API key to have access after the API is enabled, but it can on occasion take up to an hour. Until the API key is enabled, you may get errors of the form "API Key not found. Please pass a valid API key."
