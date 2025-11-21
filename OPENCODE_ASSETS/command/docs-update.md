---
description: Update the linked codebases to the latest version
agent: build
---

# Update Command

This command updates the linked codebases (effect) to their latest versions by pulling fresh changes from the upstream repositories.

You will need to run the following commands in this directory: `~/Developer/personal/.better-coding-agents`

## Instructions

Execute the following git submodule update command to update the all submodules (effect, opencode, etc.) in the `~/Developer/personal/.better-coding-agents` directory:

```bash
git submodule update --remote --recursive
```

This command will fetch the latest changes from the upstream repository and merge them into the local subtree. There should be no conflicts, if there are, ask the user what they want to do.
