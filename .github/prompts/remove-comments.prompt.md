---
agent: agent
description: 'Remove unnecessary comments from Playwright tests'
tools: ['edit/editFiles', 'search', 'runCommands', 'runTasks', 'microsoft/playwright-mcp/*', 'problems', 'changes', 'testFailure', 'fetch', 'todos']
model: 'Claude Haiku 4.5'
---

Remove any unnecessary comments from the Playwright tests. Comments should only be used to explain complex logic or non-obvious interactions. Remove comments that simply restate what the code is doing, as this clutters the code and makes it harder to read.
