# Codex Low-Usage Roblox Skills

This repository retains all 14 Roblox skills. Each skill now has a shorter trigger description and a scope-based execution policy to reduce unnecessary context loading and repeated MCP operations.

- **QUICK:** targeted static and behavior checks for contained fixes; preserve security tests when relevant.
- **STANDARD:** relevant tests and focused Studio playtest, with visual inspection for scene/UI changes.
- **FULL:** broad regression, device matrix, screenshots and profiling for major refactors/releases or explicit comprehensive requests.

Routing: UI -> scenario-roblox-ui; environment -> scenario-roblox-environment; NPC/gameplay -> scenario-roblox-gameplay; networking/cash -> scenario-roblox-networking; persistence -> scenario-roblox-data. Use scenario-roblox-expert for actual Studio MCP orchestration and multi-domain audits.

These guidance changes do not directly fix the original macOS-only Python toolkit on Windows and do not guarantee any particular percentage of usage savings. Reinstall the skills in Codex after merge and restart Codex so locally installed copies refresh.
