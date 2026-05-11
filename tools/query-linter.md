---
name: query-linter
kind: tool
requires:
  - tools/catalog-lookup
---

# Query Linter

Checks SQL snippets for tenant filters, unsafe string interpolation, broad
selects, and missing index hints.

