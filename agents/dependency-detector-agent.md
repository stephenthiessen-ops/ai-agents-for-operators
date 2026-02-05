# Dependency Detector Agent

## Purpose
Identify dependency hotspots and critical path risk across initiatives.

## Inputs
- issues with links/parentage
- target dates
- dependency labels (blocks/is blocked by)
- team ownership

## Output
- Top dependency clusters (grouped)
- Critical path candidates (near-term + high dependency density)
- “At risk” handoffs (ownership mismatch + due proximity)
- Suggested coordination actions (align sequencing / escalate / clarify contract)

## Guardrails
- Must not infer organizational intent
- Must not require new tooling; outputs should be usable in Jira/Notion
