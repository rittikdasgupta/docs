---
name: incident-triage
kind: skill
uses:
  - prompts/incident-briefing
  - prompts/runbook-update
  - tools/log-search
  - tools/runbook-fetcher
implements: prompts/incident-briefing
---

# Incident Triage Skill

Turns operational symptoms into a focused incident summary and next diagnostic
step.

