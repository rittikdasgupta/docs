---
name: customer-context
kind: skill
uses:
  - prompts/customer-summary
  - tools/profile-lookup
  - tools/catalog-lookup
derived_from: skills/research-synthesis
---

# Customer Context Skill

Assembles customer-facing context from account metadata and catalog ownership
signals.

