---
title: "How to Gate Pull Requests on LLM Evals in CI"
url: "https://openrouter.ai/blog/tutorials/how-to-gate-pull-requests-on-llm-evals-in-ci/"
date: "2026-10-01"
feed_url: "https://openrouter.ai/blog/feed.xml"
---
A one-line prompt change can ship an agent that tells customers the wrong refund window, and nothing in a normal CI pipeline checks what the model says. This guide builds a fixed eval set for a support agent, a script that exits non-zero below a measured threshold, and a GitHub Actions job that blocks the merge when the pass rate drops.
