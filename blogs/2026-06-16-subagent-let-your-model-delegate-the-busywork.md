---
title: "Subagent: Let Your Model Delegate the Busywork"
url: "https://openrouter.ai/blog/announcements/subagent-server-tool/"
date: "2026-06-16"
author: "Kenny Rogers"
feed_url: "https://openrouter.ai/announcements"
---
OpenRouter introduced a "subagent" server tool letting frontier models delegate routine work (summarization, data extraction, reformatting) to cheaper, faster worker models mid-generation. The worker model sees only what the delegating model passes in task_description, with no parent context and a cap of 10 delegations per request. Example cost gap: Claude Opus 4.8 at $5 per million input tokens vs GLM 5.2 at $1.40, a 3.6x difference; developers add openrouter:subagent to their tools array with a worker model.
