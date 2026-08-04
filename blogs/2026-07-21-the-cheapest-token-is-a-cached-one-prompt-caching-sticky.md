---
title: "The Cheapest Token Is a Cached One: Prompt Caching + Sticky Routing"
url: "https://openrouter.ai/blog/tutorials/prompt-caching-sticky-routing/"
date: "2026-07-21"
feed_url: "https://openrouter.ai/blog/feed.xml"
---
Your agent sends the same system prompt, tool definitions, and schemas on every turn. Cache reads cost 0.1x to 0.5x of fresh input, but only if the next request lands on the provider holding the warm cache. Here's how caching and sticky routing work together, and how to confirm they're working.
