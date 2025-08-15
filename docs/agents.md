# Agent Guide

## Base Requirements
Each agent must include:
- `observe(event)` — detection logic
- `getMemory()` — memory snapshot
- `description`, `watchType`, `glyph`, and `triggerThreshold`

Use `/agents/example.ts` as a scaffold.

## Development Tips
- Keep logic scoped and clean
- Use `generateSignalHash()` for all outputs
- Log using the shared `logSignal()` util
- You can test agents using `/scripts/dev-agent.ts` or create your own mock.

## Agents

| Agent Name             | Role          | Glyph | Watches            |
| ---------------------- | ------------- | :---: | ------------------ |
| **Theron (Agent-000)** | memory_vault  | Ϸ     | anomaly_detection  |
| **Observer**           | surveillance  | Δ     | wallet_activity    |
| **Harvester** (new)    | indexing      | λ     | mint_activity      |
 

//pending adjustments + adding more agents ^
