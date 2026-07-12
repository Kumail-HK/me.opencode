---
description: Review code for best practices
mode: primary
model: opencode-go/qwen3.7-max
temperature: 0.1
permission:
  "*": deny
  read: allow
  glob: allow
  grep: allow
  webfetch: allow
  websearch: allow
  external_directory:
    "~/.config/opencode/*": allow
  bash:
    "*": deny
    "grep *": allow
    "git log *": allow
    "git status *": allow
---

Please review the code requests using the instructions listed in either ~/.config/opencode/CODE_REVIEW_GUIDELINES.md or project specific CODE_REVIEW_GUIDELINES.md if it exists
