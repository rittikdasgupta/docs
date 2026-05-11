---
name: sql-analysis
kind: skill
uses:
  - prompts/sql-review
  - tools/query-linter
  - tools/lineage-fetcher
requires:
  - tools/catalog-lookup
derived_from: skills/research-synthesis
---

# SQL Analysis Skill

Reviews SQL and schema changes before merge. Focuses on tenant scoping,
parameterization, performance risk, and rollback clarity.

