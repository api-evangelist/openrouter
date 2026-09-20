---
title: "Build a Reliable Tool-Calling Agent Loop on OpenRouter"
url: "https://openrouter.ai/blog/tutorials/build-tool-calling-agent-loop/"
date: "2026-09-17"
feed_url: "https://openrouter.ai/blog/feed.xml"
---
A tool-calling agent loop sends the conversation and tool definitions to a model, runs the tool calls the model returns, appends the results, and repeats until the model answers or a stop condition fires. This guide builds that loop in TypeScript with the OpenRouter SDK, then adds an iteration cap, repeated-call detection, model fallback, and history controls.
