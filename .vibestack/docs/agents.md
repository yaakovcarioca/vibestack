# Doc agents

## Purpose
Production-grade guidance for agents in the Vibestack ecosystem.

## Scope
This docs document is part of Vibestack, a universal context operating system for AI engineering. It provides deterministic guidance for agents.

## Core Contract
- Define inputs, outputs, and non-negotiable constraints before implementation.
- Keep boundaries explicit and stable across model/runtime changes.
- Optimize for token efficiency using high-signal, reusable context modules.
- Prefer modular composition over implicit coupling.
- Record material decisions in persistent memory artifacts.

## Engineering Standards
- Include tradeoff analysis and rollback paths for major changes.
- Use measurable acceptance criteria.
- Separate policy from implementation details.
- Keep guidance runtime-agnostic and vendor-neutral.

## Compatibility
This artifact is designed for Claude Code, Gemini CLI, Codex, Cursor, OpenClaude, Ollama, OpenHands, Roo, Cline, Aider, and OpenClaw adapters.

## Governance Hooks
- Link related rules under `.vibestack/rules`.
- Map execution flow under `.vibestack/workflows`.
- Capture outcomes under `.vibestack/memory`.

## Anti-Patterns
- Embedding provider-specific assumptions in core logic.
- Oversized monolithic prompts replacing semantic modules.
- Untracked exceptions and undocumented architecture drift.
- Hidden mutable state not persisted in shared memory ledgers.

## Review Cadence
Review quarterly for drift, stale assumptions, and compatibility regressions.
