# project-logs
Communication between members and the LLM Project Manager is stored here.

/logs/            # canonical, append-only
  /sessions/{yyyy-mm}/{session_id}.jsonl
  /daily/{yyyy-mm-dd}.jsonl
/prompts/         # exact prompts used (versioned)
/snapshots/       # hashes of referenced issues/PRs content
/audit/           # non-chat actions (opened issues, labels, proposals)
/meta/            # model, params, prompt versions, bot build info
