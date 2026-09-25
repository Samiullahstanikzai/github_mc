---
agent: 'workspace'
model: GPT-4o
description: 'Performs a strict code review based on team standards'
---

Your goal is to review the code provided in the active editor pane.

Please evaluate it against the following criteria:
1. Check for memory leaks or unclosed streams.
2. Verify that variable naming follows camelCase conventions.
3. Suggest performance improvements if loops are nested.

If issues are found, format your suggestions as a clean bulleted list.
If no issues are found, reply with `No issues found.`
