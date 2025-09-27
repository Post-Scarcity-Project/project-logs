# Post-Scarcity Project — Logs

This repository is the **public ledger** of all interactions with the Post-Scarcity Project’s AI project manager.  
Every prompt, reply, proposal, and action is recorded here — append-only, verifiable, and permanent.  
Transparency is the price of trust.

## Purpose
- Guarantee **full transparency** of AI ↔ human interactions.  
- Provide a **public audit trail** of decisions, proposals, and daily standups.  
- Enable contributors to **verify what was asked and what was answered**, without hidden channels.

## Structure
- **/logs** — JSONL transcripts (daily + sessions)  
- **/prompts** — exact LLM prompts (versioned)  
- **/audit** — recorded project actions (issues, labels, proposals)  
- **/meta** — model + build information  

## Guarantees
- **No force pushes.** History cannot be rewritten.  
- **All commits signed.** Ledger integrity is cryptographically verifiable.  
- **No redactions** except for secrets or illegal content (marked `[REDACTED: reason]`).  
- **Hashes everywhere.** Every message references prompt/output hashes for reproducibility.

## How to Use
- Browse `/logs/daily/` for day-by-day summaries.  
- Browse `/logs/sessions/` for full transcripts of interactions.  
- Check `/audit/` for proposals, task creation, and other project actions.  
- Verify any bot response by following its `logged:` footer back to the corresponding JSONL line here.

---

**If it isn’t logged here, it didn’t happen.**
