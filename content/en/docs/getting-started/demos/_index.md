---
title: "Demos"
linkTitle: "Demos"
weight: 100
description: >
  See example usage of the API including a simple server and plugins.
---

The following labs exist for you to work with the Perspective API.

### Server demo

[A simple demo server](https://github.com/conversationai/perspectiveapi-simple-server) which serves some static content from a specified directory, and provides proxy to the API in a way that enables the API-key to be kept private.

This demo can hold your API key and access the API.

### Authorship demo

[Example of an authorship experience](https://github.com/conversationai/perspectiveapi-authorship-demo) gives an author feedback as they type.

### Proxy demo

[Proxy to the API](https://github.com/conversationai/perspectiveapi-proxy) with access restrictions and a simple UI to debug calls to the API. It is intended to be used by a system that wants asynchonous scoring of comments.

### Conversation AI Moderator

Thee [Conversation AI - Moderator](https://github.com/conversationai/conversationai-moderator) is a comment moderation system that provide hint and assist UI for moderators based on a plugable model of computational assistants, including support for using Perspective API models.

There are also plugins to support moderation of different platforms, e.g.:

+ [Discourse plugin](https://github.com/conversationai/conversationai-moderator-discourse)
+ [WordPress plugin](https://github.com/conversationai/conversationai-moderator-wordpress)
+ [Reddit plugin](https://github.com/conversationai/conversationai-moderator-reddit) (incomplete, does not yet support actions)

