# TASK
GOAL: Rebrand Memo-star → "Code Recall" and refocus positioning on "Persistent memory for coding agents"
NOW: Full deep rename done (entry file coderecall.js, all markers CODE-RECALL, env CODE_RECALL_*, ~/.coderecall, [coderecall] prefix, npm pkg coderecall); verified end-to-end
NEXT: commit on rebrand branch, open PR, close superseded PRs #5/#6, rename GitHub repo → code-recall
UPDATED: 2026-06-10T20:00:00+08:00

## Checklist
- [x] v1.0–v2.0 shipped on master (search, deinit, lint, sessions, git hook, temporal, mcp, graduate, selftest+CI, npm pkg)
- [x] Naming decided: brand "Code Recall", CLI+npm `coderecall`, entry file coderecall.js, full deep rename
- [x] git mv memo.js→coderecall.js, skills/memo-star→skills/coderecall
- [x] Bulk rename: MEMO-STAR→CODE-RECALL, MEMO_STAR_→CODE_RECALL_, memo-star→coderecall, Memo-star→Code Recall, memo.js→coderecall.js, command refs memo X→coderecall X
- [x] Fixed MARKER_BEGIN_RE (regex-escaped memo\.js missed by bulk pass) → marker round-trip verified "in sync"
- [x] Verified: selftest 11/11, sync --all, MCP write_decision, doctor --selftest, install-githook, deinit
- [x] Regenerated repo AGENTS.md with CODE-RECALL markers
- [ ] Commit + push rebrand branch, open PR
- [ ] Close superseded PRs #5 (prepublish gate) / #6 (README polish)
- [ ] Rename GitHub repo erikhuang76821/Memo-star → code-recall
