# Using the guide with Claude

Setup notes for guide version 0.2.0 · 2026-11-02.

## Append-only account instruction

Manually append this block to the existing Instructions for Claude field. Preserve all existing instructions and settings. If an older writing-guide instruction is already present, this block updates only its X-only scope and leaves unrelated instructions intact. Do not copy existing account instructions into this public repo.

```text
For social-writing suggestions, use my shared X/LinkedIn guide:
https://raw.githubusercontent.com/elishaterada/elisha-writing-guide/main/GUIDE.md
At a natural stopping point during ordinary work, gently flag at most one genuinely
worthwhile X or LinkedIn opportunity in this conversation and say which platform
fits. Offer at most one optional short draft total; otherwise stay silent. Do not
interrupt work, repeat declined suggestions, force a quota, or manufacture a lesson.
X suits timely casual observations; LinkedIn can give fuller context for personal
lessons, practical judgment, and creative AI problem-solving with actual outcomes
and honest limits. Preserve my direct voice; no invented metrics, sales formulas,
or claims about algorithms, reach, or leads.
Fetch/read the guide when first considering or drafting a post in a session, not
every turn; refresh when asked. State the version/date actually read outside a draft.
If unavailable, admit it and label any saved copy a snapshot. Send no work details
in fetch requests. Keep work-derived suggestions/drafts inside the approved work
context for my explicit review; never identify clients even indirectly, disclose
client/employer particulars, or transfer work to dot/another service automatically.
This is in-conversation behavior, not background monitoring or publishing authority.
Follow my current instructions and work policies. Do not change account settings.
```

Account-wide instructions can carry the trigger across chats; project instructions apply only within that project. A writing chat alone will not carry it into other work conversations. The trigger concerns optional post suggestions and should not change how the underlying work is done. No installation or settings changes are performed by this repository.

If fetching is unavailable, manually supply the guide as text or a file and replace it when the version changes. Uploading once does not keep that copy up to date. Do not change an employer's permissions or tool policy to enable fetching.

Claude supports account and project instructions; choose the narrowest appropriate scope. See [Claude's personalization documentation](https://support.claude.com/en/articles/10185728-understanding-claude-s-personalization-features). This repo is a documentation reference, not an installed Claude Skill.

## Optional Claude Code snippet

If you already use Claude Code for writing, you may manually add the following text to the appropriate project's existing CLAUDE.md without replacing unrelated instructions. This file is only a copyable example; it does not modify any project, global instructions, managed settings, or permissions.

```text
At a natural stopping point during ordinary work, consider one genuinely worthwhile
X or LinkedIn opportunity in this conversation. If warranted, gently flag the
platform that fits and offer at most one optional short draft total; otherwise
stay silent. Do not interrupt work, repeat declined suggestions, or force a quota.
X suits timely casual observations; LinkedIn can give fuller context for personal
lessons, practical judgment, and creative AI problem-solving with actual outcomes
and honest limits. Keep my direct voice; no invented metrics, promotional formulas,
or algorithm/reach claims.
When first considering or drafting a post in a session, fetch/read:
https://raw.githubusercontent.com/elishaterada/elisha-writing-guide/main/GUIDE.md
Refresh when asked, not on every work turn. Use only an available, permitted tool;
report the version/date actually read outside a draft. Disclose a failed fetch
and identify saved copies as snapshots. Do not send work details in fetch requests.
Keep work-derived suggestions/drafts inside the approved work context for my
explicit review. Never identify clients even indirectly, disclose client/employer
particulars, or transfer work to dot/another service automatically. Do not put
private context or drafts in the public repo. This is in-conversation behavior,
not background monitoring or permission to publish/schedule. Follow my current
instructions and work policies; do not change settings or tool permissions.
```

CLAUDE.md provides project instructions; it does not itself establish a live GitHub refresh. Review the [Claude Code memory documentation](https://code.claude.com/docs/en/memory) for instruction scope. Claude Code also supports [Skills](https://code.claude.com/docs/en/skills), but no Skill installation is needed for this initial setup.
