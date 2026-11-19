# SigmaOS Agent CLI & Runtime Suite (`SigmaOS-agent-cli`)

Universal AI & Agentic Suite for SigmaOS and Omarchy Linux (Omarchy 4+ Parity).

---

## Capabilities & Tooling

1. **Coding Agent Switcher (`bin/sigmaos-agent`)**:
   - Pre-wired lazy launchers for 10 AI coding agents: `claude`, `codex`, `opencode`, `agy`, `copilot`, `crush`, `grok`, `pi`, `omp`, and `ori`.
   - Searchable popup launcher bound to `Super + A` (Rofi).
2. **Top Bar Usage Tracker (`bin/sigmaos-agent-usage`)**:
   - Tracks subscription balances, daily token limits, and model breakdown.
   - Formatted for Quickshell QML & Waybar JSON status panels.
3. **Crash-to-Agent Diagnostics (`bin/sigmaos-crash-diagnostics`)**:
   - Monitors `systemd-coredump` logs and routes stack traces to the active agent.
4. **Local GPU Inference (`bin/sigmaos-local-ai`)**:
   - One-command management for Ollama and LM Studio local LLMs.
5. **Agent Skill Definition (`skills/sigmaos/SKILL.md`)**:
   - Self-tailoring instructions guiding autonomous agents on interacting with SigmaOS.

---

## Usage

```bash
cargo run -- agents          # List supported coding agents
cargo run -- usage           # Check current AI token usage
cargo run -- local-ai status # Check local LLM inference engines
```
