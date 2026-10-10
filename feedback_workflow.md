---
name: local-git-workflow
description: Save games/projects locally, use git for all version control, push to GitHub
metadata:
  type: feedback
---

**From now on, save all projects as local files instead of Claude Artifacts.**

**Why:** User wants version control and easy rollback capability through GitHub, not reliance on external artifact URLs.

**How to apply:** 
- Save interactive games and projects as `.html` files in the project directory
- Initialize git repos for projects
- Make clean, atomic commits with descriptive messages
- Push to GitHub for backup and version history
- Never use Artifact tool for game/project saves (still fine for research documents, one-offs)
