# SS14 Fork Development Instructions

This repository is a custom Space Station 14 fork
using C#, RobustToolbox, ECS, and YAML prototypes.

## Rules
- Always Inspect existing implementations before writing code.
- Always Follow this fork's coding conventions.
- Always Reuse existing systems and components where possible.
- Always Respect client/server/shared code boundaries.
- Always Try to keep gameplay changes in YAML, avoid changing C# code where possible.
- Never generate Assets from scratch unless requested to, instead use similar assets or the ones User tells to use.
- Never modify RobustToolbox unless explicitly requested.
- Never modify Git submodules or dependencies without approval.
- Never overwrite unrelated changes.
- Never commit or push without explicit permission.

## Workflow
1. Identify relevant existing files and patterns.
2. Propose an implementation plan.
3. Make focused changes.
4. Run relevant build or test commands.
5. Report changed files, validation results, and any remaining issues.

Do not claim a build or test passed unless it was executed successfully.s