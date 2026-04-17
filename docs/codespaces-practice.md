# Codespaces Practice

**Name:** Elham Hasani Alavy  
**Date:** April 17, 2026

## Initial Observations
- What felt straightforward?
Launching the Codespace was simple — clicking the green Code button and selecting "Create codespace on main" opened a fully configured VS Code environment in the browser within a couple of minutes. Running `python scripts/hello.py` in the integrated terminal worked exactly like a local setup.

- What felt unfamiliar?
The Source Control panel workflow (staging individual files with the + button, writing a commit message, then clicking Sync Changes) was different from using `git` commands directly in the terminal. It took a moment to locate all the panel icons in the Activity Bar.

- Where is the Source Control panel located?
The Source Control panel is located in the left Activity Bar, represented by a branching icon (third icon from the top). It can also be opened with the keyboard shortcut `Ctrl+Shift+G` (or `Cmd+Shift+G` on Mac).

## Understanding Git Workflow
Explain in 2–3 sentences the difference between:
- Local workspace (Codespace)
- Remote repository (GitHub.com)

The local workspace (Codespace) is a cloud-based virtual machine where files are actively edited and code is executed. It acts as a temporary working environment — changes made here exist only in that workspace until they are committed and pushed. The remote repository on GitHub.com is the permanent, shared record of the project; pushing commits transfers the saved snapshots from the local workspace to GitHub, making them visible to collaborators and preserving them beyond the lifetime of the Codespace.
