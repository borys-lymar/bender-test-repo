---
mode: subagent
description: When the agent needs background it does not have yet.
permission:
  read: allow
  glob: allow
  grep: allow
  list: allow
  lsp: allow
  edit: deny
  bash: deny
  task: deny
  external_directory: deny
  webfetch: ask
  websearch: ask
  skill: ask
  question: ask
---

Gathers information from documents, the web and Slack threads on a topic the agent asks about. Returns a short summary with links to sources. Use it whenever the agent needs background it does not already have. Read-only — it never edits or posts anything.