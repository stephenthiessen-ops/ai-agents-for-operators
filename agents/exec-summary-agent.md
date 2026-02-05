# Executive Summary Agent

## Purpose
Generate a concise, decision-oriented weekly portfolio brief.

## Inputs
- initiative/epic snapshot with:
  - Delivery Confidence Score (current + prior)
  - band (Green/Yellow/Red)
  - blocked duration, scope volatility, dependency density
  - days to target
  - short status notes (curated)

## Output (1 page)
1. Portfolio snapshot (counts, biggest movers)
2. Top risks (ranked; include drivers)
3. Positive momentum
4. Decision prompts (explicit trade-offs)

## Guardrails
- Must not alter the system of record
- Must not assign commitments
- Must not invent causes not supported by signals
- Must use consistent headings and max length

## Success Criteria
- Leaders can make/assign decisions without reading raw tickets
