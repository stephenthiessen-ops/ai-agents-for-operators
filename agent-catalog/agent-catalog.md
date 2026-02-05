# Agent Catalog

| Agent | Purpose | Primary Inputs | Outputs | Risk Tier |
|------|---------|----------------|---------|----------|
| Executive Summary Agent | Turn delivery telemetry into a 1-page weekly brief | scored snapshot (DCS, volatility, blockers) | exec brief + decision prompts | Tier 2 |
| Risk Radar Agent | Detect emerging risks earlier than status reporting | trend deltas + risk signals | ranked risks + drivers + actions | Tier 2 |
| Intake Triage Agent | Normalize intake, reduce back-and-forth, route correctly | intake form/ticket text + metadata | structured ticket fields + routing | Tier 2 |
| Dependency Detector Agent | Identify dependency clusters and critical path | issues + links + targets | dependency map + hotspots | Tier 2 |
| Decision Log Agent | Convert meeting notes into decisions & follow-ups | notes/transcript + context | decision log entry + owners + due dates | Tier 1–2 |

Risk tiers align to governance controls (see `/guardrails`).
